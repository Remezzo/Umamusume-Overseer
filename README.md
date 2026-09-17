<div align="center">

<img src="web/overseer.png" alt="Overseer" width="120" />

# Overseer

### The most complete companion for Umamusume — and the only viable app for both Global and JP. 

**Overseer is the most feature-complete companion overlay for Umamusume: Pretty Derby, and the only one viable one across both the Global and Japanese clients — same build, same installer, same features on each.** It translates the entire game into your language, shows you every event outcome before you commit to it, prices every training with the game's own numbers, forecasts your races from the server's own simulation, spends your skill points for you to approve, and skips everything you have already seen.

Other tools cover one client, or one job. Overseer is the one you install once and keep, whichever client you play — and it never plays the game for you.

[![Download](https://img.shields.io/badge/Download-Overseer.exe-2E7D46?style=for-the-badge)](https://github.com/Remezzo/Umamusume-Overseer/releases/latest)
&nbsp;
[![Discord](https://img.shields.io/badge/Discord-Join_the_Icarus_hub-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/wpbd3hTBDc)

![Platform](https://img.shields.io/badge/platform-Windows-0078D6)
![Release](https://img.shields.io/badge/release-1.1.0-2E7D46)
![Clients](https://img.shields.io/badge/clients-Global_%2B_Japan-6a4ea1)
![Languages](https://img.shields.io/badge/languages-26-8a5cf5)
![Runs locally](https://img.shields.io/badge/runs-100%25_on_your_PC-1f7a4d)
![License](https://img.shields.io/badge/license-Proprietary-c02626)

</div>

---

## The game does not tell you anything

You pick a training. You do not know what it gives you until it is given. An event fires with three
options and no indication which one matters; the wiki tab you keep open has the answer, if you can
find the event, in the language you read, before the mood wears off. You enter a race with no idea
whether you can win it. You spend skill points on a hunch.

None of that is difficulty. **The numbers exist.** The game's own servers send them to your client
every single turn — the exact stat gains for every facility, the real failure percentage, the full
outcome table for the event on screen, a complete simulation of the race about to run. The client
receives all of it and shows you almost none of it.

**Overseer puts them on screen.** It reads what the game already knows, in the moment it knows it,
and shows you the answer where you are looking. Then it skips the parts you have watched two
hundred times.

That is why there is no partial version of this that would do. A translator that cannot read the
event table cannot tell you what a choice does. A predictor that cannot render Japanese cannot help
on the client that needs it most. A skip that does not know whether you won cannot know what is safe
to skip. Overseer is built as one thing because the pieces are only useful together.

---

## One tool, both clients

Most people who play this game seriously end up touching both clients — Japan for what is out now,
Global for the account they have actually invested in. Companion tools exist for each. **What does
not otherwise exist is one tool that covers both.**

Overseer is the same binary on Global and Japan, from the same installer, with the same features on
each. Run both clients at once and each gets its own panel. You learn it once, you configure it
once, and what you know transfers.

That includes the vocabulary. Japan now uses **Global's own terminology** — Front Runner, Pace
Chaser, Late Surger, End Closer — across skills, aptitudes, missions and the race screen, so a
guide, a screenshot or a piece of advice written for one client reads correctly on the other. That
is 1,349 strings, and the skill names were taken by id from Global's own table rather than
word-swapped, so "Frantic Leaders" is "Frenzied Pace Chasers" the way Global actually writes it.

Where the two clients genuinely differ, Overseer handles the difference instead of pretending it is
not there. Japan's server does not pre-roll event branches the way Global's does, so on Japan those
are shown as an honest range rather than a false certainty.

---

## Know it before you click

Overseer watches the career loop and answers the question you are actually asking at each step:

```
   YOUR TURN
      |
      +-- The training board  ->  every facility's real gains, its failure chance,
      |                           who is on it, and which one actually scores best
      |
      +-- An event fires      ->  every outcome of every option, side by side,
      |                           and the winning branch marked IN THE GAME
      |
      +-- Race day            ->  where you will finish, from the server's own
      |                           simulation of the race, before it runs
      |
      +-- Skill points        ->  the exact buy list that adds the most rating,
      |                           highlighted on the shop rows themselves
      |
      +-- Inheritance         ->  the game's own affinity number for the pair
      |                           you are hovering, live, with the tray ranked
      |
      +-- Everything seen     ->  skipped
```

### Training predictions are the game's own numbers, not a model

When the server prices this turn's board, Overseer reads the prices. You get one row per facility
showing the **exact** stat gains, skill points, energy cost and **real failure percentage** — the
same figures the game is working from, not an estimate of them.

Beside each row is a score, and the score is explained rather than asserted. It accounts for your
current stats against your caps, how far ahead or behind the scenario's pace you are, which support
partners are on the tile, their bond, rainbow status, and whether a hint you want is attached. A
facility that looks strong but dumps points into a stat you have already capped scores lower, and
the panel tells you that is why.

### Event outcomes appear before you choose, not after

Every option, with every branch it can take, in full — stats, skill points, energy, mood, bond,
skills granted, and the conditions attached.

Where the server has already rolled which branch will fire and tells the client, **Overseer marks
that row in the game itself** — a tick on the actual choice button, so you never look away to a
second monitor. Where the server genuinely has not decided, Overseer says so and gives you the range
rather than inventing a certainty. That distinction is enforced in the code: an unknowable branch is
marked *not at all*, rather than marking every candidate and hoping.

Optional auto-choice will take the best option for you when you would rather not click.

### The race forecast comes from the race

Not from ratings, not from a heuristic. The game sends your client a full simulation of the race —
every horse, its position at every moment, the finishing order — and Overseer decodes it and tells
you where you will place **before the gate opens**. Scenario races where every horse is anonymous
are handled too, by identifying your trainee from her own character rather than an id the server
withheld.

### The Skill Optimizer spends your points for you to approve

It reads the shop the game is actually selling — including inherited skills, uniques and unhinted
whites that a reconstruction from static data structurally cannot see — and solves for the buy list
that adds the most rating within the SP you have.

Then it **outlines those rows on the skill screen itself**, so you can buy what is glowing and close
the panel. It recomputes as you pick, and never double-counts something you already selected by
hand.

### The Live Advisor is a coach, not a cheerleader

One recommendation per turn with the reasoning that beat the alternatives, measured against real
stat targets for the scenario you are in, and an honest read on whether you are ahead or behind
pace. When it is working from a stand-in — a scenario it has no profile for — it says so rather than
presenting a guess as gospel.

---

## Getting onto the Japanese client without touching the game

The Japanese client wraps its executable in commercial anti-tamper. At startup it scans the game
folder and refuses to launch if anything there is not stock. It is a real wall, and the usual way
through it is to let a tool replace the game's executable with a patched one.

**Overseer replaces nothing and injects nothing.**

Instead of touching the game, a small launcher works alongside it from the outside. It wires into
Steam's Launch Options, the genuine unmodified game starts through Steam exactly as it always does —
authentication and all — and Overseer ends up loaded the same way the game loads any of its own
libraries. Nothing is patched, nothing is hooked, and nothing of Overseer's runs inside the game
process for the anti-tamper to find.

Because the game's own files are never altered, a game patch has nothing of ours to overwrite: the
same install keeps working across updates, with no reinstall and no waiting for a fix.

The installer sets all of this up for you, including the Steam Launch Option. You never need to know
any of it is there.


---

## The entire game, in your language

Overseer ships a complete English translation for the Japanese client and supports **26 languages**
through community packs: UI, menus, skills and their descriptions, events, story, home dialogue,
missions, and race commentary.

- **It reads like the game, not like a machine.** Character names, support card titles and skill
  names are protected from translation, so nobody is "Special Week" on one screen and something else
  on the next. Strings the game assembles from parts — "Speed went up by 12" — are handled by rules
  rather than fed through a translator a fragment at a time and returned as nonsense.

- **Text fits its box.** English is wider than the Japanese it replaces, and the game's older text
  components clip rather than wrap. Overseer wraps long lines on real measured widths, and shrinks
  labels that still will not fit to a floor that stays legible instead of letting them truncate
  mid-word.

- **Optional on-device neural translation** fills anything a pack misses, running entirely on your
  machine with no service and no API key. It is **off by default**, because packs are faster and
  read better; turn it on only if you want coverage more than frame rate.

- **Image and texture translation** for the art with text baked into it.

- **You can fix anything yourself.** Any line can be overridden by hand in the panel, exported, and
  shared as a pack. Packs built on one client work on the other.

---

## What you get that a translation layer does not

If all you want is the Japanese client in English, dedicated translation tools exist and they are
reasonable at that one job. The difference is worth stating plainly, because it is not a matter of
degree:

| | A translation-only tool | Overseer |
|---|---|---|
| **Scope** | Translates text | Translates text, **and** prices every training, reveals every event outcome, forecasts races, optimises skills, ranks inheritance, and skips what you have seen |
| **Clients** | One | Global and Japan, same build, same installer |
| **Getting onto Japan** | Typically replaces the game's executable | Leaves the game untouched; a launcher steps aside during the startup scan |
| **After a game patch** | A replaced executable is overwritten — reinstall, or wait for an update | Nothing was replaced, so nothing breaks |
| **Setup** | Edit configuration files | Double-click one exe; it finds every client you have and sets each one up |
| **Day-to-day control** | Config files, then restart | A live dashboard with a switch for everything, no restart |
| **Removing it** | Put the executable back yourself | An uninstall button, plus a separate rescue uninstaller that works even if Overseer does not |
| **If both are installed** | — | Overseer detects the conflict, moves the other tool aside into a dated backup outside the game folder, tells you exactly where it went, and deletes nothing |

The honest summary: one of them is a translation layer. Overseer is a companion that happens to
include a very good one.

---

## HyperSkip — the parts you have seen two hundred times

Every one of these is an individual switch, so you keep whatever you still enjoy:

- **Event scenes** — straight to the outcome
- **Training cut-ins** — the animation between you and your stats
- **Race results** — the whole post-race sequence, including the walk back
- **Skill learning** — the purchase flow
- **The shop** — exchange and purchase confirmations
- **Inspiration scenes**
- **Rival scenes**
- **Warning and confirmation dialogs** — the ones you always answer the same way
- **Grand Live song confirmation**
- **Race fast-forward** — for the races you do want to watch, just faster

Skips are written to understand what is happening rather than to mash buttons. The race-result skip
knows whether you actually won, and stands down rather than clicking through something that matters.

---

## Everything else in the box

| | |
|---|---|
| **Gamemaster** | One page for this turn, the race, the career, the Skill Optimizer, affinity and Grand Live — everything the current moment needs. |
| **Grand Live** | Song offers decoded and scored, performance points and progress tracked, and the pick you want marked on the card in-game. |
| **Legacy / inheritance** | The game's own affinity number for the pair you are hovering, live as you change the selection, with the whole candidate tray ranked. |
| **Deck Builder** | Score a support deck against your own collection before you commit a career to it. |
| **Opponent Hunter** | Team Trials: name the opponents worth beating and Overseer rerolls until one appears, reading the offer from the server rather than guessing at memory. |
| **Un-Follower** | Prune inactive followers through the game's own request path, with a full preview of who goes before anything happens. |
| **Career telemetry** | Optional, off by default, nothing uploaded. One plain JSON file per career: every turn's stats, energy and mood, the options the game offered with its own numbers and failure chances, what you chose, what it gained, and the final grade. Your own record of how you actually play. |
| **Race exports** | Every race written out with the full field, times and result, into a folder that can tidy up after itself. |
| **Discord webhooks** | A career-completion report with the trainee's art and your deck strip, plus an optional ping when the Opponent Hunter finds a target. One clean message per career, not a firehose. |
| **Dashboard** | Everything above at `127.0.0.1:1620`, in a panel designed to stay out of your way. Search jumps to any page, setting or tool. |
| **Performance** | FPS unlock, render scale, graphics and display options, and a UI speed multiplier, for people who would rather spend the frames elsewhere. |
| **Accessibility** | Colour-vision-safe palettes, adjustable text scaling, and a panel that answers the keyboard. |
| **Master switches** | One toggle per subsystem — translation, analysis, skips, overlay, exports, webhooks, performance, advisor. Turning one off stops that whole side of Overseer, which is the fastest way to answer "is Overseer involved in this?" |
| **Logs** | What Overseer did and why, in plain language, with a live console when you want it. |

---

## Quick start

> **Download, double-click, play.** No Python, no Node, no extracting, no instructions.

1. **Grab [`Overseer.exe`](https://github.com/Remezzo/Umamusume-Overseer/releases/latest)** and put it anywhere.
2. **Double-click it.** It finds your game on any Steam drive — Global, Japanese, or both — installs
   itself into each one it finds, and sets up the Japanese launcher if you have that client.
3. **Start the game.** The dashboard opens at **`http://127.0.0.1:1620`**.
4. **Pick your language** under Translation, and turn on the skips you want under HyperSkip.
5. **Play.** Overseer fills in as you go.

Closing the panel tab changes nothing — reopen `127.0.0.1:1620` whenever you like. Running both
clients at once is fine; the second takes the next free port and opens its own panel.

**Requirements:** Windows 10/11 and Umamusume on Steam. That is the entire list.

**Already on 1.0 or 1.0.1?** Download and run `Overseer.exe` once. It updates you in place and
migrates the older install layout; every update after that arrives in the panel itself.

---

## Built to be trusted

Overseer is a finished product rather than a script dump, and it is unusually specific about what it
does to your machine:

- **It runs entirely on your PC.** Nothing is uploaded, ever. The only things Overseer sends
  anywhere are the Discord webhook you configure yourself and its own update check.
- **The dashboard is loopback-only** and refuses any request that did not come from its own page, so
  nothing else on your machine and nothing on the web can drive it.
- **Telemetry is off until you switch it on**, and even then contains nothing about you — no
  account, no trainer identity, and no game API data of any kind. It is plain JSON; open it and read
  it.
- **The game's own files are never modified.** Overseer installs beside them, and the audio codec it
  forwards to is left byte-for-byte untouched — verified end to end on a clean install.
- **If another tool already holds the slot Overseer needs**, it says so, moves that tool aside into a
  dated backup folder outside the game directory, prints exactly where it went, and deletes nothing.
- **A failing feature degrades instead of taking the game down.** Every hook runs inside a guard, so
  a fault costs you that one feature and nothing else. Genuine memory faults are deliberately not
  swallowed — a corrupted process is never quietly continued.
- **There is a rescue uninstaller.** A separate download that removes Overseer 1.0, 1.0.1 or 1.1 and
  restores the game to stock — and does not need Overseer to be working to do it.
- **It profiles its own cost and shows you the numbers.** Across a full career the overlay's
  per-frame work averages 0.0 ms over 730,000 samples, with 99th-percentile frame gaps of 8 ms.
  **Settings → Diagnostics** writes the same report for your machine, so "is this slowing my game
  down?" is a question you can answer yourself instead of taking our word for it.

---

## Part of the Icarus Suite

Overseer is one tool in a family of Umamusume utilities by **Icarus Network**. Join the hub for
releases, help, and the wider toolset:

<div align="center">

### [→ discord.gg/wpbd3hTBDc](https://discord.gg/wpbd3hTBDc)

</div>

---

## FAQ

**Does it play the game for me?**
No. Overseer is a companion — it reads what the game is doing and shows you what it knows. Every
decision stays yours. The two features that do act on their own, the Opponent Hunter's reroll and
the follower pruner, are off by default and show you what they will do before they do it.

**Is this safe for my account?**
Any third-party tool that attaches to the game carries inherent risk, and nothing anyone tells you
makes that risk zero. Overseer does not automate play, does not touch the server, and does not send
your data anywhere — but it is still a modification, and using it is at your own risk.

**I already use something on Japan. Why switch?**
If you only want Japanese text in English and you only play Japan, you may not need to. The case for
Overseer is that it is one tool for both clients, it does far more than translate, and it gets onto
Japan without replacing the game's executable — so a game patch does not send you back to the
download page.

**Will it slow my game down?**
It has not in measurement, and you do not have to take that on faith — Settings → Diagnostics
produces the same profile on your hardware. If you want every frame back, the neural translator is
off by default for exactly that reason, and every subsystem has its own switch.

**Does the game need to be open?**
Yes, for anything that reads the game. Overseer lives inside it, and the dashboard is a window onto
what it is seeing. The Deck Builder, your exports and your telemetry keep working with the game
closed.

**Can I run Global and Japan at the same time?**
Yes. Each gets its own panel on its own port, and both run the same build.

**I have another tool installed already.**
Only one thing can hold the file both tools need. Overseer notices, moves the other one aside into a
dated backup outside the game folder, and tells you where it went — nothing is deleted, and you can
put it back whenever you like.

**Windows Defender flagged it.**
Overseer installs a proxy library next to the game, which is exactly the shape heuristics look for.
The installer offers to add a folder exclusion and prints the command to add or remove it yourself.
It is announced, never silent.

**How do I remove it?**
Either the uninstall button in the panel, or the separate `Overseer-Uninstall.exe` from the releases
page, which works even when Overseer does not. Both restore the game to stock. Your telemetry and
settings are kept unless you ask for them to go.

**Where does my data live?**
Beside the game, in the folder Overseer installs into. Back that folder up and you have backed up
everything. Note that uninstalling the game through Steam takes that folder with it.

**Can I contribute a translation?**
Yes — any line can be overridden in the panel, and packs export and import. Come to the Discord.

---

## Disclaimer & license

Overseer is an independent, unofficial tool. It is **not affiliated with, endorsed by, or sponsored
by Cygames, Inc.** "Umamusume: Pretty Derby" and all related names and marks are the property of
their respective owners.

Overseer is **proprietary software** — see [LICENSE](LICENSE). You may download and run the official
build for personal use; you may **not** copy, modify, redistribute, or reuse it or its code. All
rights reserved © 2026 Remezzo / Icarus Network.

