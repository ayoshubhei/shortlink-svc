# shortlink-svc

Small bookmark service with search and tags

Small but I use it weekly.

## Install

```bash
npm install
npm run dev
```

## Features

- In-memory store with optional JSON persistence
- Request validation helpers, no framework magic
- Ready for Render/Fly deploy with PORT env
- Morgan logging and centralized error handler
- REST endpoints: list / create / delete / search

## Usage

```bash
curl -X POST localhost:3000/api/bookmarks \
  -H 'content-type: application/json' \
  -d '{"url": "https://example.com", "tags": ["reading"]}'
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── src/
│   ├── config.js
│   ├── index.js
│   └── store.js
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## License

MIT - see [LICENSE](LICENSE).
