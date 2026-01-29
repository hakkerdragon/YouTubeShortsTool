[README.md](https://github.com/user-attachments/files/24950112/README.md)
# 🎬 YouTubeShortsTool

<div align="center">

![macOS](https://img.shields.io/badge/macOS-14.0%2B-blue)
![Swift](https://img.shields.io/badge/Swift-5.9-orange)

A powerful macOS app to download, slow down, and reverse YouTube Shorts with ease.

<img src="Screenshot 2026-01-29 at 5.49.31 PM.png" alt="YouTubeShortsTool Screenshot" width="600"/>

</div>

## ✨ Features

- 📥 **Download YouTube Shorts** - Paste a Shorts URL and download instantly
- 🐢 **Slow Motion** - Adjust playback speed from 0.25x to 2x
- 🔄 **Reverse Video** - Play any Short in reverse direction
- 🎬 **Combine Effects** - Apply speed changes AND reversal together
- 📂 **Custom Output** - Choose your save location

## 🚀 Installation

1. Download `YouTubeShortsTool.dmg` from the [Releases](https://github.com/YOUR_USERNAME/YouTubeShortsTool/releases) page
2. Open the DMG
3. Drag **YouTubeShortsTool.app** to your Applications folder
4. Launch from Applications or Spotlight

## 📖 Usage

1. **Paste a YouTube Shorts URL**
   ```
   https://youtube.com/shorts/dQw4w9WgXcQ
   ```

2. **Adjust Settings**
   - Select playback speed (0.25x, 0.5x, 0.75x, 1x, 1.25x, 1.5x, 2x)
   - Toggle "Reverse Video" if desired
   - Choose output folder

3. **Download** - Your processed video is ready!

## 🛠️ Requirements

- macOS 14.0 (Sonoma) or later
- Apple Silicon or Intel Mac
- Homebrew (for dependencies)

## 🔧 Install Dependencies

```bash
brew install yt-dlp ffmpeg
```

## 📁 Project Structure

```
YouTubeShortsTool/
├── YouTubeShortsTool.xcodeproj/
├── YouTubeShortsTool/
│   ├── YouTubeShortsToolApp.swift    # App entry point
│   ├── ContentView.swift              # Main UI
│   ├── VideoProcessor.swift           # Video processing
│   ├── Models.swift                   # Data models
│   └── Assets.xcassets/               # App icons
├── setup_dependencies.sh              # Dependency installer
├── create_dmg.sh                      # DMG creator
├── clean_build.sh                     # Clean build script
└── README.md                          # This file
```

## 🙏 Acknowledgments

- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - YouTube video downloading
- [FFmpeg](https://ffmpeg.org/) - Video/audio processing

---

<div align="center">

**Made with ❤️ for the YouTube Shorts community**

⭐ Star this repo if you found it useful!

</div>
