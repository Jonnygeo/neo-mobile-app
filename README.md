# 📱 NeoLegacy Mobile App

<p align="center">
  <a href="https://neo-shade.com">
    <img src="https://neo-shade.com/wp-content/uploads/2025/07/NeoLegacyBanner.jpg" height="180">
  </a>
</p>

> **"Hold your legacy in your hand. Speak it. Hear it. Protect it."**

The **NeoLegacy Mobile App** is the portable, secure interface for managing your digital legacy from anywhere. Built for parents, visionaries, and seekers of truth, this app syncs with your NeoLegacy Vault, AI messages, and encrypted memory timeline.

---

## 📲 Core Features

- 🔐 **Biometric Login** (Face ID / Fingerprint)
- 🧠 **AI Agent Chat** with personalized memory
- 🎥 **Upload Video Confessions** or messages
- 🔁 **Schedule Delivery** of legacy items (death triggers, birthdays, etc.)
- 🗂️ **Browse Vault** of photos, files, and voice recordings
- 🔔 **Push Notifications** for time-based events or agent messages

---

## 🧰 Tech Stack

| Layer         | Tech Used                                |
|--------------|-------------------------------------------|
| Frontend     | React Native / Expo                       |
| Auth         | Firebase Auth + SOVN Token-Gated Access   |
| Storage      | Firestore + Arweave                       |
| AI Agent     | NeoVoice + ElevenLabs                     |
| Backend API  | Firebase Functions / Node                 |
| Notifications| Expo Push API                             |

---

## 🧩 Connected Modules

| Module              | Role                                                    |
|---------------------|---------------------------------------------------------|
| `NeoLegacy-Vault-Core` | Pulls encrypted legacy data                          |
| `neo-msg-deliver`   | Schedules and delivers time-based messages              |
| `neo-voice-core`    | Converts text to spoken memory via ElevenLabs           |
| `neo-crypto-guard`  | Manages auth and wallet access                          |
| `NeoLegacy`         | Master dashboard to sync all activity                   |

---

## 🚀 Setup Instructions

```bash
git clone https://github.com/Jonnygeo/neo-mobile-app.git
cd neo-mobile-app
npm install
npx expo start
