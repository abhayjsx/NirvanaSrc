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
- 🎵 **Supports Multiple Platforms** – YouTube, Spotify, SoundCloud, and more
- 🛠️ **Slash Command & Context Menu Support**
- 🪄 **Smart AutoPlay & 24/7 Mode**
- 💾 **Playlist Creation & Management**
- 🌐 **Multi-language Support**
- 🎛️ **Advanced Filters** (Bass Boost, Nightcore, Vaporwave, etc.)
- 🔒 **Owner & DJ Role System**
- ⚙️ **Easy to Setup, Lightweight & Fast**

---

## 🧠 Requirements

Before installing Nirvana, make sure you have the following:

- ![Node.js](https://img.shields.io/badge/Node.js-v20.11.1-green?logo=node.js) [Node.js LTS or higher](https://nodejs.org/)
- ![Lavalink](https://img.shields.io/badge/Lavalink-v4%2B-blue?logo=discord&logoColor=white) [Lavalink Server](https://github.com/lavalink-devs/Lavalink)

### Optional:

- ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white) [For persistent playlists or settings](https://www.mongodb.com/try/download/community)
- ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) [For containerized deployment](https://www.docker.com/)

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
