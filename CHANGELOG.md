# Overseer 1.0 — First Public Release

The first official public build of Overseer: one file you download and double-click, no setup, everything bundled. This is the release that pulls the whole companion together — translation, prediction, deck-building and quality-of-life — into a polished, professional tool anyone can run.

---

## One-file install

- **Download one thing, `Overseer.exe`, and double-click it.** It finds your game on any Steam drive, installs itself, and opens the control panel. No extracting, no scripts, no Python or Node, nothing to configure.
- **Re-running it updates you.** A newer download refreshes the install in place while preserving your language packs and settings.
- **Runs on a clean PC.** The whole program is statically compiled — no Visual C++ redistributable, no runtime to install.

## Translation

- **English on the Japanese client, end-to-end** — not just the Global build. English is its own target language, with the engine pointed at Japanese source automatically the moment it detects the JP client. Play the version that gets content first, in a language you can read.
- **French and German ship built-in** and work **fully offline** — no download, no internet. 25+ more languages via an optional on-device neural model.
- **Accurate by design.** Text comes from the game's own strings, so stats read exactly and names are never turned into gibberish. A protected glossary locks the terms that have to be right.
- **A three-part engine** — a hand-tuned glossary, a cache of everything already seen, and an on-device model for the rest. Nothing is sent anywhere.
- **A clear guide** to the three ways it works (translate live · remember what it's seen · build the whole game in advance), and an **Off** switch for the in-game build so it never competes with your play.

## Know it before you click

- **Every event choice, decoded** from the game's own data — what each option really gives, with the recommended pick highlighted. When an outcome is a genuine gamble, Overseer says so instead of pretending certainty.
- **Race finishing-place forecast** at the entry screen, and this turn's **training numbers** — gains, skill-hint procs and failure chance — before you act.

## Deck Builder

- A full out-of-game builder on the game's own database: **effects breakdown, skills, skill analysis, training gains, and rainbow (specialty) odds** per training.
- **Your owned cards load automatically** as you play — now for every account, including fresh or rerolled ones with small collections.

## Native skip, on everything

- Skipping leans on the game's **own** Skip and Fast-Forward wherever one exists, instead of faking taps — faster, and it can't fall out of sync with the UI.
- **Race results** advance the instant a win is detected — and only on a win, never during Team Trials. **Consecutive-race warnings**, **skill purchases**, **Inspiration** and **training** all fold into the same native-first path.

## Team Trials, Veterans & tracking

- **Deck profiles** — save and swap your whole 15-Uma lineup in one click, up to five named teams, each pinned to exact Umas so a reshuffle can't break it silently.
- **Opponent finder** — auto-refreshes the list and pings you (banner, Windows notification, flashing taskbar) when a trainer you named appears.
- **Veterans** with inheritance sparks, a **career dashboard**, leaderboard and finished-run history, and **career webhooks** that deliver a rich summary — or a Discord embed — whenever a run wraps.

## Performance & visuals

- **Frame rate** capped 1–300 or fully unlocked, with a true measured counter.
- **Max 3D quality** beyond the in-game cap; **Low Resource mode** to strip the game down for weak machines; always-on-top, block-minimize and screen-mode controls.

## Accessibility

- **Reduce motion**, **high contrast** and **text scaling** now work throughout the panel, and honour your system's reduced-motion setting automatically.
- Essential text was brightened to meet contrast standards; colour-vision options are remembered between sessions.

## Reliability & stability

- A focused pass on every hard crash and soft-lock from real sessions: the **skill-purchase crash**, a whole class of **mid-career access-violation crashes** (from holding game objects the GC had moved), and boot-time issues are fixed. **Self-healing** clears a stuck internal flag every frame before a screen can freeze.
- Long-running hardening: bounded internal queues and channels so an idle session can't grow memory, and safe fallbacks on the text-wrapper so a pathological string can't take the game down.
- **Colour-vision filters** softened to a natural correction, and **translated text now fits its box** without touching the Latin/numeric UI around it.

## Privacy & protection

- The public build is **scrubbed of build-machine paths and identifiers** and carries no personal information. Proprietary logic is compiled to native code.
- **Everything stays local** — the panel is localhost-only and translation runs on your machine.
- **Diagnostics** export as a single plain-text file (never a zip) carrying your version, settings and the full session, so bug reports are one click.

---

*Overseer is an unofficial tool and isn't affiliated with Cygames. It never plays the game for you and never touches your account server-side. © Rem and Ruru — all rights reserved.*
