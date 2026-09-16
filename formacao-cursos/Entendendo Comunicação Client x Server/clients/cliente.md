---
modulo: <O que são clientes>
tags:
  - web
  - http
  - cliente-servidor
  - front-end
  - cache
criado: 2026-09-16
status: rascunho
---

# Fundamentos da Web

## 1. Conceitos principais

### Cliente (Client)
- Dispositivo, navegador ou aplicação que faz solicitações ao servidor.
- O usuário utiliza o cliente para acessar páginas, sistemas e serviços.
- Comunicação pela internet, normalmente via **HTTP/HTTPS**.
- **HTTPS** é a versão segura do HTTP, pois usa criptografia.

> O cliente **não é** o usuário. O usuário é quem utiliza o cliente — como o navegador.

### Servidor (Server)
- Máquina ou serviço que armazena, processa e responde às solicitações.
- Pode hospedar sites, APIs, bancos de dados, arquivos etc.
- Responsável por entregar as informações solicitadas pelo cliente.

### Hospedar
- Colocar uma aplicação ou site em um servidor para que fique disponível na internet.
- Pode ser em servidor compartilhado, VPS, nuvem etc.

## 2. Ciclo de requisição e resposta

1. O cliente faz uma solicitação pela internet.
2. O servidor processa a solicitação.
3. O servidor devolve uma resposta pela internet.
4. O cliente renderiza a resposta.

> Ver também: [[web-vs-internet]] e [[clientes-http]].

### Cache
- O navegador pode armazenar recursos temporariamente (HTML, CSS, JS, imagens).
- Evita baixar tudo novamente a cada acesso.
- Melhora desempenho e reduz tráfego de dados.

> O termo mais adequado é **cache do navegador** ou **armazenamento em cache**, e não "memória estática".
> O cache pode ficar em memória ou em disco, dependendo do navegador e do tipo de recurso.

## 3. Desempenho e experiência do usuário

### Velocidade e otimização
- Buscar simplificar e otimizar arquivos HTML, CSS e JavaScript.
- Técnicas comuns:
  - minificação de arquivos;
  - compressão;
  - otimização de imagens;
  - uso de cache;
  - carregamento assíncrono e lazy loading.
- Reduz volume de dados e melhora tempo de carregamento e experiência do usuário.

### Refresh
- Atualiza a página buscando informações mais atuais.
- Pode aproveitar o cache ou forçar nova busca dos arquivos.
- `Ctrl + F5` geralmente força a atualização ignorando o cache.

## 4. Front-end

- Área focada na experiência do cliente.
- Trabalha com HTML, CSS e JavaScript no lado do cliente.
- Preocupações principais:
  - design responsivo;
  - adaptação a diferentes tamanhos de tela;
  - usabilidade;
  - acessibilidade.

## 5. Navegadores (Browsers)

- Testar a aplicação em diferentes navegadores.
- Objetivo: garantir compatibilidade e funcionamento em vários dispositivos.
- Boas práticas:
  - testar em Chrome, Firefox, Edge, Safari etc.;
  - testar em desktop, tablet e celular;
  - validar responsividade;
  - verificar diferenças de comportamento entre navegadores.

> Ver também: [[formacao-cursos/Entendendo Comunicação Client x Server/clients/navegadores|navegadores]] (complementar).

## 6. Resumo visual

| Conceito  | Definição rápida                                     |
| --------- | ---------------------------------------------------- |
| Cliente   | Dispositivo/navegador que solicita recursos          |
| Servidor  | Processa e responde solicitações                     |
| Hospedar  | Disponibilizar aplicação em um servidor              |
| Cache     | Armazenamento temporário para evitar novos downloads |
| Refresh   | Recarregar/atualizar a página                        |
| Front-end | Parte visual e interativa voltada ao usuário         |
| Browsers  | Navegadores que precisam ser testados                |

## 7. Fluxo resumido

**Cliente → Internet (HTTP/HTTPS) → Servidor → Processamento → Resposta → Cliente → Cache/Renderização**

## Relacionado
- [[aplicacoes]] (mesma pasta)
- [[formacao-cursos/Entendendo Comunicação Client x Server/clients/navegadores|navegadores]] (complementar)
- [[clientes-http]] (complementar)
- [[web-vs-internet]] (complementar)

## Referências
- Aula: Cliente no Linguajar Web