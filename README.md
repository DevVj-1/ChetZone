# ChetZone
💬 Free real-time chat for South Asia — no registration, Firebase-powered, city &amp; state search, group creation

# 💬 ChatZone — Free Real-Time Chat for South Asia

A free, no-registration chat website for users from **India, Bangladesh, Pakistan, and Nepal** — powered by Firebase Realtime Database.

## ✨ Features

- ⚡ **Real-time chat** between real online users (Firebase powered)
- 🔍 **City & State search** — find people from your exact city (e.g. Kota, Rajasthan)
- 👥 **City Groups** — create or join groups for your city, college, or interest
- 🌏 **South Asia only** — India 🇮🇳, Bangladesh 🇧🇩, Pakistan 🇵🇰, Nepal 🇳🇵
- 🔒 **No registration** — just pick a username and start chatting
- 💾 **No database for users** — zero data stored, 100% session-based
- 📱 **Mobile responsive** — works on phone, tablet, and desktop

## 🚀 Live Demo
> [your-site.netlify.app](https://your-site.netlify.app)

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, Vanilla JavaScript |
| Real-time | Firebase Realtime Database |
| Hosting | Netlify / Vercel (free) |
| Auth | None (no login required) |

## ⚙️ Setup

1. Clone this repo
2. Go to [console.firebase.google.com](https://console.firebase.google.com) → create a project
3. Enable **Realtime Database** (test mode)
4. Copy your **Web App config** and paste it into `index.html` inside `FIREBASE_CONFIG`
5. Set Firebase Rules to `".read": true, ".write": true`
6. Deploy `index.html` to [Netlify](https://netlify.com) or [Vercel](https://vercel.com)

## 📁 Project Structure
```
chatzone/
└── index.html   ← entire app in one file
```

## 🔐 Firebase Rules (for testing)
```json
{
  "rules": {
    ".read": true,
    ".write": true
  }
}
```

## 📌 Topics
`chat` `firebase` `realtime-chat` `india` `bangladesh` `pakistan` `nepal` `no-registration` `free-chat` `south-asia`
```

---

**GitHub Topics/Tags** to add to your repo (boosts discoverability):
```
chat  firebase  realtime  india  bangladesh  pakistan  nepal  free-chat  html  vanilla-js
