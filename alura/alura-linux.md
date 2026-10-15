curso_alura - estudando o linux

- O Linux é um "kernel" (nucleo de um sistema operacional) de open source (gratuito e aberto)
ex: de kernels: 

- pasta 'root' no diretorio / é aonde se localiza todos os pacotes e 
propriedades da maquina

#############################

pastas fundamentais para funcionamento:
 /bin → armazenamento de arquivos binários essenciais do sistema.

/boot → armazenamento de arquivos necessários para a inicialização do sistema, incluindo o carregador de inicialização (boot loader) e o kernel do Linux.

/dev → armazenamento de arquivos de dispositivo (device files) que representam dispositivos de hardware, como discos rígidos, terminais e outros periféricos.

/etc → armazenamento de arquivos de configuração do sistema.

/home → armazenamento de diretórios pessoais dos usuários.

/lib → armazenamento de bibliotecas compartilhadas essenciais para binários localizados nos diretórios /bin e \sbin.

/media → ponto de montagem para mídias removíveis (drivers USB, por exemplo).

/mnt → ponto de montagem temporária para sistemas de arquivos. Usado para montar temporariamente outros sistemas de arquivos durante a administração do sistema.

/opt → armazenamento de aplicativos opcionais e pacotes de software adicionais que não fazem parte da instalação padrão do sistema.

/proc → sistema de arquivos virtual que armazena informações sobre os processos em execução e o estado do kernel.

/root → diretório pessoal do usuário root (superusuário).

/run → armazenamento de informações voláteis sobre o sistema desde a última inicialização, como PID files e sockets.

/sbin → armazenamento de binários essenciais para a administração do sistema, necessários para o boot e recuperação do sistema.

/srv → armazenamento de dados específicos de serviços fornecidos pelo sistema.

/sys → sistema de arquivos virtual que fornece informações e interfaces para o kernel do Linux.

/tmp → armazenamento de arquivos temporários criados por aplicativos e pelo sistema. Esses arquivos geralmente são excluídos ao reiniciar o sistema.

/usr → armazenamento de dados de usuário mais instalados pelo sistema, incluindo binários adicionais, bibliotecas e arquivos de cabeçalho.

/var → armazenamento de arquivos variáveis, como logs, filas de email e arquivos de spool.

#############################

Distros (distribuições) do linux:
Debian: é conhecida como uma distribuição estável e com alta confiabilidade por ser uma das mais antigas. Destaca-se por apresentar suporte a múltiplas arquiteturas de hardware, sendo adotada em uma grande variedade de dispositivos como servidores, desktops e sistemas embarcados.
Ubuntu: distribuição bastante popular, concebida a partir do Debian, sendo conhecida por oferecer grande facilidade de uso para usuários pouco familiarizados com distribuições do Linux. Possui versões para desktops, servidores e dispositivos IoT.
Linux Mint: desenvolvida para uso em notebooks e desktops, é reconhecida por sua usabilidade.
CentOS: amplamente utilizada em servidores e ambientes corporativos devido à sua confiabilidade e compatibilidade com aplicações empresariais.

-o . antes dos arquivos geralmente sao de arquvos ocultos

man -k . = encontrar comando para apagar um arquivo/diretorio permnamentemente - exibe todos os

(comando) --help = mostra todas as vertentes do comando no terminal

- colocar / a cada dois pontos volta um diretorio. ex: ./../../ -> volta 2 casas
