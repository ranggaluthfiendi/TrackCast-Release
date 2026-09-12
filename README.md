# TrackCast

<p align="center">
  <img width="1280" height="760" alt="TrackCast Main Dashboard" src="https://github.com/user-attachments/assets/30d9d73c-ba51-4d08-ad64-32b13e9e77d1" />
</p>

<p align="center">
  <strong>Interactive TikTok Live & YouTube Music Song Request Player with Synced Lyrics, Video Player & OBS Overlays</strong>
</p>

<p align="center">
  <a href="https://github.com/ranggaluthfiendi/TrackCast-Release/releases/latest"><img src="https://img.shields.io/github/v/release/ranggaluthfiendi/TrackCast-Release?style=for-the-badge&color=00d2de" alt="Latest Release"></a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2B-blue?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

---

## Download TrackCast for Windows

Click the link below to get the official installer:

👉 **[Download TrackCast Setup v1.2.0 (.exe)](https://github.com/ranggaluthfiendi/TrackCast-Release/releases/latest/download/TrackCast-Setup-1.2.0.exe)**


---

## Features

- ☁️ **Google Drive Cloud Sync**: Backup and restore settings, playlists, blacklists, and song request history directly to your Google Account.
- 🌐 **Cloud Widgets Relay**: Zero-configuration HTTPS overlay URLs with instant SSL certificates for **TikTok LIVE Studio** and **OBS Studio**.
- 🔴 **Zero-Setup TikTok Live Connection**: Connect simply by entering your `@username` without developer tokens or paid APIs.
- 🎧 **High-Quality Playback**: Fast YouTube search, auto-resolution management, and clean borderless video player.
- 🎤 **Word-by-Word Synced Lyrics**: Real-time karaoke lyrics powered by NetEase, QQ Music, Kugou, and LRCLIB with dual subtitle translations (English, Indonesian, Japanese, Korean, Chinese, and Romaji).
- 🖥️ **7 Dedicated Stream Overlays**:
  - **Video Player** (`/overlay/video`): Borderless live video overlay with synced progress.
  - **Lyrics** (`/overlay/lyrics`): Real-time karaoke lyrics with particle effects.
  - **Queue** (`/overlay/queue`): Live request queue list with avatars.
  - **Now Playing** (`/overlay/now-playing`): Album art card with rotating vinyl disc.
  - **Alert Toast** (`/overlay/alert`): Notification toast when new songs are requested.
  - **Compact Ticker** (`/overlay/compact`): Bottom marquee bar.
  - **Timeline** (`/overlay/timeline`): Previous, current, and upcoming track cards.
- 🎨 **Studio Overlay Designer**: Interactive live stage preview to customize themes, colors, fonts, borders, and aspect ratios.
- 🛡️ **Anti-Spam & Fair Queue**: Viewer request limits, cooldown timers, permissions (followers, subscribers, moderators), and customizable blacklists.
- 🌐 **Bilingual Support**: Native English (EN) and Indonesian (ID) language support.

---

## Interface Showcase

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

## Quick Start

1. **Install Application**: Download and run `TrackCast-Setup-1.2.0.exe`.
2. **Start Live Stream**: Start streaming in **TikTok LIVE Studio** or mobile app.
3. **Connect**: Open TrackCast, enter your TikTok username in the top bar, and click **Connect Live**.
4. **Setup Overlay**:
   - In OBS Studio or TikTok LIVE Studio, add a **Browser Source** (or *Custom Link*).
   - Paste the widget URL from the **Links Hub** or **Studio Designer**.
   - Set resolution to `1920 x 1080` (landscape) or `1080 x 1920` (portrait).

---

## Viewer Chat Commands

| Command | Example | Description |
|---|---|---|
| `!play [Title]` / `!p [Title]` | `!p Night Dancer` | Searches and adds song to queue |
| `!play [YouTube Link]` | `!p https://youtu.be/...` | Plays direct YouTube link |
| `!skip` / `!next` | `!skip` | Votes to skip the current song |
| `!cancel` / `!batal` | `!cancel` | Removes the viewer's latest request |

---

## Privacy & Terms

- [Privacy Policy](https://github.com/ranggaluthfiendi/TrackCast-Release/blob/main/PRIVACY.md)
- [Terms of Service](https://github.com/ranggaluthfiendi/TrackCast-Release/blob/main/TERMS.md)

---

## License

Distributed under the **MIT License**. Created by **TrackCast Studio**.
