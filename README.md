# 🕹️ Assembly: Endgame

> **Keep the programming world safe from Assembly!**  
> Guess the hidden word within 8 attempts before Assembly takes over.

---

## 🎮 Overview

**Assembly: Endgame** is a fun and interactive word-guessing game built with **React**.  
Inspired by *Hangman*, this version adds a coding twist — each wrong guess “destroys” one programming language until only Assembly remains.  

Your mission: **Guess the word correctly before the programming world is lost!**

---

## ✨ Features

- 🧠 Random word generator for unique gameplay every round.  
- 💻 Themed around popular programming languages.  
- 🎨 Beautiful color-coded language chips.  
- 💥 Smooth animations and confetti celebration on win.  
- ♻️ Option to start a new game instantly.  
- 🔊 Accessible design with screen reader-friendly status updates.  

---

## 🧩 How to Play

1. A random word is selected secretly by the game.  
2. Click the letters on the virtual keyboard to guess.  
3. Each incorrect guess removes one programming language from the lineup.  
4. Win by revealing all letters before Assembly wins the game!  

> “Guess wisely — once JavaScript, Python, and React are gone... Assembly takes over.”

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-------------|----------|
| **React.js** | Core frontend framework |
| **clsx** | Conditional CSS class management |
| **react-confetti** | Confetti animation on win |
| **Custom CSS** | Styling and layout |
| **ES Modules** | Organized code imports/exports |

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/assembly-endgame.git
cd assembly-endgame
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Start the Development Server
```bash
npm run dev
```

### 4️⃣ Play the Game
Open your browser and navigate to:
```
http://localhost:5173/
```

---

## 🖼️ Game Preview

| Gameplay Start | Mid-Game | You Win |
|----------------|-----------|----------|
| ![Start](<img width="820" height="708" alt="image" src="https://github.com/user-attachments/assets/d15bf871-ce21-4d1f-b51f-08fb6bd44a24" />
 | ![Midgame](<img width="787" height="807" alt="image" src="https://github.com/user-attachments/assets/9dd0a8dc-c95f-4223-b7e7-d22f0a597f00" />
) | 🎉 Confetti celebration! |

---

## 📁 Project Structure

```
assembly-endgame/
├── src/
│   ├── components/
│   │   └── AssemblyEndgame.jsx
│   ├── utils/
│   │   ├── getRandomWord.js
│   │   └── getFarewellText.js
│   ├── languages.js
│   ├── App.jsx
│   ├── main.jsx
│   └── styles.css
├── public/
│   └── favicon.ico
└── package.json
```

---

## 🧠 Future Enhancements

- 🌍 Multiplayer or timed challenge mode.  
- 🔤 Word difficulty selection (easy → expert).  
- 🎧 Sound effects for guesses and outcomes.  
- 📱 Mobile-friendly responsive layout.  

---

## 👨‍💻 Author

**Ashutosh Kumar Singh**  
💡 React Developer | Passionate about clean UI and fun coding experiences  

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ *If you like this project, don’t forget to star the repo!*
