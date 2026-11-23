# CRM Ultra Comercial

Contatos da tabela `public.rota_contatos`. Publica em **ultracomercial.vercel.app**.
Um arquivo só: `index.html`. A lista de responsáveis é `CFG.EQUIPE` (fonte única:
filtro, selects do card e do painel, "Você é…").

## Deploy
Projeto Vercel `ultracomercial` **ligado ao Git** (`Bezin123123/ultracomercial`, branch `main`):
push no `main` publica em produção sozinho (confirmado em 23/11/26: o deploy do commit
`94fa53c` veio com `source: git`). Não precisa de `vercel deploy`.
Até então o site era um carregador pequeno fixo num SHA do GitHub; isso acabou — conferir
sempre que o `curl` de `ultracomercial.vercel.app` traz a página inteira, não um loader.

## Histórico
- 23/11/26: Allan entrou como responsável (`EQUIPE`).
