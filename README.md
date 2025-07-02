# YouTube Auto Speed

**Automatically adjusts playback speed on YouTube videos (excluding music videos).**

---

## Features

- Sets default playback speed to **1.25x**.
- Detects and **excludes music videos** from speed changes.
- Supports a **blacklist of channels** to skip.
- Works with YouTube’s **single-page app (SPA) navigation**.
- Lightweight and minimal console logs for easy debugging.

---

## Installation

1. Install a userscript manager like [Tampermonkey](https://www.tampermonkey.net/) or [Violentmonkey](https://violentmonkey.github.io/).
2. [Download the latest script here](https://github.com/teperyaemo/youtube-auto-speed/raw/main/youtube-auto-speed.user.js).
3. Open the script link and install it in your userscript manager.
4. Enjoy automatic speed adjustment on YouTube!

---

## Configuration

### Blacklist

You can add YouTube channel IDs to the blacklist to prevent the script from changing playback speed on those channels.

To add channels to the blacklist:

- Open your browser console on YouTube (usually F12 or Ctrl+Shift+I).
- Run:

```js
localStorage.setItem('yt_auto_speed_blacklist', 'CHANNEL_ID1,CHANNEL_ID2');
```

- Replace CHANNEL_ID1,CHANNEL_ID2 with actual channel IDs separated by commas.
- Reload the page.

## Contributing
Feel free to open issues or pull requests on the GitHub repository.

## License
This project is licensed under the MIT License.

## Author
Developed by teperyaemo

---
