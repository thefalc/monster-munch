# Monster Munch — Math Adventure!

A fun, browser-based math game for young kids (ages 4-6). Help a friendly monster eat snacks by solving math problems!

**Zero dependencies. Single HTML file. Works on any device.**

## How to Play

1. Open `math-adventure.html` in any browser
2. Tap **PLAY** to start
3. Solve the math problem by tapping the correct answer
4. Feed the monster and watch it grow!

## Math Skills Practiced

| Category | Example | Range |
|---|---|---|
| Addition +1 | 5 + 1 = ? | 1-9 + 1 |
| Addition +2 | 4 + 2 = ? | 1-8 + 2 |
| Near doubles | 8 + 9 = ? | base 1-9, presented as base + (base+1) |
| Subtraction -1 | 7 - 1 = ? | 2-10 - 1 |
| Subtraction -2 | 9 - 2 = ? | 3-10 - 2 |

## Features

### Gameplay
- **Multiple choice** — 4 large, colorful buttons sized for small fingers
- **No time pressure** — kids can think as long as they need
- **Correct answers** — "ding ding" sound, food flies into the monster's mouth, stars burst
- **Wrong answers** — "womp womp" sound, the correct answer is highlighted and revealed
- **Retry missed problems** — wrong answers are re-queued and served again a few problems later for spaced repetition
- **Celebration** every 10 problems with confetti and score summary

### Monster Evolution
The monster levels up every 10 correct answers, gaining new colors, growing larger, and unlocking accessories:

| Level | Name | Unlocks |
|---|---|---|
| 1 | Baby Blob | Purple starter monster |
| 2 | Cool Blob | Blue color + rosy cheeks |
| 3 | Strong Blob | Green color + horns |
| 4 | Super Blob | Pink color + sparkle |
| 5 | Mega Blob | Gold color, bigger |
| 6+ | Ultra Blob | Red, max size |

A progress bar shows how close the kid is to the next evolution.

### Streak Rewards
Consecutive correct answers unlock escalating accessories on the monster:
- 3 in a row — Crown
- 5 in a row — Sunglasses + cartoon burp sound
- 7 in a row — Top hat
- 10 in a row — Rainbow

### Sound Effects (Web Audio API)
All sounds are generated with the Web Audio API — no audio files needed:
- **Ding ding** — two cheerful ascending tones
- **Womp womp** — classic sad trombone
- **Cartoon burp** — gurgling throat rumble with bubbly pops (on streak milestones)

### Monster Idle Animations
The monster breathes gently and blinks at random intervals while waiting for an answer, making it feel alive.

## Technical Details

- **Single file** — everything is in one self-contained HTML file (HTML + CSS + JS)
- **No build tools** — no npm, no bundler, just open the file
- **No dependencies** — only loads Google Fonts (Fredoka One + Nunito) for the rounded comic style
- **Responsive** — works on phones, tablets, and desktops
- **Touch-friendly** — minimum 64px button height, double-tap zoom prevention on iOS
- **Web Audio API** — all sound effects synthesized in the browser

## Running Locally

```bash
open math-adventure.html
```

Or drag the file into any browser window.
