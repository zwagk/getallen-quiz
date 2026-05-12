# Getallen - Dutch Number Quiz

A browser-based Dutch number learning game. A number appears — you type the Dutch translation. Three modes, configurable timer, accent strictness toggle, and a dark mode.

**[▶ Play it live](https://zwagk.github.io/getallen-quiz)**

---

## How to play

1. Pick a range: **1-10**, **1-50**, or **1-100**
2. Set a time limit (No limit, 1 min, 5 min, 10 min, or custom) — no limit runs a stopwatch instead
3. Toggle **Ignore accents** on or off (e.g. whether `een` passes for `één`)
4. Hit **Begin Quiz** — every number in the range is listed, type the Dutch word for each
5. Press Enter to jump to the next field
6. Hit **Check answers** when done (or wait for the timer)

---

## Modes

### List quiz (1-10 / 1-50 / 1-100)
All numbers in the chosen range appear at once. Fill in every translation, then check. Wrong answers show the correction in green. Final score shows correct/total and time taken (in stopwatch mode).

### Random mode 🎲
One random number (1-100) appears at a time. Type the Dutch translation and submit. You have **3 lives** - a wrong answer costs one. The game ends when all lives are lost. A streak counter tracks consecutive correct answers and turns red at 3+.

---

## Features

- Correct Dutch spellings including `één` (1), `tweeëntwintig` (22), `tweeëndertig` (32), and all other accented compound numbers
- **Accent toggle** - ignore accents (so `een` = `één`) or require exact spelling
- **Timer modes**: countdown (1/5/10 min or custom), stopwatch, or no limit
- **Random / survival mode** - 3 lives, streak counter, answer history
- Light and dark mode (auto-detects system preference, toggle in header)
- Fully responsive - works on mobile
- No install, no build step, no dependencies - open `index.html`

---

## Running locally

```bash
git clone https://github.com/zwagk/getallen
cd getallen
# Open index.html in any modern browser
```

No internet connection required - everything is self-contained.

---

## Dutch numbers covered

| Range | Examples |
|-------|---------|
| 1-10 | één, twee, drie... tien |
| 11-19 | elf, twaalf, dertien... negentien |
| 20-99 | twintig, eenentwintig, tweeëntwintig... negenennegentig |
| 100 | honderd |

Accented numbers in the dataset: `één` (1), and all compound numbers using `ë` (tweeëntwintig, drieëntwintig, tweeëndertig, etc.)

---

## Tech

Single-file vanilla HTML/CSS/JS. No framework, no build step, no dependencies.

---

Made by [zwagk](https://github.com/zwagk)
