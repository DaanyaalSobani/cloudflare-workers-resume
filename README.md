# Daanyaal Sobani — Resume Site

A personal resume and cover letter site built with Astro and deployed on Cloudflare Workers.

**Live site:** [cloudflare-workers-resume.daanyaal-dev.workers.dev](https://cloudflare-workers-resume.daanyaal-dev.workers.dev)

Built as part of an application for the Forward Deployed Engineer role at Cloudflare. The site itself demonstrates direct, hands-on experience with the Cloudflare Workers platform — Astro SSR via the `@astrojs/cloudflare` adapter, deployed with Wrangler, with built-in Workers Observability enabled. Assembled with Claude Code.

## Stack

- [Astro](https://astro.build) — SSR framework
- [`@astrojs/cloudflare`](https://docs.astro.build/en/guides/integrations-guide/cloudflare/) — Cloudflare Workers adapter
- [Wrangler](https://developers.cloudflare.com/workers/wrangler/) — deployment tooling

## Commands

| Command              | Action                                      |
| :------------------- | :------------------------------------------ |
| `npm install`        | Install dependencies                        |
| `npm run dev`        | Local dev server at `localhost:4321`        |
| `npm run build`      | Build to `./dist/`                          |
| `npm run preview`    | Build + run via `wrangler dev`              |
| `npm run deploy`     | Deploy to Cloudflare Workers                |
| `npm run check`      | Build + typecheck + dry-run deploy          |
