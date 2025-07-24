# Monopoly-Simulator
What properties are the best in Monopoly? How can you guarantee a win every time? (You obviously can't, only read through this to gain a minor advantage :))

This project simulates full games of Monopoly using Python — four players, real property buying, house building, bankruptcies, and a winner at the end. I built it to explore how Monopoly plays out when you remove player trading (spoiler: the brown and dark blue properties win way more than they should).

---

# Why I Built This

I'm annoying to play monopoly with. I don't give up until a trade is made. I will offer ridiculous ideas such as "if you give me Indiana I'll give you a utility and throw in a 20% stake of my red monopoly" or "For the rest of the game you get $1 for every number rolled on my turns if you throw in $150"

I wanted to simulate Monopoly beyond just “which square gets landed on most.” I was curious what happens when players play out entire games with basic rules — no advanced strategy, just roll, buy, build, pay rent, and survive.

It turns out when players don’t trade, only the smallest (brown) and most powerful (dark blue) monopolies tend to get completed. And they dominate the win conditions.

---

# What It Does

- Simulates full Monopoly games with 4 players
- Each player:
  - Rolls dice and moves around the board
  - Buys unowned properties when possible (the well-known best strategy)
  - Builds houses when they complete a color set
  - Pays rent, mortgages if needed, or goes bankrupt
- Tracks:
  - Who wins
  - What properties they own
  - How many houses they built
  - How many times each player rolled the dice
- Ends when either:
  - Everyone but one player goes bankrupt
  - Each player hits 100 turns (so games don’t go forever)

---
