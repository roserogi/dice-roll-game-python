# dice-roll-game-python
Built a multiplayer dice game in Python for 2–4 players. The game features turn-based logic, score tracking, input validation, and random dice rolls. Players take risks each turn to build their score, but rolling a 1 ends their turn with zero points. The first player to reach 50 wins.
# 🎲 Dice Rolling Game (Python)

A fun, turn-based dice game for 2–4 players written in Python. The goal? Be the first to reach 50 points without rolling a 1!

---

## 📜 Game Description

Each player takes turns rolling a 6-sided die. On each roll:

- If you roll **2–6**, that number gets added to your **turn score**.
- You may choose to **roll again** or **hold** (add your turn score to your total score).
- If you roll a **1**, your turn score is lost, and your turn ends immediately.

🎯 **First player to reach or exceed 50 points wins the game!**

---

## 👨‍👩‍👧‍👦 Number of Players

- 2 to 4 players

---

## 🧠 Rules

- You can keep rolling as long as you don't roll a 1.
- Rolling a 1 resets your turn score to 0.
- Strategic play: stop rolling before you risk a 1!

---

## ▶️ How to Play

1. Clone or download this repository.
2. Run the game using Python 3:

```bash
python dice_game.py
