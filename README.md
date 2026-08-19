# 🌐 Redes de Computadores & Hardening - Plano de Estudos

## 🎯 Objetivos

- **Compreenda o funcionamento dos modelos OSI e TCP/IP**, mapeando o fluxo de dados das camadas L3, L4 e L7 até a aplicação.
- **Domine o endereçamento IPv4 e notação CIDR**, compreendendo sub-redes e o roteamento de redes privadas (RFC 1918).
- **Realize análise e inspeção de tráfego** em tempo real utilizando ferramentas CLI (`tcpdump`) e GUI (**Wireshark**).
- **Implemente servidores web seguros com Nginx**, configurando Proxy Reverso, análise de logs (`access`/`error`) e técnicas de **Hardening** para redução da superfície de ataque.

---

### 📌 Legenda de Status

- ❌ **Não Iniciado**
- ⏳ **Em Andamento**
- ✅ **Concluído**

## 📅 Progresso do Curso

| Aula no Plano | Tema do Módulo                                         | Vídeo Exato / Canal                                                                                             | Status |           Anotações           |
| :-----------: | :----------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------- | :----: | :---------------------------: |
|    **01**     | Modelo OSI vs. TCP/IP na Prática (Camadas L3, L4 e L7) | [Modelo OSI - Aula 26](https://www.youtube.com/watch?v=mMtZC5snPLQ) (Hardware Redes Brasil)                     |   ⏳   | [Ver Resumo](./Resumos/01.md) |
|    **02**     | Principais Protocolos e Portas Padrão                  | [Principais Protocolos e Portas - Aula 25](https://www.youtube.com/watch?v=DJ6e6HoJ5kI) (Hardware Redes Brasil) |   ❌   | [Ver Resumo](./Resumos/02.md) |
|    **03**     | Endereçamento IP e Classes de Rede                     | [Classes de Endereçamento IP - Aula 02](https://www.youtube.com/watch?v=kddmXxCgca8) (Hardware Redes Brasil)    |   ❌   | [Ver Resumo](./Resumos/03.md) |
|    **04**     | Cálculo de Sub-redes e Notação CIDR                    | [Cálculo de Sub-redes - Aula #12](https://www.youtube.com/watch?v=FXGBQOf2lSU&t=188s) (Hardware Redes Brasil)   |   ❌   | [Ver Resumo](./Resumos/04.md) |
|    **05**     | Captura e Inspeção de Pacotes na Prática               | [Como Utilizar o Wireshark](https://www.youtube.com/watch?v=TYk6ejP7dmI) (Lucas Teixeira)                       |   ❌   | [Ver Resumo](./Resumos/05.md) |
|    **06**     | Análise de Tráfego em Linha de Comando (`tcpdump`)     | [Análise de Tráfego com tcpdump](https://www.youtube.com/watch?v=4ccAK-t7Nes&t=9s) (Turma de TI)                |   ❌   | [Ver Resumo](./Resumos/06.md) |
|    **07**     | Servidor Web e Proxy Reverso com Nginx                 | [O que é Nginx? Proxy Reverso](https://www.youtube.com/watch?v=Kef9GF7tllo) (Wesley Milan)                      |   ❌   | [Ver Resumo](./Resumos/07.md) |
|    **08**     | Hardening Web, Proteção e Análise de Logs              | [Proxy reverso NGINX e Hardening Web](https://www.youtube.com/watch?v=Kef9GF7tllo&t=1s) (Wesley Milan)          |   ❌   | [Ver Resumo](./Resumos/08.md) |

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
