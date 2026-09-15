# Anotações de Aula — Fundamentos da Web

## 1. Conceitos principais

### Cliente (Client)
- É o dispositivo, navegador ou aplicação que faz solicitações ao servidor.
- O usuário utiliza o cliente para acessar páginas, sistemas e serviços.
- A comunicação ocorre pela internet, normalmente via **HTTP/HTTPS**.
- **HTTPS** é a versão segura do HTTP, pois utiliza criptografia.

> Observação: o cliente não é exatamente o usuário. O usuário é quem utiliza o cliente, como o navegador.

### Servidor (Server)
- Máquina ou serviço que armazena, processa e responde às solicitações.
- Pode hospedar sites, APIs, bancos de dados, arquivos etc.
- É o responsável por entregar as informações solicitadas pelo cliente.

### Hospedar
- Ato de colocar uma aplicação ou site em um servidor para que fique disponível na internet.
- Pode ser feito em servidor compartilhado, VPS, nuvem etc.

---

## 2. Ciclo de requisição e resposta

1. O cliente faz uma solicitação pela internet.
2. O servidor processa a solicitação.
3. O servidor devolve uma resposta pela internet.
4. O cliente renderiza a resposta.

### Cache
- O navegador pode armazenar recursos temporariamente, como HTML, CSS, JavaScript e imagens.
- Isso evita baixar tudo novamente a cada acesso.
- Melhora o desempenho e reduz o tráfego de dados.

> Correção: o termo mais adequado é **cache do navegador** ou **armazenamento em cache**, e não “memória estática”.
> O cache pode ficar em memória ou em disco, dependendo do navegador e do tipo de recurso.

---

## 3. Desempenho e experiência do usuário

### Velocidade e otimização
- Buscar simplificar e otimizar arquivos **HTML, CSS e JavaScript**.
- Técnicas comuns:
  - minificação de arquivos;
  - compressão;
  - otimização de imagens;
  - uso de cache;
  - carregamento assíncrono e lazy loading.
- Isso reduz o volume de dados e melhora o tempo de carregamento e a experiência do usuário.

### Refresh
- Atualiza a página buscando informações mais atuais.
- Pode aproveitar o cache ou forçar uma nova busca dos arquivos.
- Atalhos como `Ctrl + F5` geralmente forçam a atualização ignorando o cache.

---

## 4. Front-end

- Área focada na experiência do cliente.
- O desenvolvedor front-end trabalha com HTML, CSS e JavaScript no lado do cliente.
- Preocupações principais:
  - design responsivo;
  - adaptação para diferentes tamanhos de tela;
  - usabilidade;
  - acessibilidade.

---

## 5. Navegadores (Browsers)

- É necessário testar a aplicação em diferentes navegadores.
- Objetivo: garantir compatibilidade e funcionamento correto em vários dispositivos.
- Boas práticas:
  - testar em Chrome, Firefox, Edge, Safari etc.;
  - testar em desktop, tablet e celular;
  - validar responsividade;
  - verificar diferenças de comportamento entre navegadores.

---

## 6. Resumo visual

| Conceito | Definição rápida |
|---|---|
| Cliente | Dispositivo/navegador que solicita recursos |
| Servidor | Processa e responde solicitações |
| Hospedar | Disponibilizar aplicação em um servidor |
| Cache | Armazenamento temporário para evitar novos downloads |
| Refresh | Recarregar/atualizar a página |
| Front-end | Parte visual e interativa voltada ao usuário |
| Browsers | Navegadores que precisam ser testados |

---

## 7. Fluxo resumido

**Cliente → Internet (HTTP/HTTPS) → Servidor → Processamento → Resposta → Cliente → Cache/Renderização**