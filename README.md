# 🚀 AstroWar — Browser-Based Space Shooter

AstroWar is a fast-paced space shooter that runs entirely in the browser using **plain HTML, CSS, and JavaScript**.

You control an astronaut spaceship and survive waves of asteroids and alien enemies while collecting power-ups and coins.

What makes it different is the control system — instead of just using a keyboard, you can **move your head to control the ship using your webcam**.

---

## 🔗 Live Demo

👉 https://dtlg7.netlify.app  

---

## ✨ Features

### 🎮 Gameplay
- Smooth spaceship movement  
- Asteroids with health, rotation, and textures  
- Alien enemies that shoot back  
- Cinematic explosions with particles, shockwaves, and screen shake  

### 🧠 Controls
- Head tracking using MediaPipe (move your head to steer)  
- Hand gesture support (pinch to toggle firing)  
- Keyboard fallback (WASD / Arrow keys + Space)  

### 🔫 Weapons & Powerups
- Twin Diagonal  
- Plasma Lance  
- Dual Beam  
- Shield power-up (temporary invincibility)  
- Coins dropped by enemies  

### 🧩 Procedural System
- 10+ enemy formations:
  - Core Wedge  
  - Diamond Shield  
  - Twin Wings  
  - Fortress  
  - Swarm  
- Difficulty increases as you progress  

### 🔊 Audio
- Fully generated using Web Audio API  
- No audio files — everything is synthesized in real-time  

### 🌐 Social & Multiplayer
- Global leaderboard (Firebase)  
- Player profiles (name, avatar, stats)  
- Friends system  
- Real-time multiplayer mode:
  - Create a match  
  - Share link  
  - Play together with live score sync  

### 🎨 UI
- Dark space-themed design with neon accents  
- Animated home screen  
- Fully responsive (mobile-friendly)  
- Bottom navigation (Home, Play, Versus, Ranks, Profile)  

---

## 🛠️ Tech Stack

- HTML5, CSS3, Vanilla JavaScript (ES6+)  
- HTML5 Canvas  
- MediaPipe FaceMesh + Hands  
- Web Audio API  
- Firebase Realtime Database  
- Netlify  

---

## 📁 Project Structure

```
index.html          — Main entry point
main.js             — App bootstrap
app.css             — Styles

src/
  data/
    db.js
    scores.js

  game/
    state.js
    entities.js
    patterns.js
    renderer.js
    input.js
    loop.js
    game.js
    sound.js
    utils.js

  ui/
    router.js
    home.js
    leaderboard.js
    profile.js
    multiplayer.js
```

---

## ⚡ How to Run Locally

No setup required.

1. Clone the repo
```
git clone https://github.com/your-username/astrowar.git
cd astrowar
```

2. Open `index.html` in your browser

### Important (for camera features)
Run using:
- VS Code Live Server  
- or `localhost`  
- or HTTPS  

Example:
```
npx serve
```

---

## 🎮 Controls

### Camera Mode
- Move head → steer  
- Pinch fingers → toggle firing  

### Keyboard Mode
- Move → Arrow keys / WASD  
- Fire → Space (hold)  
- Auto-fire → Backspace  

---

## ⚔️ Multiplayer

1. Go to the **Versus** tab  
2. Create a match  
3. Share the link  
4. Both players join  
5. Play simultaneously  
6. Highest score wins  

---

## 📸 Screenshots

(Add screenshots or GIFs here)

---

## 🤝 Contributing

1. Fork the repo  
2. Create a branch  
3. Make changes  
4. Submit a pull request  

---

## 👨‍💻 Contributors

- Daksh  
- Lakshay  
- Tanish  

---

## 📜 License

MIT License  

---
