---
modulo: <O que são clientes>
tags:
  - navegadores
  - w3c
  - compatibilidade
  - html
criado: 2026-09-16
status: rascunho
---

# Navegadores e Compatibilidade Web

## 1. O que são navegadores?

- Programas criados por empresas para abrir, interpretar e executar arquivos web.
- Também chamados de **browsers**.
- Responsáveis por renderizar páginas compostas por:
  - HTML
  - CSS
  - JavaScript
  - imagens, vídeos, fontes etc.
- A maioria é gratuita.

> Ver também: [[formacao-cursos/Entendendo Comunicação Client x Server/clients/navegadores]] (complementar) — explica o papel do navegador como cliente HTTP.

## 2. Padrão W3C

- **W3C** = *World Wide Web Consortium*.
- Organização que cria regras e padrões técnicos para a web.
- Objetivo: garantir que sites funcionem de forma semelhante em qualquer navegador ou dispositivo.
- Seguir os padrões da W3C ajuda na:
  - compatibilidade;
  - acessibilidade;
  - padronização do código;
  - estabilidade entre navegadores.

## 3. Linha do tempo dos navegadores

- Primeiro navegador de destaque: **Mosaic**.
- Depois: **Netscape**.
- Hoje:
  - Google Chrome
  - Mozilla Firefox
  - Microsoft Edge
  - Safari
  - Opera
  - Brave

## 4. Compatibilidade entre navegadores

- Alguns recursos HTML, CSS e JavaScript funcionam em todos os navegadores.
- Outros são mais específicos e podem não funcionar em todos.
- Por isso, é importante testar em diferentes navegadores e dispositivos.
- Boas práticas:
  - testar em desktop e mobile;
  - verificar versões antigas quando necessário;
  - consultar tabelas de compatibilidade;
  - evitar recursos sem suporte amplo, ou fornecer alternativas.

## 5. Comandos, tags e atributos

- "Comandos gerais" = **tags e atributos HTML** com suporte amplo.
- Exemplos de suporte universal:
  - `<a>`
  - `<p>`
  - `<div>`
  - `<img>`
  - `<h1>` a `<h6>`
- Recursos com suporte variável:
  - `<dialog>`
  - `loading` em `<img>`
  - `srcset`
  - `referrerpolicy`
  - `minlength`

## 6. Ferramenta de consulta

- [W3Schools — HTML Reference Browser Support](https://www.w3schools.com/tags/ref_html_browsersupport.asp)

Como interpretar a tabela:

| Indicação | Significado |
|---|---|
| Yes | Suporte total naquela versão ou anterior |
| Número | Versão mínima que passou a suportar |
| No | Sem suporte |
| ? | Informação desconhecida ou não confirmada |

## 7. Resumo

- Navegadores são programas que interpretam e exibem páginas web.
- Também são chamados de browsers.
- A W3C define padrões para a web.
- A história dos navegadores passa por Mosaic, Netscape e a variedade atual.
- A maioria dos navegadores é gratuita.
- Nem todo recurso funciona igual em todos os navegadores.
- Testes de compatibilidade são essenciais.
- A W3Schools possui uma tabela útil de suporte dos navegadores.

## Relacionado
- [[formacao-cursos/Entendendo Comunicação Client x Server/clients/navegadores]] (complementar)

## Referências
- Aula: Navegadores e Compatibilidade Web
- [W3Schools — HTML Reference Browser Support](https://www.w3schools.com/tags/ref_html_browsersupport.asp)