# PyGame Music Player 🎵  
*Simple Console-Based MP3 Player (v0.1 – Initial Release)*

![Python](https://img.shields.io/badge/python-3.8%2B-blue?logo=python&logoColor=yellow)
![PyGame](https://img.shields.io/badge/pygame-2.0%2B-green)
![License](https://img.shields.io/badge/license-MIT-blue)

A minimal, terminal-only MP3 player built with **pygame.mixer**.  
No extra dependencies beyond PyGame — perfect starting point for learning audio playback in Python.

## Current Features
- Automatically scans the `musics/` folder for `.mp3` files
- Displays a numbered playlist
- Play any song by typing its number
- In-song controls:
  - `P` → Pause
  - `R` → Resume
  - `S` → Stop and return to menu
- Quit anytime with `Q`

## Requirements
```bash
pip install pygame
