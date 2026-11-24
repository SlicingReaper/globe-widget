# ◍ GLOBE//GUESS — find the mystery country

![macOS](https://img.shields.io/badge/macOS-Übersicht-3ef0ff?style=flat-square&logo=apple&logoColor=white&labelColor=040914) ![Vibecoded](https://img.shields.io/badge/vibecoded-with%20Claude-ff5ad9?style=flat-square&labelColor=040914)


| File | What |
|:--|:--|
| `globe.jsx` | The whole game, including the map: 198 countries from Natural Earth 1:50m (public domain), simplified, with border distances pre-computed |

## Play

| Input | Action |
|:--|:--|
| type + ⏎ | guess the highlighted country |
| Tab · ↑ ↓ | complete · pick a suggestion |
| drag · scroll on the globe | spin · zoom |
| click a guess | fly the globe to it |
| ∞ NEW | practice round: random country, doesn't touch your stats |
| ? GIVE UP | reveal the answer (appears after 3 guesses) |

**Daily country:** the same all day, changes at local midnight, and repeats none of the 198 until the cycle is done. Common names work too: *USA*, *UK*, *Ivory Coast*, *Czech Republic*, *Burma*…

**Saved in** `~/Library/Application Support/STUDYTERM/globe.json`: today's guesses (so a reload doesn't lose them), streak, wins and games played.

## 🚀 Install

1. Download this repo (green **Code** button → *Download ZIP*) and double-click **`install.command`**. The first time, macOS may block it: right-click → *Open*.
   It installs [Übersicht](https://tracesof.net/uebersicht/) if you don't have it and copies `globe.jsx` into its widgets folder.
2. Click the input field to play. If clicks fall through to the desktop: Übersicht menu-bar icon → this widget → turn on interaction.

- **Needs:** macOS 13+ · nothing else
- **By hand:** copy `globe.jsx` into Übersicht's widgets folder (menu-bar icon → *Open Widgets Folder*).
- **Remove:** delete `globe.jsx` from the widgets folder.

## 🎨 Look and position

Out of the box it sits in its default spot in the cyan terminal theme. The heat colours stay fixed, since they carry the game. Install [**WIDGET//CTL**](https://github.com/SlicingReaper/widgetctl) to drag it anywhere on a grid, pick from 16 colour schemes × 8 styles, and get `⌃⌥⌘W`, which hides all widgets at once.

## 🧩 Part of a collection

This widget is one of fifteen that share the same retro-terminal look, the same theming and the same show/hide hotkey. Each works on its own; together they make a desktop dashboard.

| | Widget | What |
|:-:|:--|:--|
| 💰 | [**WALLET//Ð**](https://github.com/SlicingReaper/points-wallet-widget) | Points wallet: earn for habits, spend on rewards, lock savings, keep a streak |
| 🔥 | [**75//HARD**](https://github.com/SlicingReaper/75-hard-widget) | 75 Hard challenge tracker: 7 daily tasks, day counter, auto-fail on a missed day |
| ⏱️ | [**STUDY//TERM**](https://github.com/SlicingReaper/study-timer-widget) | Study stopwatch that logs what you did, with a stats page and points |
| ✎ | [**NOTE//PAD**](https://github.com/SlicingReaper/notepad-widget) | Checklist notes with deadline countdowns, auto-expiry and a bin |
| “ | [**QUOTE//DAY**](https://github.com/SlicingReaper/quote-of-the-day-widget) | A new quote every midnight from a pool of 300, with likes and your own quotes |
| ▦ | [**TETRIS//GRID**](https://github.com/SlicingReaper/tetris-widget) | Tetris on the desktop: hold, ghost piece, levels, best score |
| ◉ | [**PONG//SOLO**](https://github.com/SlicingReaper/pong-widget) | Single-player Pong: keep the ball up, it speeds up every hit |
| ◎ | [**PONG//DUO**](https://github.com/SlicingReaper/pong-duo-widget) | Two-player Pong, 3 widgets wide: W/S vs ↑/↓, first to 7 |
| ⊞ | [**2048//TILE**](https://github.com/SlicingReaper/2048-widget) | 2048 with undo, keyboard or drag, saved between sessions |
| ⌂ | [**OUTPOST//**](https://github.com/SlicingReaper/outpost-colony-widget) | Colony-trading game: claim land, outfit robots, trade against 3 AI rivals |
| ☠ | [**DOOM//TERM**](https://github.com/SlicingReaper/doom-widget) | DOOM shareware Episode 1 in a 2-column widget: WebAssembly engine, savegames kept |
| ◍ | [**GLOBE//GUESS**](https://github.com/SlicingReaper/globe-widget) ← you are here | Daily mystery country on a spinning globe: every guess glows hotter the closer it is |
| ◍ | [**ATLAS//QUIZ**](https://github.com/SlicingReaper/atlas-quiz-widget) | Sporcle-style map quiz: type a name, the country lights up green. World, continents, US states |
| W | [**WORDLE//**](https://github.com/SlicingReaper/wordle-widget) | The daily five-letter word game: six tries, streaks, guess distribution, unlimited practice |
| 🎛️ | [**WIDGET//CTL**](https://github.com/SlicingReaper/widgetctl) | Menu-bar app that arranges and themes all the widgets, plus a ⌃⌥⌘W show/hide hotkey |

**Install all of them at once:** [`vibecoded` → install-all.command](https://github.com/SlicingReaper/vibecoded) · 🤖 Vibecoded with [Claude](https://claude.ai): I designed, directed and tested it, the AI wrote most of the code.
