---
tema: ferramentas
tags: [http, api, curl, postman]
criado: 2026-09-16
status: consolidado
---

# Clientes HTTP

## Contexto
O navegador é só um dos clientes que falam HTTP/HTTPS. Para acessar dados e serviços, qualquer cliente HTTP serve.

## Exemplos de clientes que não são navegador

- `curl https://api.github.com/users/octocat`
- Postman / Insomnia
- Apps móveis consumindo APIs
- Bots de busca
- Scripts Python com `requests`

## Por que isso importa

- **Para visualizar** uma página como usuário comum, normalmente usamos navegador — ver [[anotacoes-complementares/fundamentos/navegadores]].
- **Para acessar dados e serviços**, não é obrigatório.
- No back-end, testar APIs sem navegador é o fluxo normal.

## Relacionado
- [[anotacoes-complementares/fundamentos/navegadores]]
- [[só-acesso-web-pelo-navegador]]

## Referências
- 