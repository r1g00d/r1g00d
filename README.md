<p align="center">
  <img src="./assets/header.svg" alt="r1g00d — red team entry-level, em formação" width="100%">
</p>

<p align="center">
  <a href="https://r1g00d.github.io">
    <img src="https://img.shields.io/badge/%3E__-ENTRAR%20NO%20SISTEMA-FF1E3C?style=for-the-badge&labelColor=000000" alt="ENTRAR NO SISTEMA">
  </a>
  <br>
  <a href="https://r1g00d.github.io"><b>r1g00d.github.io</b></a> — portfólio interativo em formato de terminal
  <br>
  <sub>Há <b>3 flags de CTF</b> escondidas no site. Boa caçada.</sub>
</p>

---

### `$ whoami`

```text
nome ........ João Victor Rigo  [r1g00d]
função ...... Red Team entry-level, em formação
base ........ Franca, SP — Brasil
formação .... Engenharia da Computação — Unifran (em andamento)
prática ..... HackTheBox · TryHackMe · PortSwigger Web Security Academy
comunidade .. programa Hackers do Bem
objetivo .... primeira vaga em pentest real, com supervisão
```

> **Em português claro:** sou profissional de suporte de TI em transição para segurança ofensiva — a área que testa sistemas como um atacante faria, com autorização, para encontrar falhas antes dos criminosos.

---

### `$ cat kill_chain_da_carreira.txt`

Kill chain é a sequência de etapas de um ataque. Aqui ela descreve a minha trajetória.

```text
[1] RECON ........ Técnico em Informática — ETEC (2020)
                   Aprendiz de T.I — Jussara S.A.
        |
[2] ENUMERAÇÃO ... Magazine Luiza / Netshoes — operações e suporte
                   Solutis — Projeto Sabesp, 30 unidades atendidas
        |
[3] EXPLORAÇÃO ... PRE SECURITY (TryHackMe) — concluído
                   HackTheBox · Hackers do Bem · TR1GG3R SIEM
        |
[4] PIVOT ........ eJPT — em andamento
        |
[5] OBJETIVO ..... OSCP   (CompTIA Security+ no caminho)
```

---

### `$ cat experiencia.log`

| Empresa | Cargo | Período |
|---|---|---|
| Positivo Tecnologia S.A. | Técnico de Suporte Jr. (Field Service) | 2025-10 → atual |
| Solutis Tecnologias (Projeto Sabesp) | Analista de Suporte Pleno | 2024-09 → 2025-02 |
| Magazine Luiza S.A. (Netshoes) | Assistente Pleno de Operações Especiais / Suporte | 2022-11 → 2024-09 |
| Jussara S.A. | Aprendiz de T.I | 2021-02 → 2022-01 |

---

### `$ cat findings.md`

Em um relatório de pentest, cada descoberta é um *finding* com nível de severidade. Estes são os meus projetos.

#### `[ALTA]` [TR1GG3R SIEM](https://github.com/r1g00d/trigger_siem)

IDS/WAF integrado a um SIEM, escrito em **Python puro, sem nenhuma dependência externa**. Fica na frente de uma aplicação web, identifica ataques em tempo real e reage sozinho.

- Detecta SQL injection, XSS e path traversal
- Bloqueia força bruta: **ban de 300 s após 5 tentativas**
- Reconhece scanners como sqlmap, nikto, hydra e nmap
- Alerta por e-mail e rate limiting com SQLite

```text
$ trigger_siem --status
[+] engine ........ python3 (stdlib only)
[+] detecção ...... sqli · xss · path traversal · brute force · scanners
[+] resposta ...... ban 300s após 5 tentativas | rate limit (sqlite)
[+] alertas ....... e-mail
[*] status ........ ATIVO
```

#### `[INFORMATIVA]` [Solo Nativo](https://github.com/r1g00d/solo-nativo)

Plataforma educacional sobre geografia, biomas e geopolítica, desenvolvida como projeto acadêmico na Unifran. Atuei como **Product Owner e desenvolvedor**, com documentação em UML, BPMN e normas ABNT.

---

### `$ nmap -sV r1g00d`

```text
Starting Nmap scan on r1g00d
PORT      STATE     SERVICE        VERSION
22/tcp    open      linux          Kali, Bash
53/tcp    open      redes          TCP/IP, DNS, DHCP, VPN
80/tcp    open      web-pentest    Burp Suite, PortSwigger
389/tcp   open      windows        Windows 10/11, Active Directory
443/tcp   open      python         automação, stdlib
1337/tcp  open      offensive      Nmap, Metasploit, HackTheBox, TryHackMe
8080/tcp  open      osint          Shodan, Sherlock, Maigret
9200/tcp  filtered  siem           Sentinel, Splunk, QRadar
31337/tcp filtered  c++            em estudo

Nmap done: 1 host up
```

<sub><b>open</b> = uso no dia a dia · <b>filtered</b> = em estudo</sub>

---

### `$ ./contato.sh`

<p>
  <a href="https://www.linkedin.com/in/jvrigo/"><img src="https://img.shields.io/badge/LinkedIn-jvrigo-E6E3DA?style=flat-square&labelColor=000000" alt="LinkedIn"></a>
  <a href="mailto:r11gg0d@gmail.com"><img src="https://img.shields.io/badge/E--mail-r11gg0d%40gmail.com-E6E3DA?style=flat-square&labelColor=000000" alt="E-mail"></a>
  <a href="https://tryhackme.com/p/r11gg0d"><img src="https://img.shields.io/badge/TryHackMe-r11gg0d-FF1E3C?style=flat-square&labelColor=000000" alt="TryHackMe"></a>
  <a href="https://r1g00d.github.io"><img src="https://img.shields.io/badge/Site-r1g00d.github.io-19E6FF?style=flat-square&labelColor=000000" alt="Site"></a>
</p>

LinkedIn: [linkedin.com/in/jvrigo](https://www.linkedin.com/in/jvrigo/) · E-mail: [r11gg0d@gmail.com](mailto:r11gg0d@gmail.com) · TryHackMe: [r11gg0d](https://tryhackme.com/p/r11gg0d) · Site: [r1g00d.github.io](https://r1g00d.github.io)

---

<p align="center"><img src="./assets/sigil.svg" alt="" width="32"></p>

<p align="center"><code>[EOF] Só ataco o que tenho autorização para atacar.</code></p>
