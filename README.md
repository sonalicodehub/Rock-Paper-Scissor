# 🪨📄✂️ Rock Paper Scissors

A clean and simple **Rock Paper Scissors Game** built using **HTML**, **CSS**, and **JavaScript**. This browser-based game lets you play against a CPU opponent with smooth animations and a stylish dark interface, making it ideal for beginners learning web development.

---

## ✨ Features

- 🪨 Classic Rock, Paper, Scissors gameplay
- 🤖 Random CPU opponent with thinking delay
- 📊 Live scoreboard (You / Draw / CPU)
- 🎯 WIN / LOSE / DRAW result banner with random phrases
- 🎉 Confetti burst animation on every win
- 🔄 Reset button to clear all scores
- 🖥️ Simple and intuitive GUI
- ⚡ Instant result calculation
- 🌐 Built entirely with HTML, CSS & JavaScript
- 🎓 Beginner-friendly project

---

## 🎮 Game Controls

| Button   | Action                        |
|----------|-------------------------------|
| 🪨 Rock     | Play Rock against CPU      |
| 📄 Paper    | Play Paper against CPU     |
| ✂️ Scissors | Play Scissors against CPU  |
| Reset    | Clear all scores & reset arena |

---

## 🏆 Game Rules

| You       | CPU       | Result |
|-----------|-----------|--------|
| Rock      | Scissors  | ✅ You Win  |
| Paper     | Rock      | ✅ You Win  |
| Scissors  | Paper     | ✅ You Win  |
| Rock      | Paper     | ❌ You Lose |
| Paper     | Scissors  | ❌ You Lose |
| Scissors  | Rock      | ❌ You Lose |
| Any       | Same      | 🤝 Draw     |

---

## 🛠️ Tech Stack

| Layer      | Technology                              |
|------------|-----------------------------------------|
| Markup     | HTML5                                   |
| Styling    | CSS3 (Flexbox, Animations, Custom Properties) |
| Logic      | Vanilla JavaScript                      |
| Fonts      | Google Fonts (Bebas Neue, DM Sans)      |

---

## 📦 Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/sonalicodehub/rock-paper-scissors
cd rock-paper-scissors
```

### ▶️ Run the Application

```bash
# Simply open in browser
open index.html
```

> No installation or packages needed — just open `index.html` in any modern browser!

---

## 🤖 How the App Works

1. Player clicks **Rock**, **Paper**, or **Scissors** button
2. Player's choice is shown instantly in the arena
3. CPU shows a 🤔 thinking emoji for **600ms** suspense delay
4. CPU picks a **random** choice
5. Both choices are revealed with a **spring-bounce animation**
6. The **result banner** displays WIN / LOSE / DRAW with a random phrase
7. **Scoreboard updates** with a bump animation
8. On a WIN — **confetti bursts** across the screen 🎉
9. Click **Reset** to clear all scores and start fresh

---

## 📂 Project Structure

```
rock-paper-scissors/
│
├── index.html    ← entire game (HTML + CSS + JS in one file)
└── README.md     ← project documentation
```

---

## 📸 Sample Interface

```
 ─────────────────────────────────
       ROCK PAPER SCISSORS
     Best of legends · Pick your weapon
 ─────────────────────────────────
 |  You: 3  |  Draw: 1  |  CPU: 2  |
 ─────────────────────────────────
       🪨      VS      📄
      (You)          (CPU)
 ─────────────────────────────────
            ❌ LOSE
         Better luck next time!
 ─────────────────────────────────
  | 🪨 Rock | 📄 Paper | ✂️ Scissors |
 ─────────────────────────────────
            [ Reset Scores ]
 ─────────────────────────────────
```

---

## 🎨 Design Highlights

- 🌑 Dark brutalist theme with noise texture overlay
- 🌈 Gradient title (Red → Blue → Yellow per choice)
- 💡 Color-coded hover glow per button (Rock / Paper / Scissors)
- 📐 Fully responsive using `clamp()` for fluid font sizing
- ✨ Smooth CSS animations — reveal, bump, confetti burst

---

## 🌟 Future Enhancements

- 🌙 Light / Dark Mode Toggle
- 🏅 Best-of-5 or Best-of-10 Match Mode
- 📜 Game History Log
- ⌨️ Keyboard Input Support (R / P / S keys)
- 🔊 Sound Effects on Win / Lose / Draw
- 🤖 Smart CPU with difficulty levels (Easy / Medium / Hard)

---

## 📜 License

Released under the **MIT License** — free to use, modify, and distribute.

---

## 👨‍💻 Author

**Sonali Gupta** — Web Developer & Technology Enthusiast 🚀  
GitHub: [@sonalicodehub](https://github.com/sonalicodehub)
