anotações - redes onboarding (curso alura)

fluxo de informações:

Um cliente ou servidor envia um pacote.
Esse pacote chega ao switch ao qual o cliente/servidor está conectado.
Se o destino do pacote for em outra rede (por exemplo, outro servidor em uma rede diferente ou a internet), o switch o encaminha para o roteador.
O roteador recebe o pacote e, com base no endereço de destino, sabe para onde encaminhá-lo.
Se o pacote estiver indo para fora da rede interna (para a internet, por exemplo), ele passará pelo firewall.
O firewall verifica suas regras. Se a comunicação for permitida, ele deixa o pacote passar; caso contrário, ele o rejeita.
Depois do firewall (e possivelmente outro roteador de borda), o pacote segue seu caminho para o destino externo.

- interface de loopback é uma interface de rede que permite a comunicação host entre cliente e servidor 
	- o endereço 127.0.0.1 só funciona localmente na sua maquina. nao é possivel acessar esse endereço na maquina de terceiros
	
- endereço mac é o endereço fisico da sua rede. geralmente encontrado em roteadores	

- documento rcf descreve os tipo de endereço ip reservados
- a faixa de ip privados, de acordo com o documento rcf, é 172.16.0.0/12. se o endereço de ip cabe nessa faixa ele é um endereço privado

ipv4 = protocolo que exige a necessidade de reutilização e mascara nos ip
usa protocolo dhcp ou configuração manual (modelo de formato: 142.250.0.102
ipv6 = todo dispositivo consegue ter um endereço unico
realiza autoconfiguração (modelo de formato: 2800:3f0:4001:838::200e)

- o dns (domain name system) é um tradutor de nomes/dominios de site em endereços de ip. (ex: o site youtube tem um ip por tras dele. atraves do servidor dns vc consegue acessar o youtube pelo nome youtube, nao sendo necessario saber o ip do site)

servidor dns recursivo: se encarrega do trabalho de busca sobre um ip de um dominio q vc pergunta. se o ip estiver no cache do servidor, ele responde.
autoritativo: servidor responsavel por um dominio especifico por ser o 'dono' daquele ip. consegue responder uma consulta feito por um dns recursivo.

o comando 'ping' ecoa o icmp entre duas conexoes (uma como request outra como reply) para ver se um dominio/ip esta respondendo
- nao diagnostica um dominio fora do ar, só testa a resposta

*o roteador age quando há conexoes com REDES diferentes. em conexoes do mesmo ambiente a função é voltada pro switch	

https://aws-latency-test.com/ --- site que verifica a qualidade do envio de pacotes por entre o mundo 

ospf - utilizado mais "dentro de casa". comum em redes internas (utiliza algoritmo de djkistra)
bgp - protocolo que usa tcp externamente pelos provedores de internet para haver conversação entre tabelas de rota

o comando cat /etc/services - essa linha de comando demonstra as portas e protocolos atribuidas a sua maquina
	- pesquisar os serviços que se atribuem a portas especificas (ex: port 80 e http)
	
o comando curl traz o conteudo de um servidor/dominio especifico
	- curl -Is https://www.exemplo.com.br | head -n 1 capta só o status code do servidor (no ar/funcionando)

o comando 'netstat' exibe o endereço local e o ip visado junto do protocolo e state

*Conforme a RFC 1700 as portas até 1024 são reservadas. Geralmente, são reservadas para os processos do sistema (daemons) ou para os programas executados por usuários com privilégios.

*nao existem mais ips publicos disponiveis no modelo ipv4. os que existem ja sao reservados
NAT (network address translation) - realiza a  conversao do seu ip privado para um publico no apos atravessar o roteador (na borda da rede), assim possibilitando a troca de pacotes entre o ip destinatario e o seu. como ja indica a sigla, é um tradutor que atua entre a sua rede (local) com outras pelo mundo (externa)

*amazon lightsail é um criador de instancias (servidores virtuais remotos) que simplifica a implementação de app's ou recursos na nuvem, tem uma facilidade de gestao superior comparado a outras vps (virtual private servers)


