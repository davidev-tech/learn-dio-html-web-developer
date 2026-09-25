---
modulo: O que são servers
tags:
  - formacao-html
  - servidores
  - infraestrutura
  - redes
criacao: 2026-09-25
status: em-andamento
---

# Anotações de Aula — Tipos de Servidores

## 1. Conceito principal

- Servidores podem exercer funções específicas dentro de uma infraestrutura.
- Cada tipo tem um papel próprio: intermediar, proteger, processar, armazenar ou redirecionar.
- Muitas vezes vários tipos coexistem no mesmo ambiente.

---

## 2. Proxy

- Servidor **intermediário** entre a rede local e serviços/servidores externos.
- **Restringe acessos** de dentro para fora.
- Controla o que os usuários internos podem acessar na internet.

> Direção do controle: **interna → externa**

---

## 3. Firewall

- Servidor **intermediário de segurança**.
- **Restringe acessos externos** a serviços do servidor local.
- Protege a rede interna contra acessos indevidos vindos de fora.

> Direção do controle: **externa → interna**

---

## 4. Web Server

- Processa dados e faz requisições.
- É onde fica hospedada a sua aplicação.
- Exemplo: servidor de **API**.

---

## 5. E-mail Server

- Servidor voltado para e-mail.
- Responsável por:
  - armazenamento;
  - processamento;
  - envio.

---

## 6. Database Server

- Servidor onde o **banco de dados** fica hospedado.
- Responsabilidades:
  - armazenar arquivos físicos;
  - ceder memória RAM;
  - processar cálculos brutos;
  - gravar dados em disco;
  - executar leitura física;
  - gerenciar energia do sistema;
  - manter o hardware ativo;
  - sustentar tráfego de rede;
  - disponibilizar recursos computacionais.

---

## 7. Intranet

- Servidores **sem internet** que funcionam apenas localmente.
- Rodam apenas dentro de uma **rede corporativa**.
- Usados para serviços internos de uma empresa.

---

## 8. DNS (Domain Name System)

- Servidor de **domínio**.
- Redireciona o **nome do domínio** para o **IP** correspondente.
- Traduz nomes legíveis (ex.: `meusite.com.br`) em endereços IP.

---

## 9. Registro de domínios no Brasil

- Aplicações web brasileiras registram seus domínios no **registro.br**.
- É o órgão responsável pelos domínios `.br`.

---

## 10. Resumo visual

| Tipo | Função principal |
|---|---|
| Proxy | Intermedia e restringe acesso interno → externo |
| Firewall | Restringe acesso externo → interno |
| Web Server | Processa e responde requisições da aplicação |
| E-mail Server | Armazena, processa e envia e-mails |
| Database Server | Hospeda o banco de dados e seus recursos |
| DNS | Traduz domínio em IP |
| Intranet | Rede local corporativa sem internet |

---

## 11. Fluxo resumido

**Cliente interno → Proxy → Internet → Firewall → Servidor Local → Aplicação**

**Domínio (registro.br) → DNS → IP do servidor**