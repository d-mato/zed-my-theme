# My Theme

A personal theme for Zed, based on the [GitHub VS Code theme](https://github.com/primer/github-vscode-theme) (v6.3.5). The initial palette was converted with Zed's [theme_importer](https://github.com/zed-industries/zed/tree/main/crates/theme_importer) and is being customized from there.

## Variants

- **My Theme Dark** — based on GitHub Dark Default (bg: `#0d1117`)
- **My Theme Light** — based on GitHub Light Default (bg: `#ffffff`)
- **My Theme Dark Dimmed** — based on GitHub Dark Dimmed (bg: `#22272e`)

## Development

1. Run `zed: install dev extension` from the Zed command palette and select this directory
2. Edit `themes/my-theme.json`; changes are applied on save

### Checks

CI validates the theme files against the official Zed theme schema on every
push and pull request. To run the same check locally:

```sh
pipx run check-jsonschema \
  --schemafile https://zed.dev/schema/themes/v0.2.0.json \
  themes/*.json
```

## License

MIT — the color palette is derived from [primer/github-vscode-theme](https://github.com/primer/github-vscode-theme) (MIT, Copyright (c) 2020 Primer).
