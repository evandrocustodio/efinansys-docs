# Documentos legais

Fonte oficial dos textos exibidos no eFinansys (web e app).

| Arquivo | Uso |
|---------|-----|
| `politica-privacidade.md` | Página web `/politica-privacidade` |
| `termos-de-uso.md` | Página web `/termos-de-uso` |
| `politica-privacidade.txt` | App mobile (carregamento simplificado) |
| `termos-de-uso.txt` | App mobile (carregamento simplificado) |

## Edição

1. Altere o `.md` (web) e mantenha o `.txt` correspondente alinhado (app).
2. No projeto `efinansys`, rode `npm run sync-legal-docs` (ou `npm run dev` / `npm run build`, que sincronizam automaticamente).
3. Publique/commit este repositório e faça deploy do frontend.

## Formatação

**Markdown (web):** `##` para seções, `**texto**` para destaque, `- item` para listas.

**Texto (app):** `##` para seções, `- item` para listas, sem marcação Markdown inline.
