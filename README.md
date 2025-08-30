# Circle FTP Playlist Maker (Lite)

A lightweight **Tampermonkey/Greasemonkey userscript** for CircleFTP that generates XSPF playlists with optional **season filtering**.  
Optimized for **low-end systems** by minimizing UI and resource usage.  

---

## ✨ Features
- Detects and collects **media links** (`.mp4`, `.mkv`, `.avi`, `.mov`, `.webm`)
- Option to export **all seasons** or a specific season
- Generates **XSPF playlist** (compatible with VLC, Kodi, etc.)
- Auto UI injection when media is detected
- Works on both:
  - `http://15.1.1.50/*`
  - `http://new.circleftp.net/*`
---
## 🖼️ Script In Action
<img width="1365" height="767" alt="screenshot-1756534340004" src="https://github.com/user-attachments/assets/ec978776-b5ed-4960-96e2-f59608221029" />

---

## 📦 Installation
1. Install [Tampermonkey](https://www.tampermonkey.net/) (or Violentmonkey/Greasemonkey).
2. [Click here to install the script](userscript/circle-ftp-playlist-maker-lite.user.js?raw=1).
3. Visit CircleFTP and a small UI will appear (bottom-right) if media is found.

---

## ⚙️ Usage
- Click **Download** → generates an `.xspf` playlist.
- Use the dropdown to choose:
  - `All Seasons`
  - `Season 1`, `Season 2`, etc.
- Playlist is automatically saved.

More detailed instructions: [docs/usage.md](docs/usage.md)
