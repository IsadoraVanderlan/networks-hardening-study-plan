# 🌐 Redes de Computadores & Hardening - Plano de Estudos

> **Plano de estudos de redes, segurança de infraestrutura, análise de tráfego e troubleshooting.**

---

## 🎯 Objetivo do Curso

Este curso tem como objetivo construir uma base sólida de **Redes de Computadores aplicada à Cyber Security e Cloud Security**.

Ao concluir o curso, devo ser capaz de compreender como uma comunicação de rede funciona de ponta a ponta, identificar problemas de conectividade e interpretar os principais mecanismos utilizados para proteger aplicações, servidores e ambientes de Cloud.

---

## 🧠 Conhecimentos ao concluir o curso

### Fundamentos de Redes

- [ ] Explicar o modelo OSI.
- [ ] Explicar o modelo TCP/IP.
- [ ] Relacionar OSI e TCP/IP.
- [ ] Diferenciar L2, L3, L4 e L7.
- [ ] Explicar encapsulamento e desencapsulamento.
- [ ] Explicar como uma comunicação trafega pela rede.
- [ ] Entender Ethernet, MAC Address e ARP.

### Endereçamento e Routing

- [ ] Entender IPv4.
- [ ] Diferenciar IP público e privado.
- [ ] Entender CIDR.
- [ ] Calcular sub-redes.
- [ ] Identificar Network, Host e Broadcast.
- [ ] Entender Default Gateway.
- [ ] Entender tabelas de roteamento.
- [ ] Entender Default Route.
- [ ] Entender Next Hop.
- [ ] Ter uma visão geral de IPv6.

### Protocolos

- [ ] Diferenciar TCP e UDP.
- [ ] Explicar o TCP 3-Way Handshake.
- [ ] Interpretar SYN, SYN-ACK, ACK, FIN e RST.
- [ ] Entender portas TCP/UDP.
- [ ] Entender portas efêmeras.
- [ ] Entender DNS.
- [ ] Entender DHCP.
- [ ] Entender ICMP.
- [ ] Entender Ping e Traceroute.
- [ ] Entender HTTP e HTTPS.

### Network Security

- [ ] Entender NAT e PAT.
- [ ] Entender SNAT e DNAT.
- [ ] Entender os fundamentos de Firewall.
- [ ] Diferenciar Stateful e Stateless Firewall.
- [ ] Entender ACL.
- [ ] Entender os fundamentos de VPN.
- [ ] Entender segmentação de rede.
- [ ] Entender controle de tráfego entre diferentes redes.

### TLS e Segurança Web

- [ ] Explicar o funcionamento básico do TLS.
- [ ] Entender certificados digitais.
- [ ] Entender Certificate Authority (CA).
- [ ] Entender Certificate Chain.
- [ ] Identificar problemas básicos de TLS.
- [ ] Entender Reverse Proxy.
- [ ] Diferenciar Load Balancer L4 e L7.
- [ ] Entender o papel do Nginx em uma arquitetura web.
- [ ] Aplicar conceitos básicos de hardening web.

### Análise e Troubleshooting

- [ ] Utilizar Wireshark para analisar tráfego.
- [ ] Utilizar `tcpdump` para capturar pacotes.
- [ ] Utilizar `ip` para diagnóstico de rede.
- [ ] Utilizar `ss` para analisar conexões.
- [ ] Utilizar `dig` para investigar DNS.
- [ ] Utilizar `curl` para testar HTTP/HTTPS.
- [ ] Utilizar `nc` para testes de conectividade.
- [ ] Utilizar `openssl s_client` para investigar TLS.
- [ ] Identificar problemas de DNS.
- [ ] Identificar problemas de routing.
- [ ] Identificar problemas de firewall.
- [ ] Identificar problemas de TCP.
- [ ] Identificar problemas de HTTP/TLS.
- [ ] Investigar uma comunicação de rede de ponta a ponta.

### Aplicação em Cloud Security

- [ ] Relacionar conceitos de redes tradicionais com ambientes Cloud.
- [ ] Entender a importância de segmentação de rede em Cloud.
- [ ] Entender o papel de Security Groups e Network ACLs em ambientes Cloud.
- [ ] Entender o conceito de subnets públicas e privadas.
- [ ] Entender o papel de NAT Gateway em arquiteturas Cloud.
- [ ] Entender o fluxo de tráfego entre componentes de uma arquitetura.
- [ ] Utilizar fundamentos de redes durante investigações de segurança.
- [ ] Analisar uma arquitetura de rede pensando em segurança.

---

## 📌 Legenda de Status

- ❌ **Não Iniciado**
- ⏳ **Em Andamento**
- ✅ **Concluído**

---

# 📅 Progresso do Curso

| Módulo | Tema                       | Aulas | Status |
| :----: | :------------------------- | :---: | :----: |
| **1**  | Fundamentos de Redes       | 01–04 |   ⏳   |
| **2**  | Endereçamento IP           | 05–10 |   ❌   |
| **3**  | Protocolos de Rede         | 11–18 |   ❌   |
| **4**  | Routing e Network Security | 19–26 |   ❌   |
| **5**  | TLS e Web Security         | 27–31 |   ❌   |
| **6**  | Network Analysis           | 32–38 |   ❌   |
| **7**  | Troubleshooting            | 39–43 |   ❌   |
| **8**  | Projeto Final              | 44–45 |   ❌   |

---

### 📌 Legenda de Status

- ❌ **Não Iniciado**
- ⏳ **Em Andamento**
- ✅ **Concluído**

---

# 📚 Módulo 1 — Fundamentos de Redes

> **Objetivo:** compreender os fundamentos necessários para interpretar uma comunicação de rede e identificar o papel de cada camada.

|  Aula  | Tema                               | Vídeo Exato / Canal                                                                                                                | Status |           Anotações           |
| :----: | :--------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------- | :----: | :---------------------------: |
| **01** | Modelo OSI vs. TCP/IP na Prática   | [Curso de Modelo OSI](https://www.youtube.com/watch?v=3gpo0N04OY0&list=PLAp37wMSBouCyqVtvzLm5JS4dorY-q4uZ) — Hardware Redes Brasil |   ✅   | [Ver Resumo](./Resumos/01.md) |
| **02** | Camadas L2, L3, L4 e L7 na Prática | A definir                                                                                                                          |   ⏳   | [Ver Resumo](./Resumos/02.md) |
| **03** | Encapsulamento e Desencapsulamento | A definir                                                                                                                          |   ❌   | [Ver Resumo](./Resumos/03.md) |
| **04** | Ethernet, MAC Address e ARP        | A definir                                                                                                                          |   ❌   | [Ver Resumo](./Resumos/04.md) |

---

# 📚 Módulo 2 — Endereçamento IP

> **Objetivo:** compreender endereçamento IPv4, CIDR, sub-redes e conceitos fundamentais utilizados na construção de redes Cloud.

|  Aula  | Tema                              | Vídeo Exato / Canal                                                                                           | Status |           Anotações           |
| :----: | :-------------------------------- | :------------------------------------------------------------------------------------------------------------ | :----: | :---------------------------: |
| **05** | IPv4 e Endereçamento IP           | [Classes de Endereçamento IP - Aula 02](https://www.youtube.com/watch?v=kddmXxCgca8) — Hardware Redes Brasil  |   ❌   | [Ver Resumo](./Resumos/05.md) |
| **06** | IP Público vs. IP Privado         | A definir                                                                                                     |   ❌   | [Ver Resumo](./Resumos/06.md) |
| **07** | CIDR e Notação de Redes           | [Cálculo de Sub-redes - Aula #12](https://www.youtube.com/watch?v=FXGBQOf2lSU&t=188s) — Hardware Redes Brasil |   ❌   | [Ver Resumo](./Resumos/07.md) |
| **08** | Subnetting e Cálculo de Sub-redes | [Cálculo de Sub-redes - Aula #12](https://www.youtube.com/watch?v=FXGBQOf2lSU&t=188s) — Hardware Redes Brasil |   ❌   | [Ver Resumo](./Resumos/08.md) |
| **09** | Default Gateway                   | A definir                                                                                                     |   ❌   | [Ver Resumo](./Resumos/09.md) |
| **10** | IPv6 — Fundamentos                | A definir                                                                                                     |   ❌   | [Ver Resumo](./Resumos/10.md) |

---

# 📚 Módulo 3 — Protocolos de Rede

> **Objetivo:** compreender os principais protocolos utilizados na comunicação entre sistemas e aplicações.

|  Aula  | Tema                                       | Vídeo Exato / Canal                                                                                             | Status |           Anotações           |
| :----: | :----------------------------------------- | :-------------------------------------------------------------------------------------------------------------- | :----: | :---------------------------: |
| **11** | TCP vs. UDP                                | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/11.md) |
| **12** | TCP 3-Way Handshake                        | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/12.md) |
| **13** | TCP Flags — SYN, ACK, FIN, RST             | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/13.md) |
| **14** | Portas TCP/UDP e Portas Efêmeras           | [Principais Protocolos e Portas - Aula 25](https://www.youtube.com/watch?v=DJ6e6HoJ5kI) — Hardware Redes Brasil |   ❌   | [Ver Resumo](./Resumos/14.md) |
| **15** | DNS — Domain Name System                   | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/15.md) |
| **16** | DHCP — Dynamic Host Configuration Protocol | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/16.md) |
| **17** | ICMP, Ping e Traceroute                    | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/17.md) |
| **18** | HTTP e HTTPS                               | A definir                                                                                                       |   ❌   | [Ver Resumo](./Resumos/18.md) |

---

# 📚 Módulo 4 — Routing e Network Security

> **Objetivo:** compreender como o tráfego é encaminhado e como mecanismos de segurança controlam esse tráfego.

|  Aula  | Tema                                 | Vídeo Exato / Canal | Status |           Anotações           |
| :----: | :----------------------------------- | :------------------ | :----: | :---------------------------: |
| **19** | Routing — Fundamentos de Roteamento  | A definir           |   ❌   | [Ver Resumo](./Resumos/19.md) |
| **20** | Routing Table — Tabela de Roteamento | A definir           |   ❌   | [Ver Resumo](./Resumos/20.md) |
| **21** | Default Route e Next Hop             | A definir           |   ❌   | [Ver Resumo](./Resumos/21.md) |
| **22** | NAT, PAT, SNAT e DNAT                | A definir           |   ❌   | [Ver Resumo](./Resumos/22.md) |
| **23** | Firewall — Fundamentos               | A definir           |   ❌   | [Ver Resumo](./Resumos/23.md) |
| **24** | Stateful vs. Stateless Firewall      | A definir           |   ❌   | [Ver Resumo](./Resumos/24.md) |
| **25** | ACL — Access Control List            | A definir           |   ❌   | [Ver Resumo](./Resumos/25.md) |
| **26** | VPN — Fundamentos                    | A definir           |   ❌   | [Ver Resumo](./Resumos/26.md) |

---

# 📚 Módulo 5 — TLS e Web Security

> **Objetivo:** compreender como aplicações web são publicadas, protegidas e acessadas através de HTTPS, Reverse Proxy e Load Balancers.

|  Aula  | Tema                                          | Vídeo Exato / Canal                                                                                    | Status |           Anotações           |
| :----: | :-------------------------------------------- | :----------------------------------------------------------------------------------------------------- | :----: | :---------------------------: |
| **27** | TLS — Transport Layer Security                | A definir                                                                                              |   ❌   | [Ver Resumo](./Resumos/27.md) |
| **28** | Certificados Digitais, CA e Certificate Chain | A definir                                                                                              |   ❌   | [Ver Resumo](./Resumos/28.md) |
| **29** | Reverse Proxy                                 | [O que é Nginx? Proxy Reverso](https://www.youtube.com/watch?v=Kef9GF7tllo) — Wesley Milan             |   ❌   | [Ver Resumo](./Resumos/29.md) |
| **30** | Load Balancer — L4 vs. L7                     | A definir                                                                                              |   ❌   | [Ver Resumo](./Resumos/30.md) |
| **31** | Nginx — Reverse Proxy, HTTPS e Hardening      | [Proxy reverso NGINX e Hardening Web](https://www.youtube.com/watch?v=Kef9GF7tllo&t=1s) — Wesley Milan |   ❌   | [Ver Resumo](./Resumos/31.md) |

---

# 📚 Módulo 6 — Network Analysis

> **Objetivo:** aprender a observar o tráfego real e utilizar ferramentas de linha de comando para investigar problemas de rede.

|  Aula  | Tema                                             | Vídeo Exato / Canal                                                                              | Status |           Anotações           |
| :----: | :----------------------------------------------- | :----------------------------------------------------------------------------------------------- | :----: | :---------------------------: |
| **32** | Wireshark — Captura e Inspeção de Pacotes        | [Como Utilizar o Wireshark](https://www.youtube.com/watch?v=TYk6ejP7dmI) — Lucas Teixeira        |   ❌   | [Ver Resumo](./Resumos/32.md) |
| **33** | tcpdump — Análise de Tráfego em Linha de Comando | [Análise de Tráfego com tcpdump](https://www.youtube.com/watch?v=4ccAK-t7Nes&t=9s) — Turma de TI |   ❌   | [Ver Resumo](./Resumos/33.md) |
| **34** | `ip` e `ss` — Diagnóstico de Rede no Linux       | A definir                                                                                        |   ❌   | [Ver Resumo](./Resumos/34.md) |
| **35** | `dig` — Diagnóstico e Investigação de DNS        | A definir                                                                                        |   ❌   | [Ver Resumo](./Resumos/35.md) |
| **36** | `curl` — Análise de HTTP/HTTPS                   | A definir                                                                                        |   ❌   | [Ver Resumo](./Resumos/36.md) |
| **37** | `nc` / Netcat — Teste de Conectividade e Portas  | A definir                                                                                        |   ❌   | [Ver Resumo](./Resumos/37.md) |
| **38** | `openssl s_client` — Análise de TLS              | A definir                                                                                        |   ❌   | [Ver Resumo](./Resumos/38.md) |

---

# 📚 Módulo 7 — Troubleshooting de Redes

> **Objetivo:** desenvolver uma metodologia estruturada para investigar problemas de conectividade e comunicação.

|  Aula  | Tema                     | Vídeo Exato / Canal | Status |           Anotações           |
| :----: | :----------------------- | :------------------ | :----: | :---------------------------: |
| **39** | DNS Troubleshooting      | A definir           |   ❌   | [Ver Resumo](./Resumos/39.md) |
| **40** | Routing Troubleshooting  | A definir           |   ❌   | [Ver Resumo](./Resumos/40.md) |
| **41** | Firewall Troubleshooting | A definir           |   ❌   | [Ver Resumo](./Resumos/41.md) |
| **42** | TCP Troubleshooting      | A definir           |   ❌   | [Ver Resumo](./Resumos/42.md) |
| **43** | HTTP/TLS Troubleshooting | A definir           |   ❌   | [Ver Resumo](./Resumos/43.md) |

---

# 📚 Módulo 8 — Projeto Final

> **Objetivo:** aplicar os conhecimentos adquiridos durante o curso em um cenário próximo do que pode ser encontrado em um ambiente real.

|  Aula  | Tema                                        | Vídeo Exato / Canal | Status |           Anotações           |
| :----: | :------------------------------------------ | :------------------ | :----: | :---------------------------: |
| **44** | Arquitetura de uma Rede Segura              | A definir           |   ❌   | [Ver Resumo](./Resumos/44.md) |
| **45** | Investigação de Tráfego e Incidente de Rede | A definir           |   ❌   | [Ver Resumo](./Resumos/45.md) |

---

# 🛠️ Tecnologias e Ferramentas

![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-167EC1?style=for-the-badge&logo=wireshark&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D24?style=for-the-badge&logo=debian&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### 🐧 Sistema Operacional

- Linux
- Debian
- Ubuntu

### 🔎 Análise de Rede

- Wireshark
- `tcpdump`
- `ping`
- `traceroute`
- `ip`
- `ss`
- `dig`
- `curl`
- `nc`
- `openssl`

### 🌐 Web e Proxy

- Nginx
- Reverse Proxy
- HTTPS
- TLS
- Virtual Hosts
- Web Logs

### 🔥 Network Security

- Firewall
- ACL
- `ufw`
- `iptables`
- NAT
- PAT
- SNAT
- DNAT

---

# 🎯 Resultado Final Esperado

Ao concluir este plano de estudos, meu objetivo é conseguir olhar para uma comunicação de rede e raciocinar sobre ela de forma estruturada:

```text
Quem está falando?
        ↓
Qual é o IP?
        ↓
Qual é a subnet?
        ↓
Qual é o gateway?
        ↓
Qual rota será utilizada?
        ↓
Existe NAT?
        ↓
Existe Firewall / ACL?
        ↓
Qual porta está sendo utilizada?
        ↓
O TCP estabeleceu conexão?
        ↓
O TLS funcionou?
        ↓
O HTTP respondeu?
        ↓
A aplicação recebeu a requisição?
```

---

# 🔗 Fontes do Conteúdo

- **Hardware Redes Brasil** — [Curso de Redes de Computadores](https://www.youtube.com/@HardwareRedesBrasil)
- **Curso em Vídeo** — [Curso de Redes de Computadores](https://www.youtube.com/@CursoemVideo)
- **Conteúdos Práticos de Apoio:** Diolinux, Aécio Pires, Full Cycle e Guia Anônima.

---

# 🤝 Agradecimentos

Agradecimento especial ao **Edson Bezerra** (_Manager, LATAM Cyber Security Infrastructure Services - DXC Technology_) pela mentoria, orientações estratégicas e incentivo na estruturação deste plano de estudos.
