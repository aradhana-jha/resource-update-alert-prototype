# What To Share With Vercel

Share the zip file:

```text
resource-update-alert-vercel-export.zip
```

That zip contains everything needed to recreate the prototype:

- `index.html`
- `assets/pl-toolbar-rail.png`
- `package.json`
- `server.js`
- `vercel.json`
- `README.md`
- `VERCEL_RECREATE_PROMPT.md`

If Vercel asks for project settings, use:

```text
Framework preset: Other
Build command: leave empty
Output directory: .
Install command: leave empty
```

After deploy, open:

```text
https://YOUR-VERCEL-DOMAIN/?v=subscriber-copy-clean-final#search
```

If you are giving this to Vercel/v0/Codex as a prompt, upload the zip and paste the content from:

```text
VERCEL_RECREATE_PROMPT.md
```

Do not upload the larger `resource-update-alert-prototype` working folder. The `resource-update-alert-vercel-export.zip` file is the clean deployable package.
