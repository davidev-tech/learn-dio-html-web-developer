---
modulo: O que são servers
tags:
  - formacao-html
  - servidores
  - hardware
  - software
criacao: 2026-09-22
status: em-andamento
---

# Anotações de Aula — Hardware e Software em Servidores

## 1. Conceito principal

- Todo servidor precisa de **duas partes**: **hardware** e **software**.
- Uma depende da outra: o software roda sobre o hardware.

---

## 2. Hardware

- **Armazenamento** — discos rígidos (HDs) e SSDs.
- **Memória** — RAM, usada para manter processos ativos.
- **Processadores** — CPU, responsável pelo processamento.

> São os componentes físicos do servidor.

---

## 3. Software

- **Sistema operacional** — base que gerencia hardware e recursos.
- **Aplicações de monitoramento** — acompanham desempenho e saúde do servidor.
- **Servidor web** — responsável por atender requisições HTTP/HTTPS.

> São os programas que fazem o servidor funcionar.

---

## 4. Sistemas operacionais para servidores

- Windows Server
- Ubuntu
- Fedora
- Outras distribuições Linux

---

## 5. Servidores web

| Servidor Web | Descrição                                      |
| ------------ | ---------------------------------------------- |
| Apache       | Um dos mais tradicionais e usados              |
| Nginx        | Leve, rápido e muito usado em alta performance |

---

## 6. Relação entre as camadas

- O servidor tem um **sistema operacional**.
- O sistema operacional tem um **servidor web** rodando dentro dele.
- O servidor web atende às requisições vindas dos clientes.

> Fluxo: **Hardware → Sistema Operacional → Servidor Web → Aplicação → Cliente**

---

## 7. Custo de licenças

- Sistemas operacionais e softwares podem ser **gratuitos** ou **pagos**.
- Exemplos:
  - Linux (Ubuntu, Fedora) — geralmente gratuitos.
  - Windows Server — exige licença paga.
- O custo de licenças é um fator importante na escolha da stack do servidor.

---

## 8. Resumo visual

| Camada | Exemplos |
|---|---|
| Hardware | HD, SSD, RAM, CPU |
| Sistema Operacional | Windows Server, Ubuntu, Fedora, Linux |
| Servidor Web | Apache, Nginx |
| Monitoramento | Aplicações de acompanhamento |

---

## 9. Fluxo resumido

**Hardware → Sistema Operacional → Servidor Web → Aplicação → Cliente**