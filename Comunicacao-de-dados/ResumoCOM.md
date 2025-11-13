# Comunicação de Dados

Este documento apresenta um resumo completo e didático dos principais conceitos da disciplina "Comunicação de Dados", com explicações claras sobre redes, topologias, meios de transmissão, equipamentos e muito mais.  
Baseado no material da Universidade Franciscana (UFN).

---

## 📌 Sumário
- [1. Introdução à Comunicação de Dados](#1-introdução-à-comunicação-de-dados)  
- [2. Contexto Atual – Mundo Globalizado](#2-contexto-atual--mundo-globalizado)  
- [3. O que é uma Rede de Computadores?](#3-o-que-é-uma-rede-de-computadores)  
- [4. Tipos de Redes por Abrangência](#4-tipos-de-redes-por-abrangência)  
- [5. Topologias de Rede](#5-topologias-de-rede)  
- [6. Meios de Transmissão](#6-meios-de-transmissão)  
- [7. Equipamentos de Redes](#7-equipamentos-de-redes)  
- [8. Arquiteturas de Rede](#8-arquiteturas-de-rede)  
- [9. Protocolos de Rede](#9-protocolos-de-rede)  
- [10. Sistemas Operacionais de Rede](#10-sistemas-operacionais-de-rede)  
- [11. Segurança em Redes](#11-segurança-em-redes)  
- [12. Camada de Enlace (Enlace de Dados)](#12-camada-de-enlace-enlace-de-dados)

---

## 1. Introdução à Comunicação de Dados
Comunicação de dados é a área responsável pelo estudo da troca de informações entre dispositivos, utilizando diferentes meios, protocolos e arquiteturas.  
O objetivo principal é permitir que computadores, redes e sistemas se comuniquem com eficiência, segurança e confiabilidade.

---

## 2. Contexto Atual – Mundo Globalizado
A comunicação de dados se tornou fundamental devido a diversos fatores:
- Crescimento acelerado da tecnologia  
- Expansão das redes de comunicação  
- Internacionalização dos mercados  
- Competitividade e integração entre empresas  
- Troca eletrônica de informações em tempo real

Hoje, muitos serviços e sistemas (empresas, bancos, telecomunicações, aplicativos, automações domésticas) dependem de redes de dados.

---

## 3. O que é uma Rede de Computadores?
Uma rede de computadores é a interconexão entre dois ou mais dispositivos que se comunicam por um meio físico ou sem fio para compartilhar dados e recursos.

Principais objetivos:
- Compartilhar arquivos e impressoras  
- Comunicar sistemas e usuários  
- Acessar serviços e servidores  
- Otimizar hardware, software e conexões

---

## 4. Tipos de Redes por Abrangência

- PAN – Personal Area Network  
  - Rede pessoal com curta distância.  
  - Exemplos: Bluetooth, conexões Wi‑Fi domésticas, smartwatch + celular.

- LAN – Local Area Network  
  - Rede local, normalmente dentro de empresas, universidades, prédios ou campi.  
  - Caracteriza‑se por alta velocidade e baixo custo.

- MAN – Metropolitan Area Network  
  - Abrange uma cidade ou região metropolitana.  
  - Exemplo: rede municipal interligando vários bairros.

- WAN – Wide Area Network  
  - Abrange grandes distâncias, até países.  
  - Exemplo: a Internet e redes corporativas multinacionais.  
  - São redes mais caras e complexas, compostas por várias sub‑redes.

---

## 5. Topologias de Rede
Topologia é o formato físico ou lógico da rede.

- Topologia Barramento (Bus)  
  - Um único cabo conectando todos os dispositivos.  
  - Barata, porém frágil: um curto pode derrubar toda a rede.  
  - Usa terminadores nas extremidades; fluxo bidirecional.

- Topologia Anel (Ring)  
  - Cada computador conecta ao próximo, formando um círculo.  
  - Se uma estação falha, toda a rede pode cair.  
  - Cada estação funciona como repetidor; fluxo em uma única direção.

- Topologia Estrela (Star)  
  - Todas as máquinas conectam a um nó central (hub/switch).  
  - Se o nó central falhar, a rede cai.  
  - Mais utilizada atualmente em LANs.

- Redes Híbridas  
  - Combinação de duas ou mais topologias (ex.: Estrela + Anel).

---

## 6. Meios de Transmissão

- Analógico x Digital  
  - Analógico: sinal contínuo (rádio, TV).  
  - Digital: níveis discretos (0 e 1) usados por computadores e Internet.

- Cabo Coaxial  
  - Antigo, resistente a interferências.  
  - Usado em TV a cabo e redes antigas.

- Par Trançado (UTP/STP)  
  - Mais usado em LANs, barato e fácil de instalar.  
  - Exemplos: Cat5e, Cat6, Cat6a.

- Fibra Óptica  
  - Alta velocidade, longas distâncias sem perda, imune a interferência.  
  - Usada em backbones e provedores.

- Radiodifusão / Wireless  
  - Wi‑Fi, rádio, 5G.

- Satélite  
  - Usado em áreas remotas; apresenta alta latência.

- Backbone  
  - Infraestrutura principal de alta capacidade que sustenta toda a rede (a "espinha dorsal").

---

## 7. Equipamentos de Redes

- Placa de Rede (NIC) — Interface que permite comunicação com a rede.  
- Hub — Repassa dados para todas as portas; não é inteligente; obsoleto.  
- Switch — Envia dados somente ao destino; inteligente e rápido; padrão em LANs.  
- Roteador — Interliga redes diferentes; encaminha pacotes (Nível 3 – IP).  
- Bridge — Segmenta redes para melhorar desempenho.  
- Repetidor — Regenera o sinal em cabos longos.  
- Modem — Converte sinal digital ↔ analógico; essencial para comunicação com provedores.

---

## 8. Arquiteturas de Rede

- Cliente/Servidor — Cliente solicita serviços; servidor fornece.  
  - Tipos de servidores: arquivos, banco de dados, impressão, comunicação, gerenciamento.

- Peer‑to‑Peer (P2P) — Todos os nós têm funções iguais; compartilhamento direto.  
  - Exemplos: Torrent, redes domésticas.

---

## 9. Protocolos de Rede
Protocolos são regras que garantem a troca correta de dados entre dispositivos.

Exemplos:
- TCP/IP → padrão da Internet  
- NetBEUI → Microsoft (antigo)  
- IPX/SPX → Novell (antigo)

---

## 10. Sistemas Operacionais de Rede
Exemplos históricos e atuais de sistemas que permitem gerenciar redes e serviços:
- Windows NT  
- Windows 2000  
- NetWare  
- Unix  
- Linux

---

## 11. Segurança em Redes
Pontos fundamentais para proteger redes:
- Definição clara de usuários e administradores  
- Políticas de senha fortes  
- Criptografia de dados  
- Firewalls para bloquear acessos indevidos  
- Backups regulares

---

## 12. Camada de Enlace (Enlace de Dados)

A Camada de Enlace (Data Link Layer) é a segunda camada do modelo OSI e tem como responsabilidade principal a transferência confiável de dados entre dois nós diretamente conectados pelo meio físico. Ela atua logo acima da Camada Física, organizando os bits em unidades maiores (quadros) e provendo controle de erro, controle de fluxo e acesso ao meio.

Principais funções
- Framing (enquadramento): transformar a sequência de bits recebida da camada física em quadros (frames) com início/fim definidos.  
- Endereçamento de enlace: identificar nós locais por endereços físicos (endereços MAC).  
- Detecção e controle de erros: usar mecanismos como CRC (FCS) para detectar erros de transmissão.  
- Controle de fluxo: evitar que um transmissor rápido sobrecarregue um receptor mais lento (ex.: técnicas baseadas em janelas).  
- Controle de acesso ao meio (MAC): arbitrar quem pode transmitir quando o meio é compartilhado (ex.: CSMA/CD, CSMA/CA, token passing).  
- Transparência de transmissão: garantir delimitação de quadros mesmo que o padrão de bits do payload coincida com padrões de controle.

Sublayers: LLC e MAC
- LLC (Logical Link Control) — Subcamada superior (padronizada pelo IEEE 802.2): controla o estabelecimento de conexões, multiplexação de protocolos de rede (tipo de serviço), e controle de fluxo/erros em nível lógico.  
- MAC (Media Access Control) — Subcamada inferior: responsável pelo endereçamento físico (MAC addresses) e pelo controle de acesso ao meio.

Endereçamento MAC
- Endereço MAC: identificador único (48 bits na maioria das tecnologias) atribuído à interface de rede. Geralmente expresso em hexadecimal (ex.: 00:1A:2B:3C:4D:5E).  
- Usado para entrega de frames dentro do mesmo domínio de broadcast (LAN).

Formato de quadro (exemplo genérico / Ethernet)
- Pré‑ambulo + Start Frame Delimiter (SFD)  
- Endereço destino (MAC)  
- Endereço origem (MAC)  
- Tipo/Comprimento (indica protocolo de camada de rede ou comprimento)  
- Dados / Payload  
- Frame Check Sequence (FCS) — CRC para detecção de erros

Controle de acesso ao meio (MAC protocols)
- CSMA/CD (Carrier Sense Multiple Access with Collision Detection) — usado historicamente em Ethernet half‑duplex: escuta o meio antes de transmitir; detecta colisões e retransmite após backoff.  
- CSMA/CA (Carrier Sense Multiple Access with Collision Avoidance) — usado em redes sem fio (802.11): evita colisões por meio de deferência e confirmações.  
- Token Passing — redes como Token Ring ou FDDI (mais antigas): um token circula e só o nó que possui o token pode transmitir.

Detecção e correção de erros
- Tipicamente a camada de enlace detecta erros (CRC/FCS). Correção pode ser feita por retransmissão (ARQ — Automatic Repeat reQuest).  
- Mecanismos de redundância e controle de fluxo garantem confiabilidade em links ruidosos.

Comutação e dispositivos de camada 2
- Bridges e switches operam na camada de enlace, encaminhando frames com base em endereços MAC e construindo tabelas de comutação (MAC tables).  
- Switches modernos suportam VLANs (IEEE 802.1Q) para segmentação lógica e controle de broadcast/domínio.

MTU e fragmentação
- MTU (Maximum Transmission Unit) define o tamanho máximo de payload de um quadro/segmento na camada de enlace.  
- Fragmentação por norma é tratada geralmente na camada de rede, mas limites de MTU influenciam o comportamento de camadas superiores.

Protocolos e exemplos comuns de camada de enlace
- Ethernet (IEEE 802.3) — padrão dominante para LANs.  
- Wi‑Fi (IEEE 802.11) — inclui especificações de MAC para acesso sem fio.  
- PPP (Point-to-Point Protocol) — usado em links ponto-a-ponto (dial‑up, PPPoE).  
- HDLC — protocolo síncrono de enlace.  
- Frame Relay, ATM — tecnologias de enlace usadas historicamente em WANs (com diferentes características: células no caso do ATM).  
- ARP (Address Resolution Protocol) — embora seja um protocolo auxiliar da camada de rede/ enlace, é essencial para mapear endereços IP para MAC em LANs.

Relação com outras camadas
- A camada de enlace fornece serviços à camada de rede (ex.: entrega de frames contendo datagramas IP).  
- A camada física cuida da representação dos bits; a de enlace organiza esses bits em quadros e trata erros de transmissão.

Segurança em camada de enlace
- Técnicas: filtragem por MAC, 802.1X para controle de acesso à rede, VLANs para segmentação, proteção contra spoofing e ataques de ARP (ARP spoofing).  
- Observação: segurança na camada de enlace é importante mas insuficiente sozinha — precisa de controles adicionais em camadas superiores.

Boas práticas
- Usar switches em vez de hubs para reduzir colisões e domínios de colisão.  
- Segmentar redes com VLANs para isolar tráfego sensível.  
- Configurar MTU compatível entre dispositivos para evitar fragmentação indesejada.  
- Ativar segurança de enlace (802.1X, port security) em ambientes corporativos.

---

## Referências
- Material de apoio: Universidade Franciscana (UFN)  
- IEEE 802.3 (Ethernet), IEEE 802.11 (Wi‑Fi), RFCs relacionados a PPP/ARP

