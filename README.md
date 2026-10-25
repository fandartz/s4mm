# Sims4MM — Mod Manager for The Sims 4

A Windows app that keeps your `Mods` folder healthy: it finds broken, duplicate
and conflicting mods, checks script mods against the current game patch, tells
you which mods are out of date and updates them in one click, straight from
the mod author's site.

## What it does

**Free**

- Scans `Mods` for broken or empty packages, leftover archives, scripts placed
  too deep, and files from other games.
- Finds exact duplicates and **visual duplicates** of CAS items (same mesh and
  textures under different names), with previews.
- Detects resource conflicts and "invisible" items with missing resources.
- Flags script mods that import game modules removed by the latest patch, and
  mods missing a required library (S4CL, XML Injector, Lot51 Core).
- Reads `lastException.txt` and points to the mod behind the error.
- Finds a broken mod with a 50/50 search.
- Quarantine, backups of mods and saves, cache cleanup, and a "Play" button.
- Shows which installed mods have updates, with a link to the author's page.

**PRO**

- One-click mod updates, with the old version kept in a backup.
- Patch compatibility checks for installed mods.
- A guard mod that stops crashes in other mods' fragile code from taking the
  game down.

## How updates work

- The server keeps a catalog of hundreds of popular mods and refreshes it on
  its own: it checks the authors' sites daily for new mods and re-checks every
  mod's latest release every few hours.
- For each release it records the files inside it. The app compares the
  **contents** of your installed files with those releases, so it knows
  exactly whether a mod is current and which version you have, even when the
  file name doesn't say.
- Downloads go **straight from the author's own link** to your PC. Mod files
  are never re-hosted or passed through our servers. If an author doesn't
  allow third-party downloads, the app simply opens their page.
- Missing a mod? Paste a link to its page and it's added for everyone. Mods the
  catalog doesn't know yet are looked up automatically.

## What's next

- One-click updates for CurseForge mods (S4CL, XML Injector, T.O.O.L.,
  Lot51, LittleMsSam and more) once official API access is approved.
- More supported mod sites.
- A public website.

## Status

In development. There's no public website yet.
