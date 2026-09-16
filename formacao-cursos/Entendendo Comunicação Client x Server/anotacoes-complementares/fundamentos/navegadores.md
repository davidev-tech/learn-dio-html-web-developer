---
tema: fundamentos
tags: [web, navegador, http, dom]
criado: 2026-09-16
status: consolidado
---

# Navegadores

## Contexto
Entender o que o navegador realmente faz e como ele se posiciona dentro da Web (não é a Web em si).

## O que é o navegador?

É um **cliente HTTP/HTTPS** que:

- faz requisições a servidores;
- baixa recursos (HTML, CSS, JS, imagens, JSON...);
- interpreta HTML e constrói o **DOM**;
- aplica CSS e monta o layout visual;
- executa JavaScript;
- gerencia cookies, cache, sessão e segurança.

> O navegador não "abre uma aplicação web" como um `.exe`. Ele baixa, interpreta e renderiza recursos web.

## O que significa "interpretar, abrir e exibir"?

- HTML → DOM
- CSS → estilos e layout
- JavaScript → comportamento dinâmico
- Resultado → pixels na tela

Já PHP, Python, Node.js, Java, Ruby etc. normalmente rodam no **servidor**.
O servidor processa e envia uma resposta (HTML, JSON...).
O navegador recebe e executa apenas o que for front-end.

## Implicações para desenvolvimento web

- **Front-end**: muito contato com navegador, DOM, eventos, DevTools e compatibilidade entre Chrome, Firefox, Safari etc.
- **Back-end/APIs**: pode testar tudo sem navegador — ver [[clientes-http]].
- **Aplicações modernas**: o navegador roda a interface (React, Vue, Angular) e consome APIs que devolvem JSON.
- **Apps móveis e outros clientes**: podem consumir a mesma API que o navegador consome — ver [[onde-o-html-roda]].

## Resumo

- **Web** = conjunto de recursos e protocolos (ver [[web-vs-internet]]).
- **Navegador** = cliente que acessa, interpreta e renderiza recursos web para humanos.
- Para **visualizar** uma página como usuário comum, normalmente usamos navegador.
- Para **acessar dados e serviços**, qualquer cliente HTTP serve (ver [[clientes-http]]).
- O navegador é essencial para desenvolvimento web, mas **não é a Web em si**.

## Relacionado
- [[web-vs-internet]]
- [[clientes-http]]
- [[onde-o-html-roda]]
- [[só-acesso-web-pelo-navegador]]

## Referências
- 