# devzz-base-vite-shadcn

Base template **Vite + React + TypeScript + Tailwind v3** for Devzz sandboxes (E2B / CodeSandbox).

- Dev server: `0.0.0.0:5173` (required for E2B preview)
- Plugin: `@vitejs/plugin-react-swc`
- Path alias: `@/` → `src/`

## Publish E2B snapshot

From the main `devzz.toolzz.ai` repo (with `E2B_API_KEY`):

```bash
pnpm tsx scripts/build-e2b-template-vite.ts
```

Creates/updates E2B template `vite-react-toolzz` (tag `:default`).
