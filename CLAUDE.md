# CRM Ultra Comercial

Contatos da tabela `public.rota_contatos`. Publica em **ultracomercial.vercel.app**.
Um arquivo só: `index.html`. A lista de responsáveis é `CFG.EQUIPE` (fonte única:
filtro, selects do card e do painel, "Você é…").

## Deploy
Projeto Vercel `ultracomercial` **ligado ao Git** (`Bezin123123/ultracomercial`, branch `main`):
push no `main` publica em produção sozinho (confirmado em 23/11/26: o deploy do commit
`94fa53c` veio com `source: git`). Não precisa de `vercel deploy`.
A função de Indicação agora está no código; não existe mais carregador com remendos.
Conferir sempre que o `curl` de `ultracomercial.vercel.app` traz a página inteira, não um loader.

## Histórico
- 23/11/26: Allan entrou como responsável (`EQUIPE`).
- 24/11/26: Indicação (chip "Só indicações", etiqueta ⭐ no card, template "Indicação de cliente", campo na ficha) entrou no `index.html` (`711a2fe`); antes vivia só nos remendos do carregador.
