# CLAUDE.md

Notes for working in this clone. This file lives only on `local_dev` and is not meant to go upstream.

## Repo layout

- `upstream` = justcallmekoko/ESP32Marauder (the real project). Never push here.
- `origin` = dr3x/ESP32Marauder (Dave's fork).
- `master` and `develop` mirror upstream. Do not commit on them.
- `local_dev` = personal branch, cut from `master`. All local customizations go here.

## Keeping local_dev current

<!-- TODO: rebase or merge onto upstream/master? Record the choice and the commands. -->

## Customizations on this branch

Add one entry per change so it can be re-applied or dropped when upstream moves.

| Commit | What | Why | Upstream candidate? |
|---|---|---|---|
| `ea1aa80` | Ignore `.vscode/extensions.json` and `.vscode/launch.json` | PlatformIO generates them; `launch.json` hardcodes local paths | No |

## Hardware and build targets

<!-- TODO: which board(s) are built and flashed from this clone, and with what command. -->

## Conventions

- Files are checked out with CRLF (`core.autocrlf=true`); keep line endings consistent when editing.
- A tag named `master` exists on `origin`, so the bare name `master` can be ambiguous. Use `refs/heads/master` if a command complains.

## Open items

<!-- TODO -->
