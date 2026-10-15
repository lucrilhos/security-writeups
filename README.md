# 🛡️ security-writeups

Meu caderno público de estudos em cibersegurança: **writeups** de máquinas e salas (TryHackMe, HackTheBox) e **notas de estudo** dos cursos que estou fazendo, escritas com as minhas palavras.

> Estudante de Ciência da Computação (FIAP) em busca do primeiro estágio em segurança: pentest, análise de malware e ethical hacking. Este repositório registra a jornada, do básico de redes e Linux até as primeiras máquinas resolvidas.

---

## 🎯 O que este repositório promete

- **Aprender em público.** Cada arquivo registra o que estudei, o que pratiquei e o que deu errado no caminho.
- **Síntese, não cópia.** Nada de transcrição de aula ou resposta de exercício: só explicações com as minhas palavras, comandos que rodei e conclusões próprias.
- **Visão de segurança em tudo.** Cada assunto, mesmo os básicos (redes, Linux), termina com a pergunta: *onde isso vira vulnerabilidade, e como se defende?*
- **Ética.** Toda prática é feita em ambientes próprios ou plataformas autorizadas (TryHackMe, HackTheBox). Nada aqui deve ser usado contra sistemas sem permissão.
- **Evolução constante.** As notas mais antigas vão sendo revisadas conforme aprendo mais.

---

## 📂 Estrutura

```
security-writeups/
├── alura/          # notas de estudo dos cursos da Alura
├── try-hack-me/    # notas das trilhas e writeups de salas do TryHackMe
└── hackthebox/     # writeups de máquinas do HackTheBox (em breve)
```

---

## 📚 Conteúdo atual

### Alura

| Nota | Assuntos |
|---|---|
| [Linux](alura/alura-linux.md) | Kernel, estrutura de diretórios (`/etc`, `/var`, `/proc`...), distribuições, comandos básicos de navegação e ajuda |
| [Redes Onboarding](alura/alura-redesonboarding.md) | Fluxo de pacotes (switch, roteador, firewall), loopback, IPv4 vs IPv6, DNS recursivo e autoritativo, NAT, OSPF e BGP, portas, `ping`, `curl`, `netstat` |
| [Cibersegurança: Fundamentos](alura/alura-ciberseguranca-fundamentos.md) | Barreiras de segurança (VPN, firewall, SIEM), modelo OSI e TCP/IP, protocolos, ataques por camada (ARP spoofing, MAC flooding, IP spoofing, DDoS), cabeçalhos IPv4/IPv6 |

### TryHackMe

| Nota | Assuntos |
|---|---|
| [Insights e resumos](try-hack-me/tryhackme-insights.md) | Segurança ofensiva vs defensiva, SOC, carreiras em cyber, ferramentas de pesquisa (Shodan, VirusTotal), CVE |

### HackTheBox

_Em breve: primeiros writeups de máquinas._

---

## 📝 Modelos usados

**Notas de estudo** (cursos):

```markdown
# <Curso> (<plataforma>)

## Conceitos-chave
## Na prática         -> comandos que rodei e o que observei
## Visão de segurança -> como isso é atacado ou defendido
## Dúvidas e como resolvi
```

**Writeups** (máquinas e salas):

```markdown
# <Máquina> - <plataforma> - <dificuldade>

## Reconhecimento       -> nmap, enumeração de serviços e diretórios
## Acesso inicial       -> vulnerabilidade encontrada e como foi explorada
## Escalação de privilégio
## Lições aprendidas    -> o que eu faria diferente, como o sistema se defenderia
```

> Writeups de máquinas **ativas** do HackTheBox não são publicados, respeitando as regras da plataforma. Só máquinas aposentadas.

---

## 🗺️ Roadmap

**Organização**
- [ ] Converter as notas atuais para o modelo acima (seções de prática e visão de segurança)
- [ ] Adicionar prints e saídas de terminal das práticas

**Notas de estudo**
- [ ] Wireshark: capturar uma requisição HTTP e um login via telnet em texto puro
- [ ] Comandos de rede na prática: `telnet`, `nc`, `nmap`, `dig`, `traceroute`
- [ ] Permissões no Linux (`chmod`, `chown`, SUID) e por que importam em escalação de privilégio
- [ ] Criptografia aplicada: hash vs KDF vs criptografia (ligado ao meu projeto [cofre-senhas](https://github.com/lucrilhos/cofre-senhas))
- [ ] OWASP Top 10: uma nota por vulnerabilidade, com exemplo
- [ ] Bash e Python para automação de tarefas de segurança
- [ ] Preparação para a certificação CEH: resumo por domínio

**TryHackMe**
- [ ] Concluir a trilha *Pre Security* e *Cyber Security 101*
- [ ] Primeiros writeups de salas: Nmap, Linux Fundamentals, OWASP Top 10

**HackTheBox**
- [ ] Starting Point (Tier 0 a 2)
- [ ] Primeira máquina aposentada *Easy* com writeup completo

---

## 🔗 Projetos relacionados

- [cofre-senhas](https://github.com/lucrilhos/cofre-senhas): gerenciador de senhas CLI com Argon2id e AES-256-GCM
- [port-scanner](https://github.com/lucrilhos/port-scanner): port scanner em Python feito do zero

---

## 👤 Autor

**Lucas M. Moraes**, estudante de Ciência da Computação (FIAP), focado em cibersegurança.

- GitHub: [@lucrilhos](https://github.com/lucrilhos)
- LinkedIn: [lucas-mendes-473678339](https://www.linkedin.com/in/lucas-mendes-473678339)

> As notas refletem o meu entendimento no momento em que foram escritas e podem conter imprecisões. Correções são bem-vindas via *issue*.
