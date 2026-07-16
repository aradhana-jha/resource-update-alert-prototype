# Resource Update Alert Prototype

This folder contains the exact static prototype source for the Resource Update Alert workflow.

## Files

- `index.html`: full single-page prototype, including all screens, styling and interactions.
- `assets/pl-toolbar-rail.png`: Practical Law document toolbar image used by the document view.
- `server.js`: optional local static server.
- `package.json`: local preview scripts.
- `vercel.json`: Vercel static deployment headers.

## Local Preview

```bash
npm run dev -- --host 127.0.0.1 --port 4176
```

Then open:

```text
http://127.0.0.1:4176/?v=subscriber-copy-clean-final#search
```

## Vercel Deployment

Use this folder as the Vercel project root.

Recommended Vercel settings:

- Framework preset: Other
- Build command: leave empty
- Output directory: `.`
- Install command: leave empty

After deployment, use:

```text
https://YOUR-VERCEL-DOMAIN/?v=subscriber-copy-clean-final#search
```

## Important

Do not change the fields, copy, routes, workflow logic, scenarios, styling, or assets if the goal is to reproduce the current prototype exactly.
