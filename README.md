# CountJack 🃏

A browser-based blackjack card counting trainer built in a single HTML file. No frameworks. No install. No casino floor required.

![Vibe Coded](https://img.shields.io/badge/vibe-coded-purple)
![Casino Tested](https://img.shields.io/badge/casino-not%20tested-red)
![Pit Boss](https://img.shields.io/badge/pit%20boss-unaware-blue)

> [!WARNING]
> This project was built with AI assistance (vibe coded). While it works, the code hasn't been professionally audited — use at your own risk. If you get a chance, feel free to review the code before deploying. PRs and fixes are always welcome!

---

## What it does

CountJack helps you practice the Hi-Lo counting system alongside basic strategy decisions in real time. Think of it as a sparring partner for your brain — not a cheat code for Vegas. 🧠

- 🔢 **Running & True Count** — tracks RC and calculates TC (RC ÷ decks remaining) as you log cards
- 🤔 **Basic Strategy Advisor** — tells you whether to Hit, Stand, Double, Split, or Surrender based on your hand, the dealer's upcard, and the current true count
- 💰 **Bet Spread Recommendations** — Conservative (1–4×), Moderate (1–8×), or Aggressive (1–12×) sizing off your min/max bet. Choose wisely. Or don't.
- 🃏 **Shoe Setup** — supports 4, 6, and 8 deck shoes with a decks-remaining ticker for true count accuracy
- 🚨 **Insurance Alerts** — flags TC ≥ +3 when the dealer shows an ace (you're welcome)
- ↩️ **Undo History** — every action is logged and undoable, so you can replay hands and cry about them later

## How to use

Just open `index.html` in a browser. That's it. No npm install. No webpack config. No existential crisis.

```
open index.html
```

Set up your shoe, deal yourself a hand, pick the dealer's upcard, and start logging cards as they come out. The advisor updates in real time. Pretend the pit boss isn't watching.

## Tech

Vanilla HTML, CSS, and JavaScript. Zero dependencies. Zero build step. One file, 942 lines.

Fonts: Bebas Neue, DM Sans, DM Mono via Google Fonts.

## Disclaimer ⚖️

Card counting is legal (it's just math). Casinos, however, are not legally obligated to appreciate your math skills and may ask you to leave. This tool is purely educational — to understand the probabilistic thinking behind the game. What you do with that knowledge is between you and the pit boss.

Please gamble responsibly. Or just play for fun and keep your money. 🙏

MIT License.
