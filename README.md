# test-prepration

Front-end interview prep playground built with React 19, TypeScript, and Vite.

## Stack

- **React + TypeScript** via Vite
- **Linter:** [oxlint](https://oxc.rs/docs/guide/usage/linter) (config in `.oxlintrc.json`)
- **Test runner:** [Vitest](https://vitest.dev/) with jsdom and React Testing Library

## Scripts

| Command              | Description                          |
| -------------------- | ------------------------------------ |
| `npm run dev`        | Start the dev server with HMR        |
| `npm run build`      | Type-check and build for production  |
| `npm run preview`    | Preview the production build locally |
| `npm run lint`       | Lint the project with oxlint         |
| `npm run typecheck`  | Run the TypeScript compiler          |
| `npm test`           | Run the test suite once              |
| `npm run test:watch` | Run tests in watch mode              |

## Getting started

```bash
npm install
npm run dev
```

Tests live next to the code they cover (for example `src/App.test.tsx`). Shared test setup is in `src/test/setup.ts`.
