# efinansys-docs

Repositório oficial de documentos do **eFinansys**.

## Conteúdo

| Pasta / arquivo | Descrição |
|-----------------|-----------|
| `legal/politica-privacidade.md` | Política de Privacidade (LGPD) |
| `legal/termos-de-uso.md` | Termos de Uso |
| `legal/README.md` | Instruções de edição e formatação |

## Integração com o frontend

Os arquivos em `legal/` são a **fonte única de verdade**. O projeto `efinansys` sincroniza automaticamente esses `.md` para `public/` ao rodar:

- `npm run dev`
- `npm run build`
- `npm run sync-legal-docs`

Requisito: o clone de `efinansys-docs` deve ficar **ao lado** de `efinansys` (mesmo diretório pai).

```
cursor.ia/
├── efinansys/
├── efinansys-docs/
│   └── legal/
│       ├── politica-privacidade.md
│       └── termos-de-uso.md
└── ...
```

## Rotas públicas

- Web: `/politica-privacidade` e `/termos-de-uso`
- App mobile: abre as mesmas URLs do frontend web
