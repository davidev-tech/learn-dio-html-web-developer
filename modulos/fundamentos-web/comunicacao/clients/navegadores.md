# Anotações de Aula — Navegadores e Compatibilidade Web

## 1. O que são navegadores?

- Navegadores são programas criados por empresas para abrir, interpretar e executar arquivos web.
- Também são chamados de **browsers**.
- São responsáveis por renderizar páginas compostas por:
  - HTML
  - CSS
  - JavaScript
  - imagens, vídeos, fontes etc.
- A maioria dos navegadores é gratuita.

---

## 2. Padrão W3C

- A **W3C** é o *World Wide Web Consortium*.
- É uma organização que cria regras e padrões técnicos para a web.
- O objetivo é garantir que sites funcionem de forma semelhante em qualquer navegador ou dispositivo.
- Seguir os padrões da W3C ajuda na:
  - compatibilidade;
  - acessibilidade;
  - padronização do código;
  - estabilidade entre navegadores.

---

## 3. Linha do tempo dos navegadores

- O primeiro navegador de destaque foi o **Mosaic**.
- Depois, veio o **Netscape**.
- Hoje existem diversos navegadores, como:
  - Google Chrome
  - Mozilla Firefox
  - Microsoft Edge
  - Safari
  - Opera
  - Brave

---

## 4. Compatibilidade entre navegadores

- Existem recursos HTML, CSS e JavaScript que funcionam em todos os navegadores.
- Outros recursos são mais específicos e podem não funcionar em todos.
- Por isso, é importante testar a aplicação em diferentes navegadores e dispositivos.
- Boas práticas:
  - testar em desktop e mobile;
  - verificar versões antigas quando necessário;
  - consultar tabelas de compatibilidade;
  - evitar recursos sem suporte amplo, ou fornecer alternativas.

---

## 5. Comandos, tags e atributos

- “Comandos gerais” podem ser entendidos como **tags e atributos HTML** com suporte amplo.
- Exemplos de suporte universal:
  - `<a>`
  - `<p>`
  - `<div>`
  - `<img>`
  - `<h1>` a `<h6>`
- Alguns atributos e tags possuem suporte mais recente ou parcial.
- Exemplos de recursos com suporte variável:
  - `<dialog>`
  - `loading` em `<img>`
  - `srcset`
  - `referrerpolicy`
  - `minlength`

---

## 6. Ferramenta de consulta

Site para verificar compatibilidade de tags e atributos HTML:

- [W3Schools — HTML Reference Browser Support](https://www.w3schools.com/tags/ref_html_browsersupport.asp)

Como interpretar a tabela:

| Indicação | Significado |
|---|---|
| Yes | Suporte total naquela versão ou anterior |
| Número | Versão mínima que passou a suportar |
| No | Sem suporte |
| ? | Informação desconhecida ou não confirmada |

---

## 7. Resumo

- Navegadores são programas que interpretam e exibem páginas web.
- Também são chamados de browsers.
- A W3C define padrões para a web.
- A história dos navegadores passa por Mosaic, Netscape e a variedade atual.
- A maioria dos navegadores é gratuita.
- Nem todo recurso funciona igual em todos os navegadores.
- Testes de compatibilidade são essenciais.
- A W3Schools possui uma tabela útil de suporte dos navegadores.