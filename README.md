# 🦊 Fox Security

A lightweight, secure web browser with a local server architecture, built by a 14-year-old developer.

## 🚀 Key Features
* **Ultra-Lightweight Client:** The core interface weighs less than 200 KB (compared to 300+ MB for Chrome).
* **Local Server Architecture:** The backend runs directly on your Android device via Python.
* **Transparent Moderation:** Admins must provide a reason for any ban. Users can see exactly why they were banned, the remaining time, and directly appeal to the admin. No shadowbans.
* **Anti-Bot Protection:** Smart algorithms to prevent spam and abuse.
* **User-First Philosophy:** We don't track your data. Your privacy is our priority.

## 🛠️ Tech Stack
* **Backend:** Python (HTTP Server, JSON database)
* **Frontend:** HTML, CSS, JavaScript
* **Tunneling:** Pinggy (Dynamic Ephemeral Tunnels for security)

## ⚠️ Limitations
* The server runs on a personal Android phone. If the phone runs out of battery or the app is closed, the public link goes offline.
* The public link rotates periodically for security reasons.

## 🗺️ Roadmap
- [ ] Custom animated avatars (GIF)
- [ ] AI Assistant "Erix" for security tips
- [ ] Custom bookmarks on the home screen
- [ ] Cloudflare Tunnel integration for stable URLs

## 🏃‍♂️ How to Run
1. Install **Pydroid 3** on your Android device.
2. Install required libraries (`pip install pyngrok` or use the built-in standard library).
3. Run `fox_browser.py`.
4. Open `http://127.0.0.1:8080` in your browser.
