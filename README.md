# 🌐 Redes de Computadores & Hardening - Plano de Estudos

# 🎯 Objetivo ao concluir o módulo

Ao finalizar este módulo, devo ser capaz de:

- [ ] Explicar o modelo OSI e TCP/IP.
- [ ] Diferenciar L2, L3, L4 e L7.
- [ ] Explicar como um pacote trafega pela rede.
- [ ] Trabalhar com IPv4 e CIDR.
- [ ] Calcular sub-redes.
- [ ] Diferenciar IP público e privado.
- [ ] Entender gateways e tabelas de roteamento.
- [ ] Explicar TCP e UDP.
- [ ] Explicar o TCP 3-Way Handshake.
- [ ] Interpretar SYN, ACK, FIN e RST.
- [ ] Entender DNS, DHCP e ICMP.
- [ ] Entender HTTP e HTTPS.
- [ ] Entender NAT/PAT.
- [ ] Entender regras de firewall e ACL.
- [ ] Diferenciar Stateful e Stateless.
- [ ] Entender os fundamentos de VPN.
- [ ] Entender TLS e certificados digitais.
- [ ] Entender Reverse Proxy e Load Balancer.
- [ ] Utilizar Wireshark para analisar tráfego.
- [ ] Utilizar tcpdump para capturar tráfego.
- [ ] Utilizar `ip`, `ss`, `dig`, `curl`, `nc` e `openssl`.
- [ ] Identificar problemas de DNS.
- [ ] Identificar problemas de routing.
- [ ] Identificar problemas de firewall.
- [ ] Identificar problemas de TCP.
- [ ] Identificar problemas de HTTP/TLS.
- [ ] Investigar uma comunicação de rede de ponta a ponta.

---

### 📌 Legenda de Status

- ❌ **Não Iniciado**
- ⏳ **Em Andamento**
- ✅ **Concluído**

## 📅 Progresso do Curso

# 🌐 Módulo — Redes para Cloud Security Junior

> **Objetivo:** Construir uma base sólida de redes necessária para atuar como Junior em Cloud Security, com foco em IP, TCP/IP, DNS, routing, firewalls, NAT, TLS, análise de tráfego e troubleshooting.
>
> **Importante:** Este módulo não tem como objetivo formar um Network Engineer. O foco é adquirir o conhecimento necessário para compreender, proteger, investigar e realizar troubleshooting de ambientes Cloud.

---

## 📚 Módulo 1 — Fundamentos de Redes

| Aula no Plano | Tema do Módulo                     | Vídeo Exato / Canal                                                                         | Status |           Anotações           |
| :-----------: | :--------------------------------- | :------------------------------------------------------------------------------------------ | :----: | :---------------------------: |
|    **01**     | Modelo OSI vs. TCP/IP na Prática   | [Modelo OSI - Aula 26](https://www.youtube.com/watch?v=mMtZC5snPLQ) — Hardware Redes Brasil |   ⏳   | [Ver Resumo](./Resumos/01.md) |
|    **02**     | Camadas L2, L3, L4 e L7 na Prática | A definir                                                                                   |   ❌   | [Ver Resumo](./Resumos/02.md) |
|    **03**     | Encapsulamento e Desencapsulamento | A definir                                                                                   |   ❌   | [Ver Resumo](./Resumos/03.md) |
|    **04**     | Ethernet, MAC Address e ARP        | A definir                                                                                   |   ❌   | [Ver Resumo](./Resumos/04.md) |

---

## 📚 Módulo 2 — Endereçamento IP

| Aula no Plano | Tema do Módulo                    | Vídeo Exato / Canal                                                                                           | Status |           Anotações           |
| :-----------: | :-------------------------------- | :------------------------------------------------------------------------------------------------------------ | :----: | :---------------------------: |
|    **05**     | IPv4 e Endereçamento IP           | [Classes de Endereçamento IP - Aula 02](https://www.youtube.com/watch?v=kddmXxCgca8) — Hardware Redes Brasil  |   ❌   | [Ver Resumo](./Resumos/05.md) |
|    **06**     | IP Público vs. IP Privado         | A definir                                                                                                     |   ❌   | [Ver Resumo](./Resumos/06.md) |
|    **07**     | CIDR e Notação de Redes           | [Cálculo de Sub-redes - Aula #12](https://www.youtube.com/watch?v=FXGBQOf2lSU&t=188s) — Hardware Redes Brasil |   ❌   | [Ver Resumo](./Resumos/07.md) |
|    **08**     | Subnetting e Cálculo de Sub-redes | [Cálculo de Sub-redes - Aula #12](https://www.youtube.com/watch?v=FXGBQOf2lSU&t=188s) — Hardware Redes Brasil |   ❌   | [Ver Resumo](./Resumos/08.md) |
|    **09**     | Default Gateway                   | A definir                                                                                                     |   ❌   | [Ver Resumo](./Resumos/09.md) |
|    **10**     | IPv6 — Fundamentos                | A definir                                                                                                     |   ❌   | [Ver Resumo](./Resumos/10.md) |

---

## 📚 Módulo 3 — Protocolos de Rede

| Aula no Plano | Tema do Módulo                             | Vídeo Exato / Canal                                                                                             | Status |           Anotações           |
| :-----------: | :----------------------------------------- | :-------------------------------------------------------------------------------------------------------------- | :----: | :---------------------------: |
|    **11**     | TCP vs. UDP                                | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/11.md) |
|    **12**     | TCP 3-Way Handshake                        | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/12.md) |
|    **13**     | TCP Flags — SYN, ACK, FIN, RST             | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/13.md) |
|    **14**     | Portas TCP/UDP e Portas Efêmeras           | [Principais Protocolos e Portas - Aula 25](https://www.youtube.com/watch?v=DJ6e6HoJ5kI) — Hardware Redes Brasil |   ❌   | [Ver Resumo](./Resumos/14.md) |
|    **15**     | DNS — Domain Name System                   | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/15.md) |
|    **16**     | DHCP — Dynamic Host Configuration Protocol | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/16.md) |
|    **17**     | ICMP, Ping e Traceroute                    | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/17.md) |
|    **18**     | HTTP e HTTPS                               | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/18.md) |

---

## 📚 Módulo 4 — Routing e Network Security

| Aula no Plano | Tema do Módulo                       | Vídeo Exato / Canal | Status |           Anotações           |
| :-----------: | :----------------------------------- | :------------------ | :----: | :---------------------------: |
|    **19**     | Routing — Fundamentos de Roteamento  | A definir           |   ❌   | [Ver Resumo](./Resumos/19.md) |
|    **20**     | Routing Table — Tabela de Roteamento | A definir           |   ❌   | [Ver Resumo](./Resumos/20.md) |
|    **21**     | Default Route e Next Hop             | A definir           |   ❌   | [Ver Resumo](./Resumos/21.md) |
|    **22**     | NAT, PAT, SNAT e DNAT                | A definir           |   ❌   | [Ver Resumo](./Resumos/22.md) |
|    **23**     | Firewall — Fundamentos               | A definir           |   ❌   | [Ver Resumo](./Resumos/23.md) |
|    **24**     | Stateful vs. Stateless Firewall      | A definir           |   ❌   | [Ver Resumo](./Resumos/24.md) |
|    **25**     | ACL — Access Control List            | A definir           |   ❌   | [Ver Resumo](./Resumos/25.md) |
|    **26**     | VPN — Fundamentos                    | A definir           |   ❌   | [Ver Resumo](./Resumos/26.md) |

---

## 📚 Módulo 5 — TLS e Web

| Aula no Plano | Tema do Módulo                                | Vídeo Exato / Canal                                                                                    | Status |           Anotações           |
| :-----------: | :-------------------------------------------- | :----------------------------------------------------------------------------------------------------- | :----: | :---------------------------: |
|    **27**     | TLS — Transport Layer Security                | A definir                                                                                              |   ❌   | [Ver Resumo](./Resumos/27.md) |
|    **28**     | Certificados Digitais, CA e Certificate Chain | A definir                                                                                              |   ❌   | [Ver Resumo](./Resumos/28.md) |
|    **29**     | Reverse Proxy                                 | [O que é Nginx? Proxy Reverso](https://www.youtube.com/watch?v=Kef9GF7tllo) — Wesley Milan             |   ❌   | [Ver Resumo](./Resumos/29.md) |
|    **30**     | Load Balancer — L4 vs. L7                     | A definir                                                                                              |   ❌   | [Ver Resumo](./Resumos/30.md) |
|    **31**     | Nginx — Reverse Proxy e HTTPS                 | [Proxy reverso NGINX e Hardening Web](https://www.youtube.com/watch?v=Kef9GF7tllo&t=1s) — Wesley Milan |   ❌   | [Ver Resumo](./Resumos/31.md) |

---

## 📚 Módulo 6 — Network Analysis

| Aula no Plano | Tema do Módulo                                   | Vídeo Exato / Canal                                                                              | Status |           Anotações           |
| :-----------: | :----------------------------------------------- | :----------------------------------------------------------------------------------------------- | :----: | :---------------------------: |
|    **32**     | Wireshark — Captura e Inspeção de Pacotes        | [Como Utilizar o Wireshark](https://www.youtube.com/watch?v=TYk6ejP7dmI) — Lucas Teixeira        |   ❌   | [Ver Resumo](./Resumos/32.md) |
|    **33**     | tcpdump — Análise de Tráfego em Linha de Comando | [Análise de Tráfego com tcpdump](https://www.youtube.com/watch?v=4ccAK-t7Nes&t=9s) — Turma de TI |   ❌   | [Ver Resumo](./Resumos/33.md) |
|    **34**     | `ip` e `ss` — Diagnóstico de Rede no Linux       | A definir                                                                                        |   ❌   | [Ver Resumo](./Resumos/34.md) |
|    **35**     | `dig` — Diagnóstico e Investigação de DNS        | A definir                                                                                        |   ❌   | [Ver Resumo](./Resumos/35.md) |
|    **36**     | `curl` — Análise de HTTP/HTTPS                   | A definir                                                                                        |   ❌   | [Ver Resumo](./Resumos/36.md) |
|    **37**     | `nc` / Netcat — Teste de Conectividade e Portas  | A definir                                                                                        |   ❌   | [Ver Resumo](./Resumos/37.md) |
|    **38**     | `openssl s_client` — Análise de TLS              | A definir                                                                                        |   ❌   | [Ver Resumo](./Resumos/38.md) |

---

## 📚 Módulo 7 — Troubleshooting de Redes

| Aula no Plano | Tema do Módulo           | Vídeo Exato / Canal | Status |           Anotações           |
| :-----------: | :----------------------- | :------------------ | :----: | :---------------------------: |
|    **39**     | DNS Troubleshooting      | A definir           |   ❌   | [Ver Resumo](./Resumos/39.md) |
|    **40**     | Routing Troubleshooting  | A definir           |   ❌   | [Ver Resumo](./Resumos/40.md) |
|    **41**     | Firewall Troubleshooting | A definir           |   ❌   | [Ver Resumo](./Resumos/41.md) |
|    **42**     | TCP Troubleshooting      | A definir           |   ❌   | [Ver Resumo](./Resumos/42.md) |
|    **43**     | HTTP/TLS Troubleshooting | A definir           |   ❌   | [Ver Resumo](./Resumos/43.md) |

---

## 📚 Módulo 8 — Projeto Final

| Aula no Plano | Tema do Módulo                              | Vídeo Exato / Canal | Status |           Anotações           |
| :-----------: | :------------------------------------------ | :------------------ | :----: | :---------------------------: |
|    **44**     | Arquitetura de uma Rede Segura              | A definir           |   ❌   | [Ver Resumo](./Resumos/44.md) |
|    **45**     | Investigação de Tráfego e Incidente de Rede | A definir           |   ❌   | [Ver Resumo](./Resumos/45.md) |

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-167EC1?style=for-the-badge&logo=wireshark&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D24?style=for-the-badge&logo=debian&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

- **Sistema Operacional:** Linux (Distribuições Debian/Ubuntu)
- **Ferramentas de Análise:** Wireshark, `tcpdump`, `ping`, `traceroute`, `ss`/`netstat`, `dig`, `nc` (Netcat)
- **Servidor Web & Proxy:** Nginx (Virtual Hosts, Reverse Proxy, Log Auditing)
- **Conceitos Chave:** Modelo OSI/TCP-IP, Endereçamento IPv4 e CIDR, Captura de Pacotes, Hardening Web, Ocultação de Server Banners e Firewalls (`ufw`/`iptables`).

---

## 🔗 Fonte do Conteúdo

- **Hardware Redes Brasil** [Curso de Redes de Computadores](https://www.youtube.com/@HardwareRedesBrasil)
- **Curso em Vídeo** [Curso de Redes de Computadores](https://www.youtube.com/@CursoemVideo)
- **Conteúdos Práticos de Apoio:** Diolinux, Aécio Pires, Full Cycle e Guia Anônima.

---

## 🤝 Agradecimentos

Agradecimento especial ao **Edson Bezerra** (_Manager, LATAM Cyber Security Infrastructure Services - DXC Technology_) pela mentoria, orientações estratégicas e incentivo na estruturação deste plano de estudos.
