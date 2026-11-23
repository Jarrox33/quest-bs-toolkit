# quest-bs-toolkit
All-in-one animated neon Termux launcher for standalone Meta Quest Beat Saber tools—runs Mashup/Shaffuru Medley Cutter, Map Speed-Up, HitScoreVisualizer Randomizer, Auto-Playlists, and Void Platform Converter from one menu.
# Quest Beat Saber Termux Toolkit (`bs_toolkit.py`)

An all-in-one interactive terminal dashboard with an animated neon banner for launching standalone Meta Quest Beat Saber tools directly in **Termux**—no PC required.

## Included Tools
1. **Mashup & Shaffuru Medley Cutter (`mashup_cutter.py`)**
2. **Map Speed-Up / Slow-Down Generator (`speedup.py`)**
3. **HitScoreVisualizer Neon Randomizer (`hsv_random.py`)**
4. **Auto-Playlist Builder (`make_playlists.py`)**
5. **Void Platform `.plat` → `.qplat` Converter (`void-converter`)**

## Prerequisites
* **Beat Saber** modded with **SongCore**
* **Termux** + **Hacker's Keyboard** (enabled in Android Language & Input settings so **Enter** works)
* **Python**, **`wheel` / `setuptools`**, and **`ffmpeg`** installed in Termux

## Setup & Quick-Launch Shortcut
1. Install Python, `ffmpeg`, and build tools in Termux:
   ```bash
   termux-setup-storage
   pkg update -y && pkg install -y python ffmpeg
   pip install --upgrade pip setuptools wheel
