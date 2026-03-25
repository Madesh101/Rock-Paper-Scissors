# 🪨📄✌️ Rock Paper Scissors

A clean, dark-themed Rock Paper Scissors game built with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies — just open and play.

---

## 📁 Project Structure

```
📁 your-folder/
├── Rock-Paper-Scissors.html    # Main page (open this in browser)
│   └── Rock-Paper-Scissors.css
│   └── Rock-Paper-Scissors.js
├── images/
│   ├── rock-emoji.png
│   ├── paper-emoji.png
│   └── scissors-emoji.png
└── README.md
```

> ⚠️ Keep the `images/`, `styles/`, and `scripts/` folders in the **same directory** as the HTML file.

---

## 🚀 Getting Started

1. Download all files keeping the folder structure intact
2. Double-click `Rock-Paper-Scissors.html` to open in your browser
3. No install or build step needed — just play!

---

## ✨ Features

| Feature | Description |
|---|---|
| 🪨 📄 ✌️ Play | Click any of the 3 move buttons to make your move |
| 🤖 Auto Play | Computer plays both sides automatically every second |
| 🏆 Score Tracking | Wins, Losses, and Ties update after every round |
| 💾 Persistent Score | Score is saved in `localStorage` — survives page refresh |
| 🔄 Reset Score | Clears the scoreboard and wipes localStorage |
| 🟢🔴⚪ Result Colors | Win = green · Lose = red · Tie = gray |
| 🖼️ Move Display | Shows your move vs computer's move as emoji icons |

---

## 🎮 How to Play

1. Click **Rock**, **Paper**, or **Scissors** to make your move
2. The computer picks a random move instantly
3. Result appears — **You Win**, **You Lose**, or **Tie**
4. Score updates automatically and is saved in your browser

### Auto Play
- Click **Auto Play** to watch the computer play both sides (1 round/second)
- Button changes to **Stop** — click again to end it

### Reset
- Click **Reset Score** to wipe all scores back to zero

---

## 🎨 Design

- Dark background `#0f0f0f` with charcoal card surfaces
- *Syne* display font — bold, geometric, modern
- *Syne Mono* monospace font for the score
- Circular move buttons with a **gold glow + lift** on hover
- Result text color changes dynamically per outcome
- Layout built with **CSS Grid on `<body>`** — places the 3 move buttons in a horizontal row with no extra wrapper `<div>` needed

---

## 🛠️ Built With

- **HTML5** — structure
- **CSS3** — grid layout, transitions, CSS custom properties
- **Vanilla JavaScript** — game logic, localStorage
- **Google Fonts** — Syne + Syne Mono

---

## 🧠 Game Logic

```
Rock     beats  Scissors
Scissors beats  Paper
Paper    beats  Rock
```

The computer's move is chosen using `Math.random()` with equal ~33% probability for each option.

---

## 📌 Notes

- Score persists via `localStorage` — survives refreshes but clears if browser data is wiped
- No `<div>` wrappers were added to the HTML; the horizontal button layout is achieved purely with CSS Grid assigned to `body`

---

## 👤 Author

Built as a vanilla JS learning project.
