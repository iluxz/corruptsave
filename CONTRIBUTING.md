# Contributing to CorruptSave

Thanks for wanting to mess with reality responsibly.

## Quick start

1. Fork or clone the repo.
2. Open `index.html` in a browser.
3. Make changes.
4. Test normal gameplay and corrupted-save cases.

## What to test

- Normal flow: fight, heal, shop, next zone, save/reset.
- Editor/import/export: JSON import, raw edits, URL params.
- Storage surfaces: localStorage, sessionStorage, cookie, IndexedDB.
- Weird values: `NaN`, `Infinity`, `-Infinity`, `null`, `undefined`, empty strings.
- Tutorial: first-run display and reopen button.

## Pull requests

- Keep changes small and clear.
- Describe what you changed and how you tested it.
- Avoid adding heavy dependencies; this project is intentionally simple/static.
- No secrets, API keys, or personal data in commits.

## Bug reports

When filing an issue, include:

- Browser and version
- Steps to reproduce
- Expected behavior
- Actual behavior
- Save JSON or URL params if relevant
