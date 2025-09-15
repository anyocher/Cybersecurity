# Cybersecurity
Repository for educational purposes


1. Fundamentos de Computação e Redes
Antes de mergulhar em segurança, é essencial entender o funcionamento dos sistemas e redes.
Sistemas Operacionais: Windows, Linux (especialmente comandos básicos no terminal).
Redes de Computadores:
Modelo OSI e TCP/IP
Protocolos: HTTP, HTTPS, DNS, SMTP, FTP, SSH
Endereçamento IP, sub-redes, roteamento básico
Conceitos básicos de segurança:
Confidencialidade, Integridade e Disponibilidade (CIA Triad)
Criptografia (simétrica, assimétrica, hashes)
📚 Recurso sugerido: Curso básico de redes (Cisco Packet Tracer, por exemplo) e laboratório com máquinas virtuais.
2. Introdução à Segurança da Informação
Tipos de ataques: Phishing, Malware, Ransomware, DDoS, Engenharia Social.
Ferramentas iniciais: Wireshark (análise de pacotes), Nmap (scanner de rede).
Normas e frameworks: ISO 27001, NIST, OWASP Top 10.
3. Pentest e Ethical Hacking (Laboratórios controlados)
Pentest básico:
Reconhecimento (Whois, Shodan, Nmap)
Exploração de vulnerabilidades (Metasploit, SQL Injection, XSS)
Pós-exploração (coleta de informações, manutenção de acesso em ambiente simulado)
Plataformas de prática:
Hack The Box, TryHackMe, OverTheWire
DVWA (Damn Vulnerable Web Application)
⚠️ Importante: somente em ambientes autorizados.
4. Segurança em Sistemas e Aplicações
Hardening de sistemas: firewalls, políticas de senha, atualizações.
Segurança em aplicações web: OWASP Top 10 (SQL Injection, XSS, CSRF).
Segurança em APIs: autenticação, rate limiting, JWT seguro.
Ferramentas: Burp Suite, OWASP ZAP.
5. Segurança em Redes e Infraestrutura
IDS/IPS (Snort, Suricata)
VPNs e túneis seguros
Configuração de Firewalls (iptables, pfSense)
Monitoramento de tráfego (NetFlow, SIEMs como Splunk/ELK Stack)
6. Blue Team (Defesa)
SIEM: Splunk, Elastic (ELK), Wazuh
EDR/XDR: monitoramento de endpoints
Incident Response: criação de playbooks
Threat Hunting: análise de tráfego suspeito, IOC (Indicadores de Comprometimento)
7. Red Team (Ataque controlado)
Técnicas avançadas de exploração
Movimentação lateral, privilege escalation
Phishing direcionado (em laboratório)
Exercícios de adversary emulation
8. Áreas Avançadas e Especializações
Malware Analysis e Engenharia Reversa
Forense Digital (memória, disco, rede)
Cloud Security (AWS, Azure, GCP)
IoT/SCADA Security (segurança em dispositivos industriais)
Criptografia aplicada
9. Carreira e Certificações
Certificações iniciais:
CompTIA Security+
Certified Ethical Hacker (CEH)
Intermediárias/avançadas:
OSCP (Offensive Security Certified Professional)
CISSP (Certified Information Systems Security Professional)
CISM (Certified Information Security Manager)
10. Rotina de Estudo
Estudar teoria (livros, cursos) + praticar em laboratórios virtuais.
Participar de CTFs (Capture The Flag) para treinar resolução de problemas.
Seguir notícias de segurança (The Hacker News, KrebsOnSecurity, blogs da Kaspersky, OWASP).


# Trilha Ofensiva — Red Team (Ética e Seguro)

## Objetivo

Fornecer uma trilha de estudos estruturada para quem quer seguir a área de **Red Team / Offensive Security** — do nível iniciante ao profissional — enfatizando princípios éticos, práticas seguras e a importância da colaboração com equipes de defesa (Blue Team / Purple Team).

---

## Sumário

1. Princípios e ética
2. Pré-requisitos (Nível 0)
3. Nível 1 — Fundamentos de Offensive Security
4. Nível 2 — Ferramentas e técnicas (em laboratórios autorizados)
5. Nível 3 — Técnicas avançadas e emulação de adversários
6. Nível 4 — Profissionalização e certificações
7. Habilidades técnicas detalhadas
8. Recursos recomendados
9. Projetos e exercícios seguros
10. Como medir progresso
11. Conselhos especiais para menores de idade

---

## 1. Princípios e ética

* **Consentimento primeiro:** só realize qualquer atividade ofensiva com autorização escrita e escopo definido.
* **Foco em melhoria:** o objetivo do Red Team é identificar falhas para que possam ser corrigidas.
* **Responsabilidade legal e profissional:** ataques não autorizados são crimes; sempre consulte um responsável e o departamento jurídico quando aplicável.

---

## 2. Pré-requisitos (Nível 0)

Antes de qualquer técnica ofensiva, construa fundamentos sólidos:

* **Sistemas Operacionais:** Windows e Linux — uso de terminal, permissões, processos, serviços.
* **Redes:** modelo OSI/TCP-IP, TCP/UDP, HTTP/HTTPS, DNS, NAT, roteamento, sub‑redes e portas.
* **Programação e scripting:** Python, Bash; manipulação de strings, expressões regulares, automação.
* **Conceitos de segurança:** criptografia básica, autenticação/autorização, CIA triad.

**Prática segura:** configure VMs locais (VirtualBox/VMware) e crie uma rede isolada para estudos.

---

## 3. Nível 1 — Fundamentos de Offensive Security

Temas e objetivos:

* **Reconhecimento (OSINT):** aprender a mapear superfície de ataque com fontes públicas (teoria e ética).
* **Mapeamento e discovery:** entender o que é port scanning, fingerprinting (apenas em ambientes autorizados).
* **OWASP Top 10:** estudar vulnerabilidades web e entender impacto/mitigações.
* **Fluxo de um pentest:** planejamento, reconhecimento, exploração (autorizado), pós‑exploração, reporting.

**Exercício:** completar módulos iniciais em plataformas como TryHackMe (rotas de Offensive Basics).

---

## 4. Nível 2 — Ferramentas e técnicas (em labs autorizados)

Aprender a usar ferramentas e técnicas dentro de ambientes de treino:

* **Ferramentas (conceitos e uso em lab):** Nmap, Burp Suite/OWASP ZAP, Metasploit (uso responsável), Wireshark.
* **Exploits e payloads:** pesquisa e estudo de CVEs em ambientes controlados.
* **Pós‑exploração:** coleta de evidências, escalada de privilégios e limpeza ética de artefatos em laboratório.
* **Engenharia social (teoria):** entender vetores e contramedidas; praticar somente em exercícios simulados com consentimento.

**Plataformas:** TryHackMe, Hack The Box, VulnHub, OverTheWire.

---

## 5. Nível 3 — Técnicas avançadas e emulação de adversários

* **MITRE ATT\&CK:** mapear técnicas e práticas conhecidas; construir cenários de emulação.
* **Movimentação lateral e persistência (em sandboxes):** estudar técnicas e como detectá‑las.
* **C2 (Command & Control) em lab:** entender arquiteturas de C2 para avaliar detecção e bloqueio.
* **Planejamento de operações de Red Team:** escopo, regras de engajamento, rollback, comunicação com Blue Team.

**Atividade:** realizar exercícios Purple Team: Red Team simula ataques autorizados; Blue Team pratica detecção e resposta.

---

## 6. Nível 4 — Profissionalização e certificações

* **Certificações práticas:** OSCP (Offensive Security), e cursos práticos SANS (quando possível).
* **Competências não técnicas:** redação de relatórios, gestão de stakeholders, definição de KPIs de teste.
* **Áreas de especialização:** exploit development, social engineering (simulado), cloud penetration testing (AWS/GCP/Azure), IoT/OT security.

---

## 7. Habilidades técnicas detalhadas (estudar + defender)

* Reconhecimento & OSINT
* Exploração web (SQLi, XSS, CSRF) — e contramedidas
* Exploração de serviços e protocolos
* Escalada de privilégios em Windows e Linux
* Movimentação lateral, exfiltration e evasão
* Criação e detecção de C2 (apenas em ambiente controlado)
* Uso do MITRE ATT\&CK para planejamento e reporte

---

## 8. Recursos recomendados

* **Livros:** “The Web Application Hacker’s Handbook” (referência para web), “Red Team Field Manual” (consultar com responsabilidade).
* **Plataformas:** TryHackMe, Hack The Box, VulnHub, OverTheWire.
* **Referências:** MITRE ATT\&CK, OWASP, CVE Details.
* **Canais e notícias:** blogs de segurança, conferências (DEF CON, BSides) e repositórios de writeups.

---

## 9. Projetos e exercícios seguros

* Montar um lab local (Metasploitable, DVWA, máquinas VulnHub).
* Participar de CTFs e escrever *writeups* com foco em mitigação.
* Criar um exercício Purple Team com colegas e documentar as detecções e gaps.
* Produzir relatórios fictícios (structure: resumo executivo, técnicas usadas, evidências, recomendações).

---

## 10. Como medir progresso

* Completar rotas e módulos em plataformas (badges/score).
* Resolver CTFs e publicar writeups educativos.
* Conduzir um exercício autorizado e entregar um relatório com recomendações.
* Obter certificações práticas (quando tiver maturidade técnica e ética).

---
