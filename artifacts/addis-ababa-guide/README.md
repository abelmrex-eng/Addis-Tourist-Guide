# Addis Ababa Travel Guide

A responsive, single-page guide for visitors to Addis Ababa. It covers city landmarks, Ethiopian food and coffee, local culture, useful travel facts, and practical tips.

## Run locally

From the workspace root:

```sh
BASE_PATH=/ PORT=24300 pnpm --filter @workspace/addis-ababa-guide run dev
```

Open `http://localhost:24300/` in a browser.

## Build

```sh
BASE_PATH=/ PORT=24300 pnpm --filter @workspace/addis-ababa-guide run build
```

The production files are written to `artifacts/addis-ababa-guide/dist/public/`.

## Main files

- `index.html` — the guide page, including its styles and page behavior.
- `package.json` — development and build commands.
- `vite.config.ts` — Vite configuration for the workspace artifact.
