# Documentos legais

Fonte oficial dos textos exibidos no eFinansys (web e app).

| Arquivo | Rota pública |
|---------|--------------|
| `politica-privacidade.md` | `/politica-privacidade` |
| `termos-de-uso.md` | `/termos-de-uso` |

## Edição

1. Altere o arquivo `.md` desejado nesta pasta.
2. No projeto `efinansys`, rode `npm run sync-legal-docs` (ou `npm run dev` / `npm run build`, que sincronizam automaticamente).
3. Publique/commit este repositório e faça deploy do frontend.

## Formatação

Use Markdown simples:

- `##` para seções (aparecem no índice da página)
- `**texto**` para destaque
- `- item` para listas
