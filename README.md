# Desktop-Music-player



```markdown
# 🎵 PyQt5 Music Player

A modern, cross-platform music player built with **Python**, **PyQt5**, and **Pygame Mixer**.  
It features a sleek UI, playlist management, album art display, and intuitive controls.

---



---

## ✨ Features

- 🎼 Play, Pause, Next, Previous controls  
- 📂 Playlist management (`.m3u` support)  
- 🎨 Custom icons and cover art display  
- 🔊 Volume control with dynamic icons  
- 🏷️ Audio metadata extraction (Title, Artist, Album)  
- 📦 Cross-platform support (Windows, macOS, Linux)  
- 🧪 Unit tests for key components

---

## 📦 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/music_player.git
cd music_player
````

### 2️⃣ Create a virtual environment (optional but recommended)

```bash
python -m venv venv
# Activate:
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

Run the application:

```bash
python main.py
```

The music player will launch with:

* Default cover art if no album art metadata is found
* Local icons for controls
* Playlist loaded from `playlists/default.m3u`

---

## 🛠 Dependencies

Main Python packages:

* **PyQt5** → UI framework
* **pygame** → Audio playback (mixer)
* **mutagen** → Audio metadata handling
* **Pillow** → Image processing

Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

## 📁 Assets

The app uses **local assets** for consistent UI:

* `assets/icons/` → All control and volume icons
* `assets/images/` → Cover art placeholder and app icon

You can replace these with your own PNG files to customize the look.

---

## 🧪 Testing

Run unit tests:

```bash
pytest tests/
```

Tests cover:

* Audio playback functions (`test_player.py`)
* Metadata extraction (`test_metadata.py`)

---

## 📝 License

This project is licensed under the **MIT License** — feel free to modify and distribute it.

---

## 💡 Future Improvements

* 🎚️ Equalizer support
* 🌙 Dark/Light theme toggle
* 📡 Streaming audio support
* 🎤 Lyrics display

---

**Author:** amar
📧 Contact: [amaranarayana363@gmail.com](mailto:you@example.com)

```

---

If you want, I can now also give you the **`requirements.txt`** for this project so your GitHub repo is fully ready to run without dependency issues.
```
