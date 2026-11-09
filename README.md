# Hey iB! — Voice & Android Auto Companion for iBroadcast

**Hey iB!** is an independent third-party companion application designed to provide advanced offline voice search, smart classical/box-set disambiguation, and seamless Android Auto integration for [iBroadcast](https://ibroadcast.com).

> *Note: Hey iB! is an independent companion app created by RAD. It is not officially affiliated with, endorsed, or sponsored by iBroadcast Media LLC.*

---

## 📱 Features
* **Offline Voice Recognition:** Powered by Vosk for fast, private wake-word detection in vehicles.
* **Android Auto Integration:** Full MediaSession3 playback, custom voice actions, and a 3-album art collage display mode.
* **Smart Voice Trainer (`🎓 Teach`):** Easily teach the app custom pronunciations and aliases for tricky classical composers and multi-CD box sets.
* **Local Caching:** SQLite database caching for lightning-fast library lookups.

---

# Privacy Policy

**Last updated:** November 9, 2026

This Privacy Policy describes how **Hey iB!** ("we", "our", or "us") handles information when you use our mobile application.

### 1. Information We Collect and Process
* **Microphone Audio (Ephemeral):** Hey iB! accesses your device microphone solely to capture spoken voice commands (e.g., *"Play Bach Cantatas"*). Voice audio is processed locally on your device via the Vosk speech recognition engine. We do not store, record, transmit, or upload your voice audio to any external servers.
* **iBroadcast Account Credentials & Authentication:** When you sign in using iBroadcast OAuth 2.0, your authentication tokens (`access_token` and `refresh_token`) are stored securely and exclusively in local device storage (`EncryptedSharedPreferences` / app-private storage). These tokens are used solely to communicate directly with official iBroadcast streaming APIs (`api.ibroadcast.com`) to retrieve your music library and stream tracks.
* **Local Library Data:** Your music catalog metadata (tracks, albums, artists) is cached locally in an on-device SQLite database to enable instant search indexing. This data never leaves your device.

### 2. Third-Party Services
Hey iB! communicates directly with **iBroadcast** APIs using your credentials. We do not integrate third-party analytics trackers, advertising networks, or data brokers.

### 3. Data Security
All network communications between Hey iB! and iBroadcast servers use encrypted HTTPS/TLS connections. OAuth tokens and local cache files remain sandboxed within the application-private directory on your Android device.

### 4. Children’s Privacy
Hey iB! does not knowingly collect or solicit personal information from anyone under the age of 13.

### 5. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Any changes will be posted on this page with an updated revision date.

### 6. Contact Us
If you have any questions or suggestions about this Privacy Policy, please open an issue on our GitHub repository or contact us.

---

## ⚖️ Legal & Trademarks
* **iBroadcast®** and the "Powered by iBroadcast" badge are registered trademarks of iBroadcast Media LLC.
* **Vosk** is licensed under the Apache License 2.0 (Alpha Cephei Inc.).
* **ExoPlayer / AndroidX Media3** is licensed under the Apache License 2.0 (The Android Open Source Project).
