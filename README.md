# micangasdajuh-quiz — Quiz + TSL de Brincos de Miçanga

Domínio: https://micangasdajuh.vercel.app (desde 22/11/2026; antes era a página de vendas,
que foi para https://micangasdajuh-backup.vercel.app — repo `micangasdajuh`).

- `/` (index.html) — quiz de 7 perguntas + TSL no fim, checkouts 17,90 e 27,90
- `/vendas` — cópia da página de vendas validada
- `/promo` — back redirect R$ 9,90
- `/ups`, `/upsell`, `/dows` — pós-venda da Wiapy (apontam para este domínio)

Local: `node servidor.cjs` → http://localhost:4181
Subir: `node scripts/publicar-site.cjs funis/micangasdajuh-quiz "msg"`
