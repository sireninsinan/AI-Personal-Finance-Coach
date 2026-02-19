# 🧠 TRAC Finance Coach — AI Crypto Advisor

> An AI-powered personal finance coach for TRAC & crypto holders, built on the Intercom P2P agent network.

[![Built on Intercom](https://img.shields.io/badge/Built%20on-Intercom-00ffa3?style=flat-square)](https://github.com/Trac-Systems/intercom)
[![Fork](https://img.shields.io/badge/Fork%20of-Trac--Systems%2Fintercom-7b61ff?style=flat-square)](https://github.com/Trac-Systems/intercom)

---

## 💡 What is TRAC Finance Coach?

A lightweight AI agent that acts as your **crypto financial advisor** for TRAC and the Trac ecosystem. Users can ask natural-language questions about their holdings and get:

- 📊 **Risk Assessment** — Low / Medium / High scoring based on conversation context
- 💬 **Hold vs. Move Signals** — Framework-based recommendations
- 📈 **DCA & Strategy Tips** — Time-tested approaches for volatile assets
- 🔍 **Wallet Activity Comparison** — How your behavior compares to avg TRAC holders
- 📖 **Tokenomics Explanations** — TRAC, TAP, Pipe, Intercom — all explained simply

> ⚠️ **Not financial advice.** All outputs are educational and for informational purposes only. Always do your own research.

---

## 🚀 Live App

Open `index.html` in your browser — no server needed. Pure HTML/CSS/JS.

### Features:
- Real-time AI chat interface
- Quick-action prompt buttons
- Animated risk meter per response
- Session question counter
- Mobile-responsive design
- Built with Intercom P2P agent architecture in mind

---

## 📸 Screenshots

> *(Add your own screenshots here after running the app)*

![TRAC Finance Coach Screenshot](./screenshot.png)

---

## 🛠 How to Run

```bash
# Clone this repo
git clone https://github.com/YOUR_USERNAME/intercom

# Open the app
open index.html
# or just double-click index.html in your file explorer
```

No dependencies. No build step. No API keys needed for the demo.

---

## 🔗 Intercom Integration

This app is designed as an Intercom agent. In a full deployment:

1. The AI coach runs as an **Intercom agent** on the Trac P2P network
2. Users connect their TRAC wallet address
3. The agent pulls on-chain data via Intercom sidechannels
4. Personalized risk scoring is computed in real-time

The `SKILL.md` file documents the agent's capabilities for other Intercom agents.

---

## 📬 TRAC Payout Address

```
trac1gklwft2t72gywvgvgyrtnev8r8a976n97hmgdcykzq5yevy4jecsv5t4ve
```

> Replace the above with your actual Trac address to receive the 500 TNK payout.

---

## 📁 File Structure

```
intercom/
├── index.html          # Main app — TRAC Finance Coach UI
├── SKILL.md            # Agent skill file for Intercom agents
├── README.md           # This file
└── screenshot.png      # App screenshot (add yours)
```

---

## 🌐 About Trac Systems

- Upstream Intercom: https://github.com/Trac-Systems/intercom
- Trac Network: https://trac.network
- Awesome Intercom: https://github.com/Trac-Systems/awesome-intercom

---

*Built for the Intercom fork competition. Fork it, ship it, earn TNK.*
