# Tower Clash 3D ⚔️

A 3D real-time strategy battle arena game built with Three.js — inspired by Clash Royale. Deploy troops, cast spells, destroy the enemy King Tower, and control the territory to win.

![Tower Clash](https://img.shields.io/badge/Three.js-r128-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## 🎮 Play

No build step required — it is a single static HTML file.

- **Local:** open `index.html` in any modern browser.
- **Online:** enable **GitHub Pages** (Settings → Pages → Branch: `main` → `/root`) and play from the live URL.

> Internet is required for the "Create Room" / "Join Room" online multiplayer (uses PeerJS).

## ✨ Features

- 3D battlefield with towers, bridges, river, trees and dynamic sky
- 10 collectible cards: Goblins, Knight, Archers, Wizard, Giant, Fireball, Barbarians, Freeze, Musketeer, Skeletons
- Card upgrade system with saved progress (localStorage) and gold coins
- Territory control bar + timed match, double elixir and overtime
- Play vs AI or online 1v1 with room codes
- Sound effects, particles, health bars and screen shake

## 🕹️ How to Play

- ⚡ **Elixir** regenerates over time — every card costs elixir.
- 🃏 Tap a card, then tap **your half** of the arena to deploy troops.
- 🔥 **Spells** like Fireball and Freeze can be cast anywhere.
- 🏰 Destroy the enemy **King Tower** to win instantly.
- 🌉 Troops cross the river on the two bridges.
- 🗺️ Every tower you keep controls **territory**.
- ⏱ At 1:00 left, **double elixir** kicks in, then overtime decides the winner.

## 🛠️ Tech Stack

- [Three.js](https://threejs.org/) (r128) for 3D rendering
- [PeerJS](https://peerjs.com/) for online multiplayer
- Plain HTML / CSS / JavaScript — zero dependencies to install

## 📁 Project Structure

```
tower-clash/
└── index.html   # entire game (HTML + CSS + JS)
```

## 🚀 Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `tower-clash`).
2. Push this folder to it (see commands below).
3. Repository **Settings → Pages → Source: Deploy from a branch → `main` / `/root`**.
4. Your game goes live at `https://<your-username>.github.io/tower-clash/`.

```bash
git init
git add .
git commit -m "Initial commit: Tower Clash 3D"
git branch -M main
git remote add origin https://github.com/<your-username>/tower-clash.git
git push -u origin main
```

## 📜 License

MIT
