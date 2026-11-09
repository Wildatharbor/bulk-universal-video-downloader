# 📥 Bulk Universal Video Downloader

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=16,1,22&height=210&section=header&text=Bulk%20Universal%20Video%20Downloader&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Download%20Videos%20from%201%2C000%2B%20Sites%2C%20in%20Bulk&descAlignY=56&descSize=17" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-4.5.0-8338EC?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Platform](https://img.shields.io/badge/Windows%20%7C%20Linux%20%7C%20macOS-3A86FF?style=for-the-badge&logo=linux&logoColor=white)](https://github.com)
[![License](https://img.shields.io/badge/license-MIT-FF006E?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Sites](https://img.shields.io/badge/sites-1%2C000%2B-FFBE0B?style=for-the-badge&logo=youtube&logoColor=black)](https://github.com)

<br/>

### ⚡ A powerful, cross-platform downloader for videos from almost any website

*🎯 Bulk Queue • 🎬 4K & 8K • 🎵 Audio Extract • ⚡ Multi-Threaded • 🖥️ GUI + CLI*

<br/>

<a href="https://share.google/idkgao7LhwfpGUxR4">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD_APP-8338EC?style=for-the-badge&logo=download&logoColor=white&labelColor=5F23B8" alt="Download App" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/idkgao7LhwfpGUxR4">
  <img src="https://img.shields.io/badge/🚀_QUICK_START-3A86FF?style=for-the-badge&logo=rocket&logoColor=white&labelColor=1E5FCC" alt="Quick Start" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/idkgao7LhwfpGUxR4">
  <img src="https://img.shields.io/badge/📚_DOCS-FF006E?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=CC0058" alt="Docs" height="45"/>
</a>

</div>

<img width="1200" height="750" alt="standard" src="https://github.com/user-attachments/assets/908fe997-dd1d-4d9d-abc1-5946aedd1ea7" />

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 Overview

**Bulk Universal Video Downloader** is a fast, reliable tool that downloads videos from **over 1,000 supported websites** — in bulk. Paste a list of URLs (or a playlist link), choose your quality, and let the app handle the rest: parallel downloads, automatic retries, format conversion, and organized output folders.

Built on top of battle-tested download engines, it handles everything from YouTube playlists to self-hosted video sites with ease.

> ⚠️ **Legal disclaimer:** This tool is intended for **downloading content you own or have explicit permission to download**, such as your own uploads, public-domain media, or Creative Commons videos. Downloading copyrighted content without authorization may violate the terms of service of the source website and local copyright law. **Use responsibly.**

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🎯 **Bulk Queue** | 🎬 **Up to 8K** | 🎵 **Audio Extract** |
|:---:|:---:|:---:|
| Add 100+ URLs<br/>at once | Full quality range<br/>from 144p to 8K | Extract MP3, M4A<br/>or FLAC audio |

| ⚡ **Multi-Threaded** | 📁 **Auto Organize** | 🖥️ **GUI + CLI** |
|:---:|:---:|:---:|
| Download multiple<br/>videos in parallel | Sort by site, date<br/>or playlist | Point-and-click app<br/>or terminal power |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Downloader

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🌍 **1,000+ Sites** | YouTube, Vimeo, TikTok, Twitch, Dailymotion, and hundreds more |
| ⚡ **Parallel Downloads** | Download 10 videos simultaneously with per-file speed control |
| 🔄 **Auto-Resume** | Interrupted downloads resume exactly where they stopped |
| 🎨 **Clean UI** | Beautiful GUI for beginners, powerful CLI for automation |
| 🔐 **No Ads, No Tracking** | Fully local processing — no accounts, no telemetry |
| 📦 **Batch Conversion** | Convert formats and resize videos without extra tools |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 App Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  📥  Bulk Universal Downloader  v4.5.0           ║
╠══════════════════════════════════════════════════╣
║  📋 Queue: 12 videos                             ║
║  ──────────────────────────────────────────      ║
║  ✅ Video 1: "Tutorial"    1080p   [done]        ║
║  ✅ Video 2: "Review"      4K     [done]        ║
║  ⏳ Video 3: "Documentary" 2160p  62% ▲ 24MB/s   ║
║  ⏳ Video 4: "Interview"   1080p  41% ▲ 18MB/s   ║
║  ⏳ Video 5: "Live Set"    720p   28% ▲ 12MB/s   ║
║  ⏸️ Video 6: "Recap"       waiting              ║
║  ──────────────────────────────────────────      ║
║  📊 Total: 12  ✅ 4 done  ⏳ 5 in progress        ║
║  📁 Output: ~/Downloads/bulk-2026-11-09/         ║
║  ⚡ 5 parallel threads   🎵 Audio: MP3 320k      ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
📥 bulk-universal-video-downloader/
├── 🎯 src/
│   ├── downloader/            # Core download engine
│   │   ├── queue.py
│   │   ├── worker.py
│   │   └── retry.py
│   ├── resolver/              # Site detection & extractors
│   ├── converter/             # FFmpeg wrappers
│   ├── gui/                   # Desktop interface
│   └── cli/                   # Command-line tool
├── 🎨 assets/                 # Icons & themes
├── 🧪 tests/                  # Unit & integration
└── 📖 docs/                   # Supported sites & usage
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![yt-dlp](https://img.shields.io/badge/yt--dlp-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)
![Qt](https://img.shields.io/badge/Qt_6-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a site that isn't supported? Want a new feature?

<div align="center">

<a href="https://share.google/idkgao7LhwfpGUxR4">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/idkgao7LhwfpGUxR4">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-8338EC?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/idkgao7LhwfpGUxR4">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-FFBE0B?style=for-the-badge&logo=github&logoColor=black" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.


<br/>

<div align="center">

### 📥 Made with ⚡ by the Bulk Downloader Team

*If this app saved you time — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=16,1,22&height=120&section=footer" width="100%"/>

</div>
