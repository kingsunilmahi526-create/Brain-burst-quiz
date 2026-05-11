# 🧠 BrainBurst – General Knowledge Quiz Website

A bright, playful, and fully interactive quiz website built with pure HTML, CSS, and JavaScript. No frameworks or build tools required!

---

## 📁 Project Structure

```
quiz-website/
├── index.html          ← Main HTML file
├── css/
│   └── style.css       ← All styles (bright & playful theme)
├── js/
│   ├── questions.js    ← All 60 questions (Easy / Medium / Hard)
│   └── app.js          ← Quiz logic & game engine
└── README.md
```

---

## 🚀 How to Run in VS Code

### Option 1 – Live Server (Recommended)
1. Open the `quiz-website` folder in VS Code
2. Install the **Live Server** extension (by Ritwick Dey)
3. Right-click `index.html` → **"Open with Live Server"**
4. The quiz opens in your browser at `http://127.0.0.1:5500`

### Option 2 – Open Directly
1. Just double-click `index.html` to open it in your browser

---

## 🎮 Features

| Feature | Details |
|---|---|
| 🎯 Questions | 20 questions per game, randomly selected |
| 📚 Difficulties | Easy (30s), Medium (25s), Hard (20s) |
| 🏷️ Categories | Geography, Science, History, Arts, Nature |
| ⏱️ Timer | Per-question countdown with color indicators |
| ⭐ Live Score | Updates in real-time as you answer |
| 🔵 Progress Dots | Visual tracker showing correct/wrong/skipped |
| 💬 Floaty Feedback | Fun animated messages for right/wrong answers |
| 🏆 Results Screen | Score circle, stats, emoji rating |
| 📋 Answer Review | Full review of every question with correct answers |
| 📱 Responsive | Works on mobile and desktop |

---

## ✏️ How to Customize

### Add More Questions
Open `js/questions.js` and add to the `easy`, `medium`, or `hard` arrays:
```js
{
  category: "🎮 Gaming",
  question: "Your question here?",
  options: ["Option A", "Option B", "Option C", "Option D"],
  answer: 0  // index of correct answer (0 = A, 1 = B, 2 = C, 3 = D)
}
```

### Change Timer Duration
In `js/app.js`, edit the `timePerQ` object:
```js
timePerQ: { easy: 30, medium: 25, hard: 20 }
```

### Change Colors / Theme
Edit CSS variables at the top of `css/style.css`:
```css
:root {
  --orange: #FF6B35;
  --pink: #FF4D6D;
  --blue: #4D96FF;
  /* etc. */
}
```

---

## 🌐 Technologies Used
- **HTML5** – Structure
- **CSS3** – Animations, gradients, responsive layout
- **Vanilla JavaScript** – Game logic, DOM manipulation
- **Google Fonts** – Fredoka One + Nunito

---

Enjoy playing BrainBurst! 🎉
