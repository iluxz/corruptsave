# CorruptSave

CorruptSave is a tiny browser game where the save data is part of the gameplay. You can play it normally, or edit its state through the in-game editor, browser devtools, URL params, localStorage, sessionStorage, cookies, IndexedDB, or the console.

## Play

Open `index.html` in a browser.

## What you can edit

- In-game editor panel (right side)
- `localStorage` key: `corruptsave_state`
- `sessionStorage` key: `corruptsave_session`
- Cookie: `corruptsave_cookie`
- IndexedDB: `CorruptSaveDB` / object store `saves` / key `state`
- URL params: `?gold=NaN&hp=Infinity&name=null`
- Console: `game.state.gold = Infinity; game.render(); game.save();`

## Special values

- `NaN`: math/combat becomes confused and glitch effects appear.
- `Infinity`: ascended/broken behavior (overpowered or absurd values).
- `-Infinity`: void/collapse behavior.
- `null`/`undefined`/empty names: identity corruption flavor.

## Tutorial

The game includes a first-run tutorial modal. You can reopen it with the "Tutorial" button.

## Development

This is a static single-file project:

- `index.html` - game, UI, styles, and logic

No build step required.

## Repo notes

- License: MIT (`LICENSE`)
- Contributing: `CONTRIBUTING.md`
- Code of Conduct: `CODE_OF_CONDUCT.md`
