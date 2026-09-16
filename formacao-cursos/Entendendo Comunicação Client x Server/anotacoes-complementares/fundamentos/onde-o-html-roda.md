---
tema: fundamentos
tags: [html, webview, mobile, electron]
criado: 2026-09-16
status: consolidado
---

# Onde o HTML Roda?

## Contexto
Nem toda aplicação que usa HTML roda dentro de um navegador visível. Este nota mapeia os três cenários possíveis.

## 1. HTML na Web

- Todo código HTML roda na web por meio de um navegador.
- O navegador interpreta HTML, CSS e JavaScript e renderiza a interface — ver [[anotacoes-complementares/fundamentos/navegadores]].

## 2. HTML fora do navegador tradicional

- Nem toda aplicação que usa HTML roda dentro de um navegador visível.
- Em alguns casos, o HTML é executado "por baixo dos panos".
- Esse método é chamado de **WebView**.

### O que é WebView?

- É um componente que funciona como um **navegador invisível**.
- Ele lê e renderiza HTML, CSS e JavaScript reais.
- É muito usado em aplicações mobile e desktop para reaproveitar código web.
- Em alguns frameworks, o conceito é adaptado: eles juntam tudo e renderizam diretamente na tela.

## 3. Frameworks que usam WebView

- **Cordova**
- **Ionic**
- **Electron**

Características:

- Usam WebView por baixo dos panos.
- HTML, CSS e JavaScript são executados dentro de um navegador embutido.
- A interface é basicamente uma página web rodando dentro de um app.
- **Vantagem**: reaproveitamento de código web.
- **Desvantagem**: desempenho pode ser inferior ao de interfaces nativas.

## 4. Frameworks que NÃO usam WebView

- **React Native**
- **Flutter**

Características:

- Não usam WebView.
- Geram a interface **nativa** diretamente na tela do celular.
- Cada componente é traduzido para elementos nativos do sistema operacional.
- **Vantagem**: melhor desempenho e aparência mais próxima do nativo.
- **Desvantagem**: não reaproveitam diretamente HTML/CSS como no caso da WebView.

## 5. Conclusão

- HTML pode rodar:
  - no navegador tradicional;
  - dentro de uma WebView em apps híbridos;
  - ou ser substituído por interfaces nativas em frameworks como React Native e Flutter.
- Entender essa diferença ajuda a escolher a tecnologia certa para cada projeto.

## Relacionado
- [[anotacoes-complementares/fundamentos/navegadores]]
- [[webview-vs-nativo]]

## Referências
- 