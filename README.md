# 🎵 TrackCast

<p align="center">
  <img width="1280" height="760" alt="TrackCast Main Dashboard" src="https://github.com/user-attachments/assets/30d9d73c-ba51-4d08-ad64-32b13e9e77d1" />
</p>

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

👉 **[Download TrackCast Setup v1.2.0 (.exe)](https://github.com/ranggaluthfiendi/TrackCast-Release/releases/latest/download/TrackCast-Setup-1.2.0.exe)**

*(Or visit all versions on the [Releases Page](https://github.com/ranggaluthfiendi/TrackCast-Release/releases))*

---

## ✨ Features

* ☁️ **Google Drive Cloud Sync**: Seamlessly backup and restore your settings, playlists, blacklists, and song request queue to Google Drive.
* 🔴 **Zero-Setup TikTok Live Connection**: Connect simply by entering your `@username`. No developer tokens or paid APIs required.
* 🎧 **High-Quality YouTube Playback**: Instant search and automatic high-resolution audio queue playback.
* 🎤 **Word-by-Word Synchronized Karaoke Lyrics**: Accurate real-time lyrics powered by NetEase, QQ Music, Kugou, and LRCLIB.
* 🌐 **Dual Subtitle Multi-Language Translations**: Real-time translation to English, Indonesian, Japanese, Korean, and Chinese with Romaji support.
* 🖥️ **6 Dedicated OBS & TikTok LIVE Studio Overlays**:
  * **Overlay Lyrics** (`/overlay/lyrics`): Cinematic karaoke lyrics.
  * **Overlay Queue** (`/overlay/queue`): Live request queue list with avatars.
  * **Overlay Now Playing** (`/overlay/now-playing`): Sleek album card with rotating vinyl disc.
  * **Overlay Alert** (`/overlay/alert`): Toast notifications when songs are added.
  * **Overlay Compact Ticker** (`/overlay/compact`): Bottom ticker marquee.
  * **Overlay Timeline** (`/overlay/timeline`): Previous / Now / Next preview cards.
* 🛡️ **Anti-Spam & Fair Queue System**: Built-in viewer request limits, cooldowns, and customizable term/song/user blacklists.

---

## 📸 Interface Showcase

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <strong>🎨 Studio Overlay Designer</strong><br><br>
      <img src="https://github.com/user-attachments/assets/c451f4f9-aae6-4e83-a19e-0bfd992abc33" width="100%" alt="Studio Overlay Designer" />
    </td>
    <td width="50%" align="center">
      <strong>🎤 Player & Synced Karaoke Lyrics</strong><br><br>
      <img src="https://github.com/user-attachments/assets/c2db2f38-f564-4813-af67-c7b44c8df369" width="100%" alt="Player & Synced Lyrics" />
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <strong>💬 TikTok Live Chat & Queue</strong><br><br>
      <img src="https://github.com/user-attachments/assets/8ecc18b3-79a3-4fe1-b85d-649f1591925a" width="100%" alt="TikTok Live Request Queue" />
    </td>
    <td width="50%" align="center">
      <strong>☁️ Google Cloud Backup & Sync</strong><br><br>
      <img src="https://github.com/user-attachments/assets/af4905e9-92b1-4472-a6f9-7e0d8448b7a6" width="100%" alt="Cloud Backup & Settings" />
    </td>
  </tr>
</table>

---

## 🚀 Quick Start Guide

1. **Install Application**: Download and run `TrackCast-Setup-1.2.0.exe`.
2. **Start Live Stream**: Launch your stream in **TikTok LIVE Studio** or mobile app.
3. **Connect**: Open TrackCast, enter your TikTok username in the top header, and click **Connect Live**.
4. **Setup OBS / TikTok LIVE Studio Overlay**:
   * Open OBS Studio $\rightarrow$ Add **Browser Source** (or *Custom Link* in TikTok LIVE Studio).
   * Enter the widget URL from the Links Hub
   * Set dimensions to `1920 x 1080` (or `1080 x 1920` for portrait mode).

---

## 💬 Viewer Chat Commands

Viewers in your TikTok Live can interact directly through chat:

| Command | Example | Description |
|---|---|---|
| `!play [Title]` / `!p [Title]` | `!p Night Dancer` | Searches YouTube and adds the song to queue |
| `!p [YouTube Link]` | `!p https://youtu.be/...` | Plays direct YouTube / YouTube Music URL |
| `!cancel` / `!batal` | `!cancel` | Removes the viewer's latest song request |

---

## 🔒 Privacy & Terms

- [Privacy Policy](https://github.com/ranggaluthfiendi/TrackCast-Release/blob/main/PRIVACY.md)
- [Terms of Service](https://github.com/ranggaluthfiendi/TrackCast-Release/blob/main/TERMS.md)

---

## 📜 License

Distributed under the **MIT License**. Created with ❤️ by **TrackCast Studio**.
