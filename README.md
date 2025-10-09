
<p align="center">
  <img src="https://i.postimg.cc/Dw589NJ5/grok-image-xyt677o.jpg" alt="Project Logo" width="500">
  <h1 align="center">Made by HGH</h1>
  <p align="center">
    A free, simple, and open-source JSON API for fetching in-game stock and economy data from popular Roblox games.
    <br />
    <a href="https://api-giahuy.duckdns.org/"><strong>Visit the Homepage »</strong></a>
    <br />
    <br />
    <a href="https://discord.gg/chynUJbdwX">Report a Bug</a>
    ·
    <a href="https://discord.gg/chynUJbdwX">Request a Game</a>
  </p>
</p>


---

Tired of complex setups or web scraping to get in-game stock data? This API provides simple, free, and semi-reliable JSON endpoints for a few popular Roblox games. It's perfect for developers creating Discord bots, web dashboards, or any other project that needs up-to-date in-game stock information.

## 📖 Table of Contents

- [✨ Features](#-features)
- [💡 A Note on Performance](#-a-note-on-performance)
- [🎮 Supported Games](#-supported-games)
- [🚀 Quick Start](#-quick-start)
- [🗂️ API Endpoints & Response Formats](#️-api-endpoints--response-formats)
- [🤝 How to Contribute](#-how-to-contribute)
- [📜 License](#-license)

## ✨ Features

- **🎮 Multi-Game Support:** A single API for fetching stock data from multiple Roblox games.
- **⚡ Live Data:** Fetches data to provide the most current stock information.
- **🆓 Completely Free:** No API keys, no rate limits, and no cost.
- **🔄 CORS Enabled:** Use it directly from your frontend or backend applications without any hassle.
- **🤝 Open to Contributions:** Easily request new games or contribute new endpoints.
- **JSON Format:** Clean, predictable, and easy-to-parse JSON responses.

## 💡 A Note on Performance

To ensure the data is always up-to-date, this API fetches information live when a request is made. This process can sometimes take a few seconds to complete. Additionally, as a serverless function, the first request after a period of inactivity may experience a "cold start," which adds a little extra delay.

## 📚 API Documentation

| Section | Link |
|----------|------|
| Docs | [View API Docs](https://api-giahuy.duckdns.org/docs) |

## 🎮 Supported Games

| Game | API Endpoint | Status |
| :--- | :--- | :--- |
| **Grow a Garden** | [`Grow A Garden API`](https://api-giahuy.duckdns.org/api/v3/growagarden/stock) | ✅ Online |
| **Plants vs Brainrots** | [`Plants Vs Brainrots API`](https://api-giahuy.duckdns.org/api/v3/growagarden/stock) | ✅ Online |

*Don't see the game you need? [Open an issue](https://discord.gg/chynUJbdwX) to request it!*