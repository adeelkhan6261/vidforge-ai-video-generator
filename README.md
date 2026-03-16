# VidForge Pro 🚀

VidForge Pro is a **local AI video generator** that automatically creates complete videos from a simple topic.

It uses **AI script generation, text-to-speech voiceover, stock footage, subtitles, and FFmpeg video rendering** to produce ready-to-upload videos.

Everything runs **locally on your computer** with **zero monthly cost**.

---

## ✨ Features

* 🧠 **AI Script Generator**
* 🔊 **Multi TTS Engine**

  * Edge TTS
  * Google TTS
  * Offline TTS (pyttsx3)
* 🎬 **Automatic Video Creation**
* 🖼 **Stock Footage Support (Pexels API)**
* 📝 **Automatic Subtitles**
* 🎞 **FFmpeg Video Rendering**
* 🌐 **Local Web Interface**
* 💰 **Zero monthly cost**

---

## 🖥 Requirements

Before running the project make sure you have:

* Python 3.10+
* FFmpeg installed
* Internet connection (for Pexels & TTS)

Optional:

* Ollama (for local AI script generation)

---

## 📂 Project Structure

```
vidforge-hotfix/
│
├── vidforge_server_v23.py   # Backend server
├── vidforge_ui.html         # Web interface
├── START_SERVER_V23.bat     # Start server script
├── output/                  # Generated videos
├── temp/                    # Temporary files
└── README.md
```

---

## ⚙️ Installation

1. Clone the repository

```
git clone https://github.com/yourusername/vidforge-pro.git
```

2. Open project folder

```
cd vidforge-pro
```

3. Install dependencies

```
pip install -r requirements.txt
```

4. Install FFmpeg

Verify installation

```
ffmpeg -version
```

---

## ▶ Running the Project

Start the backend server:

```
python vidforge_server_v23.py
```

Or simply double click:

```
START_SERVER_V23.bat
```

Then open the interface:

```
vidforge_ui.html
```

---

## 🎬 How It Works

1. Enter a **topic**
2. AI generates the **script**
3. TTS generates the **voiceover**
4. Pexels fetches **video clips**
5. FFmpeg assembles the **final video**

The generated video will be saved in:

```
output/
```

---

## 📦 Example Use Case

Generate videos for:

* YouTube automation channels
* TikTok / Shorts
* Educational content
* Facts & storytelling videos

---

## ⚠ Disclaimer

This project is intended for **educational and research purposes only**.

---

## 👨‍💻 Author

Created by **Adeel**

If you like this project ⭐ consider giving it a star on GitHub.
