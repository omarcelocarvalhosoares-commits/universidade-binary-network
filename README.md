🎓 University Binary Network

Projeto de **Redes de Computadores e Infraestrutura de TI** desenvolvido utilizando **Cisco Packet Tracer**, criado como parte do meu portfólio para colocar em prática conhecimentos adquiridos na faculdade e em cursos voltados para redes e infraestrutura.

O projeto simula a infraestrutura de rede de uma instituição de ensino, incluindo laboratórios, área de coordenação, sala de servidores, conectividade Wi-Fi e acesso a uma rede externa através de um ISP.



📌 Sobre o projeto

O objetivo deste projeto foi desenvolver uma infraestrutura de rede funcional, segmentada e com controles básicos de segurança, aplicando conceitos fundamentais de **Networking, Infraestrutura de TI e Segurança de Redes**.

A topologia foi construída utilizando equipamentos Cisco e diferentes segmentos de rede, permitindo a aplicação prática de VLANs, roteamento, ACLs, serviços de rede e NAT/PAT.



🗺️ Topologia

A infraestrutura é composta por:

- Laboratório A
- Laboratório B
- Laboratório C
- Coordenação
- Sala de Servidores
- Core Switch
- Core Router
- Roteador ISP
- Access Point
- Servidor Web
- Servidor DNS
- PC utilizado para validação do NAT/PAT



🛠️ Tecnologias e conceitos utilizados

🌐 Networking

- IPv4
- TCP/IP
- VLANs
- Inter-VLAN Routing
- Router-on-a-Stick
- Switch Core
- Switching
- Roteamento estático
- ICMP

🔐 Segurança

- Extended ACL
- Segmentação de rede
- Controle de tráfego entre VLANs
- Restrição de ICMP
- Controle de acesso aos servidores

🌎 Serviços e conectividade

- HTTP / Web Server
- DNS
- Wi-Fi / Access Point
- NAT
- PAT (NAT Overload)
- ISP simulado

🏷️ Segmentação por VLAN

A rede foi dividida logicamente através de VLANs para melhorar a organização e a segmentação do ambiente.

| VLAN | Segmento | Rede |
|------|----------|------|
| VLAN 10 | Laboratório A | `10.1.10.0/24` |
| VLAN 20 | Coordenação | `10.1.20.0/24` |
| VLAN 30 | Servidores | `10.1.30.0/24` |

