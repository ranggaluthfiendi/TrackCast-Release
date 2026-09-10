# 🎵 TrackCast

<p align="center">
  <strong>Interactive TikTok Live & YouTube Music Song Request Player with Synced Lyrics & OBS Overlays</strong>
</p>

<p align="center">
  <a href="https://github.com/ranggaluthfiendi/TrackCast-Release/releases/latest"><img src="https://img.shields.io/github/v/release/ranggaluthfiendi/TrackCast-Release?style=for-the-badge&color=00d2de" alt="Latest Release"></a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2B-blue?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

---

## 📥 Download TrackCast for Windows

Click the link below to get the latest official installer:

👉 **[Download TrackCast Setup v1.0.0 (.exe)](https://github.com/ranggaluthfiendi/TrackCast-Release/releases/latest/download/TrackCast-Setup-1.0.0.exe)**

*(Or visit all releases on the [Releases Page](https://github.com/ranggaluthfiendi/TrackCast-Release/releases))*

---

## ✨ Features

* 🔴 **Zero-Setup TikTok Live Connection**: Connect simply by entering your `@username`. No developer tokens or paid APIs required.
* 🎧 **High-Quality YouTube Playback**: Instant search and automatic high-resolution audio queue playback.
* 🎤 **Word-by-Word Synchronized Karaoke Lyrics**: Accurate real-time lyrics powered by NetEase, QQ Music, Kugou, and LRCLIB.
* 🌐 **Dual Subtitle Multi-Language Translations**: Real-time translation to English, Indonesian, Japanese, Korean, and Chinese with Romaji support.
* 🖥️ **6 Dedicated OBS Studio Overlays**:
  * **Overlay Lyrics** (`/overlay/lyrics`): Cinematic karaoke lyrics.
  * **Overlay Queue** (`/overlay/queue`): Live request queue list.
  * **Overlay Now Playing** (`/overlay/now-playing`): Sleek album card.
  * **Overlay Alert** (`/overlay/alert`): Toast notifications when songs are added.
  * **Overlay Compact Ticker** (`/overlay/compact`): Bottom ticker marquee.
  * **Overlay Timeline** (`/overlay/timeline`): Previous / Now / Next preview.
* 🛡️ **Anti-Spam & Fair Queue System**: Built-in viewer request limits, cooldowns, and customizable term/song/user blacklists.

---

## 🚀 Quick Start Guide

1. **Install Application**: Download and run `TrackCast-Setup-1.0.0.exe`.
2. **Start Live Stream**: Launch your stream in **TikTok Live Studio** or mobile app.
3. **Connect**: Open TrackCast, enter your TikTok username in the top header, and click **Connect Live**.
4. **Setup OBS Overlay**:
   * Open OBS Studio $\rightarrow$ Add **Browser Source**.
   * Enter the URL: `http://localhost:8969/overlay` (or pick any specific widget from the Studio Designer tab).
   * Set dimensions to `1920 x 1080`.

---

## 💬 Viewer Chat Commands

Viewers in your TikTok Live can interact directly through chat:

| Command | Example | Description |
|---|---|---|
| `!play [Title]` / `!p [Title]` | `!p Night Dancer` | Searches YouTube and adds the song to queue |
| `!p [YouTube Link]` | `!p https://youtu.be/...` | Plays direct YouTube / YouTube Music URL |
| `!cancel` / `!batal` | `!cancel` | Removes the viewer's latest song request |

---

## 📜 License

Distributed under the **MIT License**. Created with ❤️ by **TrackCast Studio**.
