---
tema: comparativos
tags: [webview, react-native, flutter, mobile]
criado: 16-09-2026
status: consolidado
---

# WebView vs Nativo

## Contexto
Comparativo entre frameworks que usam WebView e frameworks que renderizam nativamente. Complementa [[onde-o-html-roda]].

## Tabela comparativa

| Tipo | Exemplos | Usa WebView? | Como renderiza |
|---|---|---|---|
| Web tradicional | Navegadores | Sim, é o próprio navegador | HTML/CSS/JS no navegador |
| Híbridos | Cordova, Ionic, Electron | Sim | HTML/CSS/JS em navegador invisível |
| Nativos modernos | React Native, Flutter | Não | Componentes nativos na tela |

## Quando escolher cada um

- **Híbrido / WebView**: quando o time já domina web e quer reaproveitar código. Aceita-se troca de desempenho.
- **Nativo moderno**: quando desempenho e aparência nativa são prioridade. Não reaproveita HTML/CSS diretamente.

## Relacionado
- [[onde-o-html-roda]]
- [[anotacoes-complementares/fundamentos/navegadores]]

## Referências
- 