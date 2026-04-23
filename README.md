# Userscript: Video Speed Control

Easily control the playback speed of videos (1x to 5x) using keyboard shortcuts on popular social media and video platforms.

## Installation

-  Install a userscript manager:
   - [Violentmonkey](https://violentmonkey.github.io/) **(Recommended)**
   - [Tampermonkey](https://www.tampermonkey.net/)
-  [Click here to install the script](https://github.com/fahim-ahmed05/userscript-videospeedcontrol/raw/main/videospeedcontrol.user.js)

## Features

- Speed range: **1x to 5x**
- Default speed: **2x**
- Works on:
  - Facebook, Messenger, Instagram, Threads
  - Twitter / X
  - TikTok, Rumble, Patreon, Bitchute
  - Substack, LinkedIn, PreserveTube
- Dynamic overlay displays the current speed
- Automatically applies to newly loaded videos
- Lightweight and privacy-friendly (no tracking, no external dependencies)

## Keyboard Shortcuts

| Action                  |    Chromium    |     Gecko     |
| :---------------------- | :------------: | :-----------: |
| Decrease speed (-0.25x) |    `Alt + 3`   |    `Alt + ,`  |
| Increase speed (+0.25x) |    `Alt + 4`   |    `Alt + .`  |
| Set speed to 1x         |    `Alt + 1`   |   `Ctrl + ,`  | 
| Set speed to 2x         |    `Alt + 2`   |   `Ctrl + .`  |

**Gecko:** Firefox, Floorp, Zen, Other firefox based browsers. <br>
**Chromium:** Chrome, Brave, Vivaldi, Other chrome based browsers.

## How It Works

- Script monitors for video elements and applies the chosen speed.
- Speed persists across newly loaded videos (e.g., infinite scroll).
- Displays a brief on-screen overlay showing the current speed setting.

