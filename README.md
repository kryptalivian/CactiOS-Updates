<img width="1392" height="832" alt="Screenshot 2026-11-02 at 11 35 50 AM" src="https://github.com/user-attachments/assets/b3736f04-f404-42d3-a40b-37f14c620b50" />
<img width="1392" height="832" alt="Screenshot 2026-11-02 at 11 37 02 AM" src="https://github.com/user-attachments/assets/2e55f33a-971c-4613-8fe8-02df32efea72" />
<img width="1392" height="832" alt="Screenshot 2026-11-02 at 11 38 55 AM" src="https://github.com/user-attachments/assets/3aee72f2-6c1e-456e-ba52-214430e95bc6" />
<img width="1392" height="832" alt="Screenshot 2026-11-02 at 11 39 39 AM" src="https://github.com/user-attachments/assets/7e3bf6ac-0151-477a-b8b0-0267a48b7adf" />
<img width="1392" height="832" alt="Screenshot 2026-11-02 at 11 39 50 AM" src="https://github.com/user-attachments/assets/c8b939c9-c240-4316-b8de-1c92d8ee6763" />
<img width="1392" height="832" alt="Screenshot 2026-11-02 at 11 40 22 AM" src="https://github.com/user-attachments/assets/365f82d6-2ab7-4a25-9011-e7b5c478782b" />

Cacti OS

Cacti OS is a modern, controller-first retro gaming front end. It has a console-style interface, RetroAchievements support, and per-player profiles. It scans your ROM folders, scrapes box art, and launches games in emulators. The same interface runs on desktop, as a ready-to-flash Raspberry Pi 5 image, and on Android.

Features
Library: Scans your ROM folders and scrapes box art and metadata. Duplicate regions and multi-disc games are collapsed into one entry, with a toggle to show them all.
Clean up library: Moves files into the right console folder (.nes to NES, .sfc to SNES, and so on). Saves and scraped art move with the game. Anything it can’t identify, such as zips of unknown systems, is left alone.
RetroAchievements: Sign-in, per-game progress, unlock pills during play, hardcore mode, and a points and last-played summary for each player.
Players and profiles: Each player has their own saves, save states and backups, plus a Guest mode that keeps nothing. A “Who’s playing?” screen appears at startup when there’s more than one player.
Visuals: Presets that make the picture look like the original hardware, including aspect ratio, integer scaling and LCD or CRT shaders.
Compare view: Launches a local ROM next to the game page, so you can check a region or revision before playing.
Recomps: Installed recompilation ports appear as their own tab and launch like any other game.
Themes and settings: Several themes, plus icon settings (trophy, friends, header icon size and decluttering).
Platforms
Platform	Notes
Windows, macOS	Electron desktop app
SteamOS	Desktop package for Steam Deck or Linux
Web	Browser build
Raspberry Pi 5	Buildroot-based OS image that boots straight into Cacti OS and grows its data partition on first boot
Android	Native player (libretro cores plus an rcheevos achievements runtime) with the same UI, tested on tablet
Status

Desktop is at v1.12.8, and Android is a debug build at 1.12.8-android14. In progress or planned:

Matching games on RetroAchievements by file hash instead of title.
A save-state manager, which is on hold.
A ScreenScraper developer registration for built-in scraping.
Legal

Cacti OS doesn’t include or download games or BIOS files. Bring your own legally obtained ROMs.# CactiOS-Updates
Updates for the CactiOS Frontend.
