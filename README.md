# 🌌 Galaxy Factory — Stardust Clicker

Welcome to **Galaxy Factory**, a feature-rich, space-themed idle/clicker game where you harvest stardust, build cosmic factories, and ascend through the tiers of the universe!

The entire game is built in a **single `index.html` file** — no frameworks, no build tools, no external assets. Pure web technology.

---

## 👨‍💻 About the Developer

| | |
|---|---|
| **Developer** | Nhat (Nhất) |
| **Grade** | 5th Grade Student & Future Software Engineer 🚀 |
| **GitHub** | [danghuuthanh805-hub](https://github.com/danghuuthanh805-hub) |
| **Version** | 2.0 |

---

## 🎮 Game Features

### Core Gameplay
- **Tap to Earn** — Tap the Star Core to harvest Stardust ✨
- **15 Unique Upgrades** — From Star Finger 👆 to Multiverse ♾️, unlock tap power boosters and auto-collectors
- **Prestige System** — Reset at 1M total dust to earn Star Gems 💎 that permanently multiply ALL earnings by +25% each

### ⚡ Combo System
- Tap fast to build a **combo multiplier** (up to x5!)
- Visual combo bar fills as you tap rapidly
- Stop tapping and the combo decays — keep the rhythm going!

### 💥 Critical Hits
- Every tap has a chance to trigger a **Critical Hit** (5% base chance)
- Crits deal **5x~15x** damage with special red visual effects and sound
- Prestige increases both crit chance (+0.5% per prestige) and crit multiplier (+1x per prestige)

### ⭐ Star Core Evolution (10 Tiers)
Your Star Core **visually transforms** as you progress through 10 unique tiers:

| Tier | Name | Requirement |
|------|------|-------------|
| 1 | ⭐ Spark | 0 |
| 2 | 🔥 Ember | 500 |
| 3 | ☀️ Flame | 5K |
| 4 | 💫 Nova | 50K |
| 5 | ⚡ Pulsar | 500K |
| 6 | 🌟 Quasar | 5M |
| 7 | 🌌 Nebula | 50M |
| 8 | 💥 Supernova | 500M |
| 9 | 🔮 Cosmos | 5B |
| 10 | ♾️ Infinity | 50B |

Each tier changes the Star Core's color palette, glow effects, ray count, and orbiting particles.

### 🏆 Achievement System (20 Achievements)
Track your milestones across multiple categories:
- **Tap milestones** — First Tap → Tap Legend (10,000 taps)
- **Dust milestones** — Dust Collector → Trillionaire
- **Upgrade milestones** — Upgrader → Factory Boss
- **Prestige milestones** — Reborn → Veteran
- **Gem milestones** — Gem Collector → Gem King
- **Tier milestones** — Rising Star → Supernova
- **DPS milestones** — Automation → Mass Production

### 📊 Detailed Statistics
A full stats panel tracks everything in real-time:
- Total taps, total dust earned, current dust
- Tap power, dust/s, gem multiplier
- Crit chance & multiplier, current tier
- Total upgrades bought, achievements unlocked
- Total time played

### 💾 Smart Save System
- **Auto-save** every 5 seconds via `localStorage`
- **Offline earnings** — Earn dust while away (50% efficiency, up to 2 hours)
- **Welcome back** notification shows how much you earned offline
- **Reset option** in Settings to start fresh

### 📱 Universal Compatibility
- Works on **all devices**: phones, tablets, laptops, desktops
- **Responsive layout** adapts to any screen size
- **Touch optimized** with proper pointer events (no double-tap zoom issues)
- Runs at **smooth 60fps** even on low-end devices

---

## 🛠️ Technical Details

### Built With
| Technology | Purpose |
|---|---|
| **HTML5 Canvas** | All game graphics rendered programmatically — star core, planets, particles, floating text |
| **Web Audio API** | Synthesized sound effects (tap, buy, crit, prestige, achievement) — no audio files needed |
| **CSS3** | Responsive UI layout with `clamp()`, flexbox, and CSS variables |
| **JavaScript (ES6)** | Game loop, state management, upgrade math, save/load system |

### Performance Optimizations
- **Single render pass** — Background stars drawn as fast `fillRect` instead of `arc`
- **Dirty flag system** — UI only re-renders when data actually changes
- **Conditional canvas drawing** — Only the visible screen's canvas is drawn each frame
- **Minimal DOM manipulation** — Upgrade list HTML is compared before writing
- **Efficient particles** — Limited count, drawn as rectangles, cleaned per-frame
- **No external dependencies** — Zero network requests during gameplay

### Code Stats
- **Single file**: `index.html`
- **Zero dependencies**: No libraries, no CDNs, no images, no fonts
- **~700 lines** of optimized, production-ready code

---

## 🚀 How to Play

1. **Open** `index.html` in any modern browser
2. **Tap** the Star Core to harvest Stardust
3. **Buy upgrades** to increase tap power and auto-collection
4. **Tap fast** to build combo multiplier (up to x5!)
5. **Watch for crits** — red flashing numbers mean big bonus!
6. **Prestige** at 1M total dust for permanent gem multipliers
7. **Unlock achievements** and climb through the 10 star tiers
8. **Close the tab safely** — your progress auto-saves and you'll earn offline dust!

---

## 🌐 Play Online

Play the game directly at: **[Galaxy Factory on GitHub Pages](https://danghuuthanh805-hub.github.io/Galaxy-factory/)**

---

## 📄 License

This project is open source. Feel free to learn from, modify, and share it!

---

*Thank you for checking out Galaxy Factory! If you enjoy the game, please leave a ⭐ on GitHub!*
