# Nirvana

<center><img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Nirvana&fontSize=80&fontAlignY=35&animation=twinkling&fontColor=gradient" /></center>

[![Node.js][node-shield]](#)
[![Discord.js][discordjs-shield]](#)
[![License][license-shield]](license-url)
[![Support Server][support-shield]][support-url]
[![Version][version-shield]](#)
[![Contributors][contributors-shield]][contributors-url]
[![Stars][stars-shield]][stars-url]

<br />

<p align="center">
  <a href="https://discord.gg/9bWCU6VPEM">
    <img src="nirvana.jpg" alt="Nirvana" width="200" height="200">
  </a>
</p>

<h1 align="center">Nirvana</h1>

<p align="center">
  <b>Nirvana — A Quality Music Bot that Makes You Feel the Music and its Beats.</b><br>
  Your go-to bot for instant tunes, harmonic brilliance, and personalized playlists.<br>
  <br />
  <a href="https://discord.com/oauth2/authorize?client_id=1044688839005966396&permissions=8&scope=bot">Invite Nirvana</a>
  ·
  <a href="https://discord.gg/9bWCU6VPEM">Join Support Server</a>
</p>

---

## 🌟 Features

- 🎧 **Crystal Clear Audio Quality**
- 🎵 **Supports Multiple Platforms** – YouTube, Spotify, SoundCloud, etc.
- 🛠️ **Slash Command & Context Menu Support**
- 🪄 **Smart AutoPlay & 24/7 Mode**
- 💾 **Playlist Creation & Management**
- 🌐 **Multi-language Support**
- 🎛️ **Advanced Filters** (Bass Boost, Nightcore, Vaporwave, etc.)
- 🔒 **Owner & DJ Role System**
- ⚙️ **Lightweight, Fast & Easy Setup**

---

## 🧠 Requirements

- ![Node.js](https://img.shields.io/badge/Node.js-v20.11.1-green?logo=node.js) Latest LTS Node.js
- ![Lavalink](https://img.shields.io/badge/Lavalink-v4%2B-blue?logo=discord&logoColor=white) Lavalink v4+

### Optional

- MongoDB (for persistent playlists/settings)
- Docker (for container deployment)

---

## 🚀 Installation from Source

### 1. Clone the Repository

```bash
git clone https://github.com/abhay/Nirvana.git
```

### 2. Enter the Directory

```bash
cd Nirvana
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment

Copy `.env.example` to `.env`:

```env
TOKEN=your_discord_bot_token
PREFIX=!
OWNER_ID=your_discord_user_id
LAVALINK_HOST=localhost
LAVALINK_PORT=2333
LAVALINK_PASSWORD=youshallnotpass
```

### 5. Run the Bot

```bash
npm start
```

### 6. Invite Nirvana to Your Server

[Invite Link](https://discord.com/oauth2/authorize?client_id=1044688839005966396&permissions=8&scope=bot)

---

## 🐳 Docker Installation

1. Prepare the `.env` file.
2. Run:

```bash
docker compose up -d
```

To update:

```bash
docker compose up --force-recreate --build -d
docker image prune -f
```

---

## 💬 Commands Overview

| Command          | Description                  |
| ---------------- | ---------------------------- |
| `/play <song>`   | Play a track from any source |
| `/skip`          | Skip current track           |
| `/queue`         | View queue                   |
| `/pause`         | Pause playback               |
| `/resume`        | Resume playback              |
| `/stop`          | Stop all playback            |
| `/filter <type>` | Apply a filter               |
| `/24_7`          | Toggle 24/7 mode             |

---

## 📢 Support

Join our Discord: [https://discord.gg/9bWCU6VPEM](https://discord.gg/9bWCU6VPEM)

Or open an issue: [https://github.com/abhay/Nirvana/issues](https://github.com/abhay/Nirvana/issues)

---

## 🧩 Technologies Used

- Node.js
- Discord.js
- Lavalink
- Shoukaku / Kazagumo
- MongoDB
- Docker

---

## 👨‍💻 Contributing

1. Fork the repo
2. Create a branch: `git checkout -b feature/AmazingFeature`
3. Commit changes
4. Push: `git push origin feature/AmazingFeature`
5. Open a PR

---

## ⚖️ License

Distributed under the **MIT License**.

---

<div align="center">
  <h3>💖 Thank you for choosing Nirvana!</h3>
  <p>Taste the Opulence of Harmonic Brilliance 🎶</p>
</div>

[node-shield]: https://img.shields.io/badge/node-v20.11.1-green?style=for-the-badge&logo=node.js
[discordjs-shield]: https://img.shields.io/badge/discord.js-latest-blue?style=for-the-badge&logo=discord&logoColor=white
[license-shield]: https://img.shields.io/badge/license-MIT-red?style=for-the-badge
[license-url]: ./LICENSE
[support-shield]: https://img.shields.io/discord/987749138743582811?color=7289da&logo=discord&logoColor=white&style=for-the-badge
[support-url]: https://discord.gg/9bWCU6VPEM
[contributors-shield]: https://img.shields.io/github/contributors/abhay/Nirvana?style=for-the-badge
[contributors-url]: https://github.com/abhay/Nirvana/graphs/contributors
[stars-shield]: https://img.shields.io/github/stars/abhay/Nirvana.svg?style=for-the-badge
[stars-url]: https://github.com/abhay/Nirvana/stargazers
