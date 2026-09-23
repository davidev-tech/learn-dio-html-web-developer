---
modulo: O que são servers
tags:
  - formacao-html
  - servidores
  - infraestrutura
criacao: 2026-09-22
status: em-andamento
---

# Anotações de Aula — Servidores

## 1. Conceitos principais

### Servidor (Server)
- Máquina ou serviço responsável por armazenar, processar e responder solicitações.
- Pode existir na **internet** ou em ambiente **local**.
- Precisa ser mais **robusto** que uma máquina comum, pois:
  - exige processamento constante;
  - recebe várias pessoas e dispositivos conectados ao mesmo tempo;
  - faz muitas requisições simultâneas.
- Por isso, tende a ser mais **potente** e mais **caro**.

### Servidor local
- Fica dentro da própria rede/ambiente do usuário.
- Usado para testes, desenvolvimento ou serviços internos.

### Servidor na internet
- Fica acessível remotamente pela web.
- É o modelo usado para hospedar sites e aplicações públicas.

### Data center
- Local físico que reúne vários servidores/máquinas.
- Pode variar de uma sala pequena a estruturas gigantescas.

---

## 2. Propriedades dos servidores

- **Armazenamento** — capacidade de guardar arquivos, bancos de dados e aplicações.
- **Processamento (CPU)** — potência para lidar com várias requisições ao mesmo tempo.
- **Memória (RAM)** — necessária para manter processos e conexões ativas.
- **Largura de banda** — capacidade de tráfego de dados de entrada e saída.
- **Disponibilidade** — precisa funcionar de forma contínua (24/7).
- **Escalabilidade** — capacidade de crescer conforme a demanda aumenta.
- **Redundância** — cópias de segurança para evitar falhas totais.
- **Segurança** — proteção contra acessos indevidos e ataques.

> Essas propriedades explicam por que servidores são mais potentes e mais caros que máquinas comuns.

---

## 3. Tipos de servidores

| Tipo | Função |
|---|---|
| Arquivos | Armazenar e disponibilizar arquivos |
| Segurança (Firewall) | Filtrar e proteger o tráfego de rede |
| Streaming | Entregar áudio e vídeo sob demanda |
| E-mail | Enviar, receber e armazenar mensagens |
| Web | Hospedar e servir sites e aplicações |

> Observação: um mesmo servidor físico pode acumular mais de uma função, dependendo da configuração.

---

## 4. Estruturas e tamanhos

- Existem servidores pequenos, que ficam em um canto de sala ou escritório.
- Existem estruturas enormes que reúnem vários servidores/máquinas: os **data centers**.
- Data center é o local físico onde ficam armazenados diversos servidores.

---

## 5. Resumo visual

| Conceito             | Definição rápida                                       |
| -------------------- | ------------------------------------------------------ |
| Servidor             | Máquina que armazena, processa e responde solicitações |
| Servidor local       | Servidor dentro da própria rede/ambiente               |
| Servidor na internet | Servidor acessível remotamente pela web                |
| Data center          | Local que reúne vários servidores                      |
| Firewall             | Servidor/recurso de segurança de rede                  |

---

## 6. Fluxo resumido

**Cliente → Internet → Servidor → Processamento → Resposta → Cliente**