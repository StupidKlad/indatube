# 👀 TubeMusic: Ad-free Kodi Youtube Music client
![License - MIT](https://img.shields.io/badge/License-MIT-orange)
![Kodi Version - 19+ or newer](https://img.shields.io/badge/Kodi_Version-19+-blue)

**TubeMusic** is a YouTube Music ad-free Kodi (XBMC) add-on, powerred by unofficial Yotube Music API.
# 📌 Features
- Search for songs, albums, playlists
- Top charts and trending music
- Personal playlists (if logged)
- Background playback
- Lightweight & fast (no official API needed)
# 📥 Installation
## Method 1: Via Kodi Repository (Recommended)
1. Download the latest `.zip` release.
2. In Kodi:
`Add-ons` → `Install from zip file` → `Select the downloaded file`.

## Method 2: Manual Installation
1. Clone this repo into Kodi's addons folder:
```bash
git clone https://github.com/StupidKlad/tubemusic.git plugin.audio.tubemusic
```
2. Restart Kodi.
# 🛠 Development
## Dependencies
- Python 3.x
- Kodi 19+ (Matrix) or newer
- YouTube Music Unofficial API (`resources/lib/ytmusicapi`)
## TubeMusic Stucture
```
plugin.audio.indatube/  
├── addon.xml            # Addon metadata  
├── plugin.py            # Main plugin logic  
├── resources/  
│   ├── lib/             # InnerTube and other libraries  
│   ├── settings.xml     # User settings  
│   ├── icon.png         # Addon icon
│   └── ...              # Other stuff (screenshots, languages and etc.)
└── LICENSE              # MIT License  
```
## Building for Release
```bash
zip -r plugin.audio.indatube.zip plugin.audio.tubemusic/
```
# 📜 License
**MIT License**
© 2024 StupidKlad
<p>
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
</p>
(The full license text is in LICENSE.)

# 💡 Support & Contributions
- Found a bug? Open an Issue.
- Want to contribute? Submit a Pull Request!
- Need help? Contact me on Telegram: `username`.
