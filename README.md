<div align="center">

<img src="icarus.png" alt="Icarus" width="120" />

# Overseer

### Play it in your language. Skip what you've seen. Know what happens *before* you click.

**The companion overlay that turns Umamusume: Pretty Derby into the game you always wanted it to be.** It translates the game from the inside, gives you back the hours you spend watching the same animations, and reads every turn, every event and every race before you commit. One file, zero setup, everything on your PC, on the Global and the Japanese client alike.

[![Download](https://img.shields.io/badge/Download-Overseer.exe-D4A017?style=for-the-badge)](https://github.com/Remezzo/Umamusume-Overseer/releases/latest)
&nbsp;
[![Discord](https://img.shields.io/badge/Discord-Join_the_Icarus_hub-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/wpbd3hTBDc)

![Platform](https://img.shields.io/badge/platform-Windows-0078D6)
![Version](https://img.shields.io/badge/release-1.1.2-D4A017)
![Clients](https://img.shields.io/badge/clients-Global_%2B_Japanese-1f7a4d)
![Languages](https://img.shields.io/badge/languages-12_built_in-1f7a4d)
![License](https://img.shields.io/badge/license-Proprietary-c02626)

[What's new in 1.1.2](CHANGELOG.md) 

</div>

---

> **Download `Overseer.exe` → double-click → play.** It finds your game on any Steam drive, installs itself, opens its control panel and keeps itself up to date. No Python, no extracting, no folders to copy, no guide to follow. If you can double-click, you're done.

**Overseer is advice-first.** It reads what the game already knows and puts it in front of you in time; every decision stays yours. The handful of features that can press a button for you are **off until you switch them on**, and each one says exactly what it does.

---

## Contents

[At a glance](#at-a-glance) · [Translation](#translation-that-reads-like-the-game) · [Gamemaster](#gamemaster-know-it-before-you-click) · [Racing](#racing-the-whole-race-before-during-and-after) · [In the game itself](#in-the-game-itself-the-rail-and-the-marks) · [HyperSkip](#hyperskip-respect-for-your-time) · [Performance](#performance) · [Accessibility](#accessibility) · [Tools](#tools) · [Telemetry & data](#telemetry--your-data) · [Dashboard](#dashboard) · [Settings & the panel](#settings-and-the-panel) · [Global and JP](#global-and-jp) · [Privacy](#private-by-architecture) · [Install](#install-update-uninstall) · [Troubleshooting](#troubleshooting) · [FAQ](#faq)

---

## At a glance

| You want to… | Overseer… |
|---|---|
| **Read the game** in your language | Replaces the game's own text, inside the game, from its own text database: twelve languages ship ready to go, on Global *and* JP. |
| **Stop guessing** at events | Decodes every option's real outcome before you tap, and marks the branch that will fire right on the game's screen. |
| **Train smarter** | Scores every facility from the game's exact numbers and rings the best pick on the training screen. |
| **Win the race** | Shows each runner's chance to win, to place and to run out of stamina, before the gates open. |
| **Spend your SP well** | Prices every skill at your hint discounts and marks the best set in the game's own shop: for rating, or for seconds off a race. |
| **Plan your legacy** | Measures inheritance affinity in the game and searches your characters for the best parent rotations. |
| **Get your evenings back** | Native skips and up to 20× UI speed turn a long career into a coffee break. |
| **Know what a skill really does** | Shows the exact effect and trigger of every skill on Global, built from Global's own data. |
| **Keep your history** | Records every career, race and veteran on your PC, with dashboards, leaderboards and exports. |

---

## Translation that reads like the game

**The entire game, in your language, fully offline.** Not screenshots, not OCR, not a browser tab on your second monitor. Overseer replaces the text **inside the game**, straight from the game's own database, so every number is exact to the digit and no character's name ever comes out garbled.

### Twelve languages in the box

| | | | |
|---|---|---|---|
| English | French | Spanish | Italian |
| German | Dutch | Swedish | Indonesian |
| Malay | Filipino | Turkish | Vietnamese |

Every pack works on **both the Global and the Japanese client**. Menus, skills, events, story and live race commentary work the moment you pick one, with no internet needed. On the Japanese client the game starts **in English on a fresh install**, so you can play the version that gets new content first and read all of it.

### How it works: four layers, fastest first

1. **The pack.** A translated copy of the game's own text database: menus, skills, events, story, race commentary. It's already there when a screen opens and costs nothing to run.
2. **The glossary.** Text the game assembles as it runs (labels, counts, terms) never reaches its database, so no pack contains it. The per-language glossary covers those instantly.
3. **Already translated.** Anything translated once is remembered and shown instantly forever after, and **your own fixes always win**.
4. **The neural model** *(optional)*. Translates the rare line all three layers miss, on your PC, line by line as you play. Worth switching on for a while after a game update adds new text.

**Names are protected** in every layer. Characters, skills, races and titles stay exactly what they are, in every language.

### Machine Translation, built in

- **On-device and offline.** Two models: *Fast* (0.6 GB) or *Quality* (1.4 GB, noticeably better text).
- **One-click download.** A model you don't have has a **Download** button right under the picker, with live progress and Cancel. Files come from a pinned version on Hugging Face and are checked byte for byte before anything is replaced.
- **Light when it's off.** The model only loads while Machine Translation is on. Switch it off and its memory is freed at once.
- **A safety gate** refuses machine output that would damage a name, a number or a formatting tag; the game's own text shows instead of a broken line.

### Build Packs: 25+ more languages, made on your PC

Translate the whole game once, ahead of time, into a full pack for any of 25+ languages.

- **Build outside the game** (recommended): full speed, no effect on your frame rate, and it keeps going after you quit.
- **Or inside the game,** at the speed you choose: *Gentle*, *Background*, *Faster* or *Full speed*. It waits on hold until you pick one.
- **Stop any time; it resumes** from where it stopped.
- **After a game update,** *Translate what changed* only touches new or changed text: minutes, not hours.
- **On JP it builds from the English pack**, which is human-made, because the model translates far better out of English than out of Japanese.
- **A hand-made pack is never written over.**

### Corrections and updates

- **Fix any line permanently**, or pick one from the recently translated list.
- **Share or import a glossary** as JSON.
- **Check for pack updates** pulls only the files that changed, verifies them and swaps them in. Your corrections stay on top.

### Detailed skill descriptions *(Global)*

Turn it on and every skill description in the game becomes exact:

> **Target Speed +0.35 m/s for 5 s** when: Final corner/straight AND In trailing 60% AND Overtaking

The effect, the number, the duration and **every trigger condition**, in the format JP players already know. It's built from **Global's own skill data**, never copied from JP: 74 of Global's 726 skills have different numbers or conditions from their JP versions, and these follow Global. A patch that rebalances a skill needs no new Overseer.

*Translation → Language & Pack, or Settings → General → Interface. Shows while the game is in English, from the next game start.*

*Other tools translate a picture of the game. Overseer translates the game.*

---

## Gamemaster: know it before you click

The game has already decided what happens. Overseer reads that decision **before you commit**. Gamemaster is the page where it all comes together, one tab per moment of a career.

### This turn

**Every training facility, scored from the game's exact numbers.**

- **The full picture per facility:** stat gains, skill points, energy, the **real failure chance**, bond progress, exact **rainbow** (friendship training) detection and skill hints. A hint shows the support card that will give it and that card's whole candidate pool, with skills you already hold marked *held*.
- **The advisor's pick:** each facility is scored against stat targets specific to your trainee (scenario, distance and running style), scaled to where you are in the run and against her real stat caps. A stat that's behind pace is weighted up.
- **Failure is a hard filter, not a score.** Below 30% energy the advisor won't suggest training at all, not even Wit: the advice becomes *Rest*, and it shows the failure number it refused.
- **The pick is ringed on the game's own training screen**, with its reasoning in the panel and the rail.

**Every event choice, decoded.** What each option *really* gives you (stats, skill hints, energy, mood, conditions, hidden branches), laid out before you tap.

- **On Global** the game decides the branch before you press, so Overseer marks **the row that will fire**.
- **On JP** the server rolls the branch when you press, so every row that *could* fire is shown with how often each one does, and the floor and ceiling of what you might get.
- **Overseer never tells you which button to press.** It makes sure the press is an informed one.

### Race

The race in front of you, from the gate to the result. See [Racing](#-racing-the-whole-race-before-during-and-after).

### Career

- **Race Plan:** your trainee's objectives in order, with the one the game is asking for now marked.
- **Inheritance Sparks:** the whole end-of-career spark pool, before you pick.
- **Race History:** every race this session.

### Skill Optimizer

On the end-of-career skill screen, press **Recommend**.

- **It prices every skill at your hint discounts,** weighted for your trainee's distance and style, and finds the set that raises your **rating** most within your SP.
- **Or optimise for race time:** pick a race preset, and it buys the set that takes the most **seconds** off your finish on that course. A cheap speed skill on the last straight can beat an expensive one that fires when you're already at top speed.
- **Upgrades are priced at what they add,** so ◎ over an owned ○ costs what it really costs.
- **Each recommended row is marked in the game's own shop.** It never buys anything for you.

### Affinity

Inheritance planning from affinity **measured in the game itself**: a loop planner that searches your characters for the best legacy rotations, with data coverage shown. On Global it also shows a live readout as you pick parents on Legacy Select.

### Friendship

Your six support cards' bonds this career: who is close to a rainbow, who will get there before the run ends, and who won't. It's projected from *your* run and uses the same logic as the training advisor, so the two never disagree.

### Your scenario: Grand Live

The last tab is named after the scenario you're running.

- **On the lesson screen,** the best of the three cards is marked in the game.
- **Every song and technique ranked** by what it's worth to *this* run.
- **A pre-farm planner** that prices each song against the Performance Points you've already saved.
- **The concert schedule,** so you can see which turn each one lands on.

Training advice, event decoding, race chances, the Skill Optimizer and the in-game marks work in **every** scenario.

*Stop guessing. The data was always there. Overseer just shows it to you in time.*

---

## Racing: the whole race, before, during and after

- **Chances at the entry screen.** At the entry screen the server sends every runner's exact stats, aptitudes, mood and running style a few seconds before you have to decide. Overseer runs that field through a simulation of the game's own race physics a couple of hundred times: **win chance, top-3 chance, and how often each runner runs out of stamina before the line**. It's computed only from what is known *before* the gates open, never peeked from the result.
- **Race Field, the one race table.** Every rival's stats (on hover), the three aptitudes that matter for *this* race, mood, popularity and the simulated chances, with your row lit. After the race it becomes the finishing order, place and margin first, with the chances still beside them, so you can see who beat the odds.
- **Live race.** The game's own simulation read frame by frame while the race plays: positions, gaps, speed and stamina for every runner.
- **Race Forecast.** The finishing order, decoded from the game's own race data the moment the race loads, so you know the result before you watch it.
- **Race replays.** Every race saved as a file a race-replay viewer opens, for running lines, margins and which skills each runner activated. Player ids are stripped first.
- **Team Trials.** The Opponent Hunter finds the trainers you want to race, and every Team Trials result can be exported with each runner's skills, sparks and parents.

---

## In the game itself: the rail and the marks

**The live rail** is the right-hand column of the panel, and it follows you across every page: this turn's advice, every event option and what it pays, the race forecast, the Grand Live pick, energy and stats. **Pop out** puts it in its own window beside a fullscreen game.

**On the game's own screens**, Overseer draws in five places:

1. **A ✓ and an outline** on the event branch that will fire.
2. **The recommended Grand Live lesson card.**
3. **Each skill row** the Skill Optimizer says to buy.
4. **A ring on the training facility** the advisor picks this turn.
5. **An optional FPS counter.**

All the marks are **one switch and one colour** under *Settings → General → Overlay*. Turn it off and every mark disappears at once.

---

## HyperSkip: respect for your time

You've watched that training cut-in four hundred times. Overseer gives you the hours back.

**Auto-skip**, driven by the game's **own** skip and fast-forward routines, so it's instant and never desyncs the screen:
- Training · Events · Shop · Rival · Race result (only when you've won)

**Auto-options**, each its own switch, each **off by default**:
- Event choice → top option · Confirm warnings (consecutive races and the like) · Inspiration · Skill learning · Grand Live song confirm

**Race Fast-Forward** speeds up races automatically, and only when you've won. Lose, or an unclear result, and it stops and hands the controls back.

**UI Speed** runs menus, transitions and event text at up to **20×**, at whatever pace you can read.

A guard steps back the moment a skip doesn't land, so the screen always stays yours, and a career that took an evening takes a coffee break.

---

## Performance

- **Low Resource Mode** runs the game smoothly on modest hardware, in tiers you choose.
- **Frame rate:** cap it anywhere from 1 to 300 or run it unlimited, with an optional in-game FPS counter.
- **Graphics:** force maximum 3D model quality, and set anti-aliasing, shadows and shadow distance yourself.
- **Display & Window:** keep the game always on top, or block it from minimising.

---

## Accessibility

- **Colour-vision modes** for the panel, plus an **in-game filter** with adjustable strength, with a live preview.
- **Reduce motion** and **high contrast.**
- **Interface text size** you can scale.

---

## Tools

### Deck Builder
Build and analyse support decks from **your client's own database**.
- **Owned** shows your real collection at its real levels; **All cards** lets you theorycraft anything.
- **Set each card's limit break**, and its level follows.
- **Effects Breakdown, Skills, Skill Analysis and Training Analysis** update as you edit, including rainbow chance per training and stat gains per turn.
- **Save a deck as a profile** and load it back in one click.

### Rating Calculator
Type any stat line, unique skill level and skill set, and see the **rating**, the **rank** it lands on and **how far the next rank is**, from the rank table your own client ships. Global and JP rank tables differ above UG1, and JP has two hundred tiers Global has never seen, so Overseer always reads yours.

### Opponent Hunter *(off until you start it)*
Rolls the Team Trials opponent list until a target trainer appears (by name or UID, several at once), then stops and alerts you with a Windows notification and, optionally, a webhook ping to your phone. It uses the game's own button at a human pace.

### Room Finder *(off until you start it)*
Refreshes Room Match until a room you named appears (by room name, id or host), then stops and raises a Windows notification. About one refresh every three seconds, slowing down and then stopping if the game stops answering. **It never joins for you.**

### Un-Follower *(Global, off until you start it)*
Trims your oldest inactive followers when the list nears the 1,000 cap, through the game's own remove flow. You preview every name first, a whitelist always wins, and it stops itself on anything unexpected.

---

## Telemetry & your data

Telemetry has its own page, with every export beside it.

### Career telemetry *(on by default, never uploaded)*

A turn-by-turn record of every career, on your PC:
- **What was on offer** each turn: every facility, the races you could enter, the skill shop as it stood.
- **What you chose and what happened**: gains, events and their outcomes, races and results, skills bought.
- **The context:** your deck, your parents' and grandparents' sparks and affinity from turn 1, and **the score the run would end on** at every step.

It's never trimmed, rotated or capped. It never contains your account, trainer identity or any game API data. **Prepare a file to send** bundles this session, the last one, your complete runs or everything into one compressed file, to share in the Discord and help improve the advice everyone gets.

### Data Export *(each off until you turn it on)*

- **Races:** every race as a replay file the race viewers open, grouped by race type.
- **Team Trials:** every result with each runner's real trained uma: skills, sparks and parents.
- **Veterans:** your full trained roster, which also powers the Dashboard's Veterans.
- **Files & retention:** every folder with its size, and **Open file location** on every tab. Keep everything (the default), or the newest 100/250/500/1000 races per race type. Nothing is deleted unless you choose a limit.

---

## Dashboard

- **Overview:** the career you're running (turn and date, stats against their caps, the advisor's scores, decisions, races, skills bought), this session, your career stats, recent activity and what happens next.
- **History:** sessions, run history, an all-time leaderboard, records and a Hall of Fame.
- **Trends:** charts and summary cards across your finished careers.
- **Veterans:** every trained horsegirl with her sparks and her parents'.
  - A summary band: veterans, locked, best grade, average score, best spark pool, scenarios.
  - Filters for grade, scenario, aptitude, style and lock.
  - **Star-count spark filters that work in any pack language.**
  - Side-by-side **Compare** for up to four, with the best value in each row lit.
  - Your favourites from the game starred, and **CSV export** of the current view.
- **Roster:** every trainee your account can run, how many careers each has had, and how far her permanent **Bond** has come, straight from the game. Search it, filter to the ones you've never run, sort by bond.

---

## Settings and the panel

The control panel lives at `127.0.0.1:1620` and opens for you when the game starts. A three-question **first-run setup** gets you going, and everything it sets stays in Settings.

**Settings → General**, in five sections:
- **Interface:** the panel's own language (**English, French, German or Spanish**), auto-open, streamer mode, detailed skill descriptions.
- **Overlay:** the one switch and colour for every mark Overseer draws in the game.
- **Discord:** optional **rich presence** showing the scenario, the in-game date and who you're raising. Never your trainer name, UID or anything that identifies you.
- **System:** a master switch for every subsystem (the quickest way to find out whether Overseer is involved in something), plus health, memory and the translation model.
- **Maintenance:** diagnostics and uninstall.

**Settings → Shortcuts.** Every page and the search have keyboard shortcuts you can change. A key the browser would grab first is refused, and it tells you which. **Ctrl+K** (or **/**) searches every page, tab and setting by name.

**Settings → Webhooks.**
- **What posts:** a career finished, an opponent found, a room found.
- **What a post carries:** the sections you choose, delivery attempts and tags.
- **Where it goes:** as many endpoints as you like. Discord URLs get a rich embed; anything else gets a clean JSON envelope.
- **Saved URLs are hidden** in the panel and never shown again.

**Streamer mode** masks account identities wherever the panel shows one: UIDs become dots, names keep their first letter.

**Logs** has Decision Reasoning, Player Actions and the Console, plus **Export**: one file with everything a bug report needs.

**Catalogue** shows the rest of the Icarus family and which client each tool supports.

**Help** matches this build line for line: every feature explained, guides for the tricky parts (training calls, event branches, friendship, rating vs race time, Grand Live, the Deck Builder, building a pack, your files) and troubleshooting.

---

## Global and JP

**One build runs on both.** Overseer works out which client it's attached to on its own, and the panel hides whatever doesn't apply.

| | Global | Japanese |
|---|:---:|:---:|
| Training advice, event decoding, race chances | Yes | Yes |
| Skill Optimizer, Grand Live, in-game marks | Yes | Yes |
| HyperSkip, Performance, Deck Builder, webhooks | Yes | Yes |
| Twelve translation packs | Yes | Yes |
| Starts in English out of the box | (already English) | Yes |
| Detailed skill descriptions | Yes | (the English pack has its own) |
| Live Legacy Select affinity readout | Yes | — |
| Un-Follower | Yes | — |

**The Japanese client needs a launcher**, and Overseer sets it up for you. The JP client checks its own folder at startup and refuses to run if it finds a mod, so Overseer installs a small launcher and points Steam's launch options at it. It steps Overseer aside for that check and puts it back as the game loads. You press Play as normal and never see it.

**Everything is read from the database *your* client installed.** A game patch that adds or rebalances something needs no new Overseer to stay accurate.

---

## Private by architecture

- **Everything runs on your PC.** The panel only listens on your own machine.
- **Translation is on-device.** The only download is the optional model, and only when you ask for it.
- **Your data never leaves your computer** unless you choose to send a file. Telemetry never contains your account, trainer identity or any game API data, and exported files have player ids stripped.
- **Overseer never touches your account server-side.** It's an unofficial companion that improves what *you* see and do, not a bot playing in your place.

**Light on your PC, too.** Overseer's own work per frame is measured in fractions of a millisecond, settings save without making the game wait for the disk, and closed panel pages stop polling. The optional translation model is the only heavy part, and it only loads while you have Machine Translation on.

---

## Install, update, uninstall

1. **[Download `Overseer.exe`](../../releases/latest).** One file, everything bundled.
2. **Double-click it.** Windows SmartScreen? *More info → Run anyway.* If your antivirus flags the overlay loader, that's a known false positive: allow-list the game folder.
3. **That's it.** The game launches, the panel opens, and every feature above is a switch away. On the Japanese client, Overseer sets up its own launcher.

**Updates install themselves**, checked against the release's published hash, and translation packs update separately through *Check for pack updates*.

**Already using another tool that hooks the same file?** The installer says so, moves it safely aside with a backup, and never touches a setup it doesn't recognise.

**Uninstalling puts the game back exactly as it was.** Use *Settings → General → Maintenance*, or `Overseer-Uninstall.exe` from the release page if Overseer itself won't start. Your career telemetry is kept unless you ask for it to go.

**Requirements:** Windows 10/11 · Umamusume: Pretty Derby on Steam (Global or Japanese) · windowed or borderless mode. No runtimes, no dev tools, and no internet needed for the built-in languages.

---

## Troubleshooting

- **The game won't launch.** Close any other mod or tool that injects into the game. Deleting `cri_mana_vpx.dll` from the game root alone puts the game back to vanilla. Never touch the file inside `Plugins\x86_64`: that one is the game's.
- **The panel won't load.** The game has to be running: the panel at `127.0.0.1:1620` is served only while the game is open.
- **JP shows "Communication error" (Code 102).** That's the game losing its connection to Cygames, most often through a VPN whose address is blocked. Try a different Japan server and press Retry. Overseer doesn't touch the game's network.
- **A translation looks wrong.** Correct any line under *Translation → Corrections*, or run *Check for pack updates*.
- **A panel says a screen isn't open.** Some tools read a screen only while you're on it (Followers, Select Opponent, Room Match). Open the screen and the panel fills.
- **Veterans is empty.** Turn on *Telemetry → Veterans*, then open your Trained Uma list in the game once.
- **Something else?** *Logs → Export* saves one file with everything we need. Bring it to the [Discord](https://discord.gg/wpbd3hTBDc).

---

## FAQ

**Does it play the game for me?** No. Overseer shows you information and speeds up what you've already seen. The few optional automations (auto-options, Opponent Hunter, Room Finder, Un-Follower) are off by default and only do exactly what their switch says.

**Does it tell me which option to pick?** For training it gives a recommendation with its reasoning. For events it shows what every option does and which branch will fire, and leaves the choice to you.

**Global or Japanese?** Both, from the same download, with the same features apart from the few in the table above.

**Will it slow my game down?** No: its own per-frame cost is a fraction of a millisecond. If you're short on RAM, leave Machine Translation off; the packs translate the game without it.

**Do I need the translation model?** No. The twelve packs, the glossary and your corrections all work without it. The model only matters for building new packs or catching the rare untranslated line.

**Where's my data?** Beside the game, in `UmamusumePrettyDerby_Data\Plugins\x86_64`. *Telemetry → Files & retention* shows every folder and its size. Note that uninstalling the *game* through Steam removes that folder too, so copy anything you want to keep first.

**Is my account safe to show on stream?** Switch on streamer mode, and Discord rich presence never carries your identity in the first place.

**How do I get help?** *Help* inside the panel covers every feature, and the [Discord](https://discord.gg/wpbd3hTBDc) is where we answer questions and take bug reports.

---

<div align="center">

### Part of Icarus

Every tool speaks the game's own API. The same protocol work sits underneath each one; each does a different job on top.
**Icarus** (career automation) · **Sundial** (multi-account manager) · **Fortuna** (account reroller) · **Un-Follower** (follower cleanup) · **Overseer** (this) · **Navigator** (protocol research)

[**Join the community on Discord →**](https://discord.gg/wpbd3hTBDc)

<sub>Overseer is proprietary, closed-source software — see [LICENSE](LICENSE). Redistribution, modification, and reverse engineering are not permitted. Not affiliated with, endorsed by, or sponsored by Cygames, Inc. All rights reserved © 2026 Remezzo / Icarus.</sub>

</div>


