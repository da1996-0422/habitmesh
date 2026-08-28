# habitmesh

Small Vue 3 side project: track daily habits as a heatmap grid

Built for my own use; public in case it helps someone.

## Getting started

```bash
npm install
npm run dev
```

## Features

- GitHub-style contribution grid per habit
- State persisted to localStorage
- Vite dev setup with hot reload
- Composition API + script setup

## Examples

```bash
# open http://localhost:5173
# click a cell to toggle that day
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── pull_request_template.md
├── docs/
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── App.vue
│   ├── config.js
│   └── store.js
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── package.json
└── vite.config.js
```
