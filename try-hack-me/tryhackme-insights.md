tryhackme - insights & resumos

modulo 1 - offensive security:
- segurança ofensiva é o ato de pensar como um hacker nao etico para penetrar um sistema x considerando os pontos fracos que podem ser usados contra o mesmo
- comando dirb *http://alvo.com* exibe diretorios ocultos ou nao linkados publicamente

modulo 2 - defensive security:
- a segurança defensiva visa a vigilia, detecção e investigação de ataques, para corresponde-los antes que aconteçam
- Security Operations Center (SOC) is a team of IT security professionals tasked with monitoring, preventing , detecting , investigating, and responding to threats within a company’s network and systems.

modulo 3 - careers in cyber
analista de segurança - analisa a segurança cibernetica da empresa por meio de relatorios continuos acerca dos sistemas da empresa, documentações sobre medidas de segurança a serem implementadas ou alteradas. é necessario estar inteirado sobre a tendencia de ataques ciberneticos, proteção de dados da empresa e adoção de medidas protetetivas.
engenheiro de segurança - o engenheiro se baseia em dados fornecidos pelos setores para contornar ataques, tambem implementar medidas de segurança tanto para servidores web quanto para aplicações. tem uma leve enfase na parte de redes, por ser necessario o monitoramento dos sistemas para mante-los atualizados e protegidos.
respondente de incidente - tambem chamado de "socorristas", essa area é centrada na eficiencia e rapidez, por isso é importante ser um profissional preparado com planos e políticas para conseguir aplica-los de prontidao durante um ataque cibernetico. sua função é identificar, recuperar e reconhecer os ataques para proteger os dados que estao sendo cogitados. tem suas responsabilidades cruciais para a empresa, envolvendo a estabilidade financeira, reputação da empresa e proteção dos dados. sempre importante manter planos futuros e relatorios *após* os incidentes.
examinador forense - detetive. você coleta e analisa evidencias digitais para cybercrimes. é essencial saber o vinculo do incidente com os procedimentos legais que serao necessarios adotar ao analisar um caso.
analista de malware - com uma base solida em programação (principalmente de baixo nivel como C e Assembly), o analista de malware é um engenheiro reverso, estudando programas maliciosos e como eles funcionam para documenta-los. sua tarefa gira em torno da conversao de programas compilados para codigos legiveis, assim desvendando como sua estrutura funciona desde a raiz, para compreende-los e descobrir como detecta-los
testador de penetração - o 'hacking etico'. um individuo invade sistemas e softwares de uma empresa para identificar vulnerabilidades e brechas por meio de um hacking sistematizado. é responsavel pelos insights para riscos iminentes e evita-los.
caminhoneiro vermelho - semelhantes aos pentestings, sao hackers contratados para serem adversarios da defesa imposta pela empresa. de tal forma, eles  testam a capacidade da empresa de responder e reconhecer invasores ou riscos em potencial nos sistemas. relatam insights com dados acionaveis desempenhando o papel de um criminoso cibernetico.

Habilidades de pesquisa - trilha de cybsergurança

- ferramentas como *Shodan* têm a funçao de escanear ip's, servidores, dominios para localizar e pontuar cada informação relevante de tudo que está conectado a rede publica de internet. é possivel especificar ip, país, organizaçao, port (porta q o servidor esta conectado) e nome do host para consulta
- *VirusTotal* tem os mecanismos antivirus linkados a uma pontuação que a comunidade dá para url's, dominios ou hash de arquivos maliciosos. é um recurso popular para analise de arquivos ou links suspeitos
o CVE (dicionario de vulnerabilidades e exposições comum) é um dicionario de todos os males que podem atingir uma informação protegida. cada vulnerabilidade recebe um identificador unico. ex: cve-2006-192 cve-ano-numero. ex de vulnerabilidades conhecidas: Heartbleed, React2Shell e Log4Shell. a pontuação de cada vulnerabilidade se baseia em fatores como complexidade, impacto e a disponibilidade de alguem para solucionar tal problema
- site *ExploitDb* para conhecimento sobre vulnerabilidades
- explorar comando manual (man) no terminal do linux
- há repositorios maliciosos no github que buscam te convencer a clonar o repositorio na sua maquina e assim infectar o computador. muitos deles estao disfarçados como Poc's (provas de conceito)
- Uma Prova de Conceito geralmente é um pedaço de código ou um aplicativo usado para demonstrar que uma ideia ou teoria é possível. Provas de conceito são frequentemente usadas para demonstrar vulnerabilidades
- 
