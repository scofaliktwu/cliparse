# cliparse

Learning TypeScript by building tiny CLIs

## Highlights

- Ships as an ESM binary
- commander-based subcommands
- npm link friendly
- Strict tsconfig, no any

## Getting started

```bash
npm install
npm run build
```

## How to use

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── src/
│   ├── config.js
│   └── index.ts
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Why

Needed this for myself; figured others might too.

## License

MIT - see [LICENSE](LICENSE).
