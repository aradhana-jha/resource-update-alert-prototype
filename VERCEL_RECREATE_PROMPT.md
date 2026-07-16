# Prompt For Vercel/V0 Recreate

Recreate and deploy this prototype exactly as provided in the attached project files.

Requirements:

- Use `index.html` as the source of truth.
- Preserve every screen, field, label, CTA, route, modal, scenario, workflow state, visual style, and interaction exactly.
- Do not redesign, simplify, rewrite copy, rename fields, reorder fields, remove fields, add fields, change colors, change spacing, change typography, or replace the Practical Law document page treatment.
- Preserve all four test outcomes: Happy path, Missing category, High-confidence duplicate, and Possible duplicate.
- Preserve the recovery path where a document alert was sent first and the Resource Update Alert is generated later without resending the document alert.
- Preserve the consumer-facing Practical Law document view opened from the subscriber alert preview.
- Preserve the high-confidence duplicate behavior: the merged alert draft is read-only by default, `Edit draft` unlocks the title/body, `Done editing` locks them again, `Unmerge alert` remains available, and the subscriber preview shows both related resources as plain links with no internal labels.
- Preserve hash-based routes such as `#search`, `#auto-merge`, `#email`, and `#document-focus`.
- Deploy as a static site with `index.html` at the root and `assets/pl-toolbar-rail.png` available at `/assets/pl-toolbar-rail.png`. Do not add a server entrypoint.

Final journey URL after deployment should be:

```text
https://YOUR-VERCEL-DOMAIN/?v=subscriber-copy-clean-final#search
```

Do not make any changes unless explicitly requested.
