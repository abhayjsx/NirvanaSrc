<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Nirvana&fontSize=80&fontAlignY=35&animation=twinkling&fontColor=gradient" alt="Nirvana Banner" />

  <!-- Badges -->
  <p align="center">
    <a href="https://nodejs.org/">
      <img src="https://img.shields.io/badge/Node.js-v18%2B-339933?logo=node.js&logoColor=white" alt="Node.js">
    </a>
    <a href="https://discord.js.org/">
      <img src="https://img.shields.io/badge/Discord.js-v14-5865F2?logo=discord&logoColor=white" alt="Discord.js">
    </a>
    <a href="https://github.com/siddhantabhang/NirvanaSrc/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/siddhantabhang/NirvanaSrc?color=blue" alt="License">
    </a>
    <a href="https://github.com/siddhantabhang/NirvanaSrc/stargazers">
      <img src="https://img.shields.io/github/stars/siddhantabhang/NirvanaSrc?color=yellow" alt="Stars">
    </a>
    <a href="https://github.com/siddhantabhang/NirvanaSrc/network/members">
      <img src="https://img.shields.io/github/forks/siddhantabhang/NirvanaSrc?color=green" alt="Forks">
    </a>
  </p>

  <!-- Logo -->
  <img src="nirvana.jpg" alt="Nirvana Logo" width="200" style="border-radius: 50%; margin: 20px 0; border: 5px solid #7289DA" />

  <!-- Title -->
  <h1>Nirvana</h1>
  <h3>🎵 A High-Quality Discord Music Bot</h3>
  <p>Experience crystal clear audio, powerful features, and seamless performance</p>

  <!-- Buttons -->
  <p>
    <a href="https://discord.com/oauth2/authorize?client_id=1044688839005966396&permissions=8&scope=bot%20applications.commands">
      <img src="https://img.shields.io/badge/Invite-Bot-7289DA?style=for-the-badge&logo=discord" alt="Invite Bot">
    </a>
    <a href="https://discord.gg/9bWCU6VPEM">
      <img src="https://img.shields.io/badge/Join-Support_Server-7289DA?style=for-the-badge&logo=discord" alt="Support Server">
    </a>
    <a href="https://github.com/siddhantabhang/NirvanaSrc/issues">
      <img src="https://img.shields.io/badge/Report-Issue-FF0000?style=for-the-badge&logo=github" alt="Report Issue">
    </a>
  </p>
</div>

---

## ✨ Key Features

### 🎵 Music Features
- 🎧 Crystal Clear Audio Quality (Opus 256kbps)
- 🌐 Multi-Platform Support (YouTube, Spotify, SoundCloud, Apple Music, and more)
- 🔄 24/7 Music Playback with Auto-Reconnect
- 🎚️ Advanced Audio Filters (Bass Boost, Nightcore, Vaporwave, etc.)
- 🔄 Auto-Play & Queue System
- 📻 Radio Stations Support
- 📻 Live Stream Support

### 🤖 Bot Features
- 💾 Playlist Management (Save, Load, Delete)
- 🎛️ DJ Role System with Custom Permissions
- 📊 Server Statistics & Music Analytics
- 🎨 Customizable Embeds & Messages
- ⚡ Fast & Lightweight
- 🔒 Secure & Private
- 📱 Mobile-Friendly Controls

### 🛠️ Developer Friendly
- 🔄 Easy to Deploy
- 📝 Well-Documented Code
- 🧩 Modular Architecture
- 🔄 Auto-Updating System
- 🛡️ Built-in Error Handling

---

## 🚀 Quick Start

### Prerequisites
- [Node.js](https://nodejs.org/) v18 or higher
- [Lavalink](https://github.com/lavalink-devs/Lavalink) server (v4+)
- Discord Bot Token from [Discord Developer Portal](https://discord.com/developers/applications)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/siddhantabhang/NirvanaSrc.git
   cd NirvanaSrc
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure the bot**
   ```bash
   cp .env.example .env
   # Edit the .env file with your credentials
   ```

4. **Start the bot**
   ```bash
   npm start
   ```

### 🐳 Docker Installation

```bash
docker-compose up -d
```

## 📦 Dependencies

### Core
- [Node.js](https://nodejs.org/) - JavaScript runtime
- [Discord.js](https://discord.js.org/) - Discord API library
- [Erela.js](https://github.com/MenuDocs/erela.js) - Music manager
- [MongoDB](https://www.mongodb.com/) - Database (optional)

### Development
- [TypeScript](https://www.typescriptlang.org/) - Type checking
- [ESLint](https://eslint.org/) - Code linting
- [Prettier](https://prettier.io/) - Code formatting

---

## 🚀 Installation from Source

1. **Clone the Repository**
   ```bash
   git clone https://github.com/abhay/Nirvana.git
   ```

````

2. **Enter the Directory**

   ```bash
   cd Nirvana
   ```

3. **Install Dependencies**

   ```bash
   npm install
   ```

4. **Configure Environment**
   Copy `.env.example` to `.env` and fill in the required values:

   ```env
   TOKEN=your_discord_bot_token
   PREFIX=!
   OWNER_ID=your_discord_user_id
   LAVALINK_HOST=localhost
   LAVALINK_PORT=2333
   LAVALINK_PASSWORD=youshallnotpass
   ```

5. **Run the Bot**

   ```bash
   npm start
   ```

6. **Invite to Your Server**
   [Invite Nirvana](https://discord.com/oauth2/authorize?client_id=1044688839005966396&permissions=8&scope=bot)

---

## 🐳 Installation with Docker

1. Copy the `.env` file and fill it properly.

2. Then run:

   ```bash
   docker compose up -d
   ```

3. The bot should now be running!
   To update Nirvana:

   ```bash
   docker compose up --force-recreate --build -d
   docker image prune -f
   ```

---

## 💬 Commands Overview

| Command          | Description                            |
| ---------------- | -------------------------------------- |
| `/play <song>`   | Plays a song from any supported source |
| `/skip`          | Skips to the next track                |
| `/queue`         | Shows the current queue                |
| `/pause`         | Pauses the music                       |
| `/resume`        | Resumes playback                       |
| `/stop`          | Stops playback                         |
| `/filter <type>` | Applies a music filter                 |
| `/24_7`          | Toggles 24/7 mode                      |

---

## 📢 Support

Having issues or ideas?
Join our support community: [Discord Server](https://discord.gg/9bWCU6VPEM)

You can also open an issue on [GitHub](https://github.com/abhay/Nirvana/issues).

---

## 🧩 Technologies Used

* [Node.js](https://nodejs.org/)
* [Discord.js](https://discord.js.org/)
* [Lavalink](https://github.com/lavalink-devs/Lavalink)
* [Kazagumo / Shoukaku](https://github.com/Deivu/Shoukaku)
* [MongoDB](https://www.mongodb.com/)
* [Docker](https://www.docker.com/)

---

## 👨‍💻 Contributing

We welcome contributions!

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## ⚖️ License

Distributed under the **MIT License**.
See the [LICENSE](./LICENSE) file for more information.

---

<div align="center">
  <h3>💖 Thank you for choosing Nirvana!</h3>
  <p>Taste the Opulence of Harmonic Brilliance 🎶</p>
</div>

---

[version-shield]: https://img.shields.io/github/package-json/v/abhay/Nirvana?style=for-the-badge
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

```
````
