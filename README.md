# ts-toolkit-cli

Small TypeScript CLI: CSV to JSON converter

## Installation

```bash
npm install
npm run build
```

## Examples

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Highlights

- npm link friendly
- commander-based subcommands
- Ships as an ESM binary
- Strict tsconfig, no any

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── pull_request_template.md
├── docs/
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── index.ts
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```
