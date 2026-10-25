# Shuffle Song Finder

Your iPod renames every song to gibberish like `BXQT.mp3`. Shuffle Song Finder reads the song info hidden inside each file and shows the real title, artist and album. Then you can play, shuffle and skip through them right in your browser.

**Use it:** [sodabro.com/ipod](https://sodabro.com/ipod)

## How to use it

1. Plug in your iPod. It shows up like a USB drive.
2. Open the page and click **Choose iPod folder**.
3. Open your iPod, then `iPod_Control` → `Music`, and click Open.
   - `iPod_Control` is hidden. Show hidden folders with **Ctrl + .** on a Chromebook, **Cmd + Shift + .** on a Mac, or **View → Hidden items** in File Explorer on Windows.

## Features

- Decodes ID3 tags (MP3) and iTunes tags (M4A/AAC)
- Search and sort by artist, song or album
- Shuffle, play/pause, previous/next and ±15 second skip
- Keyboard: Space to play/pause, ←/→ to skip 15 seconds
- Copy your full song list

## Privacy

Everything runs in your browser. Your songs are never uploaded anywhere.

Songs bought from iTunes with copy protection (older `.m4p` files) can be listed but won't play outside iTunes.

## Tech

One self-contained `index.html` with no build step and no dependencies beyond Google Fonts.
