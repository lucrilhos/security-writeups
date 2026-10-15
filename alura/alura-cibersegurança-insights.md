alura - cibersegurança: fundamentos insights

exemplos de barreiras de segurança nos sistemas:
- vpns que fazem um tunel seguro entre duas (ou mais) conexoes
- firewalls como intermedio e mediador de conexoes
- siem's correlacionam os eventos e logs 

modelo osi camadas respectivas:
- física
- ligação de dados (enlace)
- rede
- transporte
- sessao
- apresentação
- aplicação

			(switch)			(roteador)
*(empacota) dispositivo fisico/bits brutos---endereço mac/frames---endereçamento ip/roteamento---protocolo tcp/udp---segmenta usuarios/login---criptografia & descriptografaia/conversao de dados tabela ascii---protocolos http, ftp, smtp (desempacota)---> resposta ao usuario

modelo tcp/ip camadas respectivas:
- aplicação
- transporte
- rede
- interface de rede
protocolos:
- tcp (comunicação e integridade dos dados)
- udp (streaming/jogos pela agilidade)
- http (comunicações web)
- htpps (comunicações web criptografadas)
- dns (conversao de dominios pra ip)
- ssh (security shell - comunicação criptografada)
- ftp (transferencia de arquivos)
- icmp (teste de conexao entre hosts e redes)

*camada de enlace
- ataques de arp spoofing e mac flooding
- endereço mac
- switching

endereço mac (
- tamanho de 48 bits
- identificador unico de cada dispositivo  (fabricador | dispositivo)
- separado em 6 'conjuntos de numero e letra' 00:0A:0B:0C:0D:0E

*camada de rede
- protocolo ip
- roteamento
- ataques de ddos, ip spoofing (man in the middle), configuração de firewall

*todo pacote de dados tem um cabeçalho com informações cruciais para o funcionamento da rede
	- ipv4 < com mais divisoes de informações
	- ipv6 > com menos divisoes de informaçoes

*whireshark

cabeçalhos ipv4
- padding pra otimização de informações
- de 20 ate 60 bytes
- o tamanho total do cabeçalho é sempre multiplo de 32 bits (4 bytes)
*cabeçalhos ipv6 tem tamanho fixo


