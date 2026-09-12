# Privacy Policy for TrackCast

**Effective Date:** September 12, 2026  
**Last Updated:** September 12, 2026  

TrackCast ("we", "our", or "the application") is committed to protecting your privacy. This Privacy Policy explains how our application collects, uses, and safeguards your information when you use our desktop application and cloud synchronization services.

---

## 1. Information We Access and Collect

TrackCast is built with a **local-first architecture**. By default, all song requests, playlists, settings, blacklists, and playback histories are stored locally on your own computer.

### Google Account & Google Drive Data (Cloud Backup):
When you voluntarily sign in with Google to enable cloud backup, TrackCast requests access to:
- **Basic Profile Information (`userinfo.profile`, `userinfo.email`)**: Used solely to display your Google profile name, email, and avatar in the TrackCast Settings screen to verify which account is connected.
- **Application-Specific Google Drive Storage (`drive.appdata`)**: Used strictly to read and write your TrackCast configuration files (`settings.json`, `playlists.json`, `blacklists.json`, `queue.json`, `history.json`) inside Google Drive's hidden `appDataFolder`. 
  - TrackCast **CANNOT** access, view, modify, or delete any of your personal Google Drive files, documents, photos, or other application data outside its own dedicated folder.

---

## 2. How We Use Your Information

- To backup and sync your custom playback settings, playlists, blacklists, and request queues across your devices.
- To maintain your authenticated session with Google Drive APIs.
- We do **NOT** sell, rent, monetize, or share your personal information with any third parties or advertisers.

---

## 3. Data Storage & Security

- All authentication tokens are stored locally on your device in secure application data storage.
- All network communications with Google APIs are encrypted via Industry Standard Transport Layer Security (TLS/HTTPS).

---

## 4. User Control & Data Deletion

You retain full control over your data at all times:
- **Disconnect Google Account**: You can sign out of your Google account anytime via the Settings tab in TrackCast.
- **Delete Backups**: Disconnecting or deleting data from TrackCast clears local credentials. You can also delete TrackCast data from your Google Account settings under **Security > Third-party apps with account access**.

---

## 5. Contact Us

If you have questions regarding this Privacy Policy, you can open an issue or reach out via:
- **GitHub Repository**: [https://github.com/ranggaluthfiendi/TrackCast-Release](https://github.com/ranggaluthfiendi/TrackCast-Release)
- **Developer Email**: rangdevio@gmail.com
