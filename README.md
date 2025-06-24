# 🌙 Lunaria

**Lunaria** is an elegant, torrent-powered streaming platform for movies, TV shows, and anime. Built with FastAPI and React, it brings together beautiful design, instant magnet streaming, and open APIs — all in one seamless experience.

---

## 📌 Features (Initial Phase)
- 🔍 Search for movies and TV shows using TMDB API
- 🔁 Fetch IMDb ID from TMDB
- 🧲 Retrieve magnet links via Torrentio API (movies + shows)
- 🎥 Stream torrents using a local or browser-based engine
- 💬 Subtitle support (coming soon)
- 🧠 Smart episode-to-episode playback (planned)
- 🧷 Continue Watching via local storage

---

## 🧪 Tech Stack

| Layer     | Technology          |
|-----------|---------------------|
| Backend   | FastAPI, Python, TMDB API, Torrentio |
| Frontend  | React.js (WIP)      |
| Streaming | WebTorrent / Libtorrent (Planned) |
| Subtitles | OpenSubtitles API (Planned) |

---

## 🚀 Getting Started (Backend)

### 📦 Setup

```bash
git clone https://github.com/your-username/lunaria.git
cd lunaria/backend

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
