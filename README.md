# React + TypeScript + Vite

## Running

> Node version: v20.10.0

Running app with its API. 
It requires back-end-api project running in parallel.
```sh
pnpm run dev
```

Running app without its API.
Uses Mock Service Worker (MSW) to simulate the back-end. 
```sh
pnpm run dev:test
```

Running E2E Tests with UI rendering (Playwright).
```sh
pnpm run dev:test-ui
```