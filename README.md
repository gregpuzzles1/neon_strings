# Neon Strings 🎵

An interactive music playground that turns taps, swipes, and keystrokes into sound and light.

Play glowing strings, create melodies, and watch colorful waves, ripples, and sparkles respond to your touch.

## Features

- **22 interactive strings** with synthesized musical tones.
- **Seven color themes:** Ocean Blue, Violet, Rose Pink, Ember Red, Sunset Orange, Golden Glow, and Forest Green.
- **Three musical moods:** Moonlight, Daydream, and Deep Space.
- **Touch, mouse, and keyboard controls.**
- **Auto play** for an automatic melody.
- **Adjustable volume** and a sound toggle.
- **Saved color preference** using browser local storage.
- **Responsive layout** for desktop and mobile screens.
- **Reduced-motion support** based on your device settings.
- Matching browser favicon and iPhone Home Screen icon.

## How to Play

1. Click or tap **Enable sound**.
2. Tap a string or drag across the strings to play notes.
3. On a keyboard, use **A, S, D, F, G, H, J, K** to play.
4. Choose a musical mood and color theme.
5. Select **Auto play** to start an automatic melody, or **Pause** to stop it.

**Reset** stops autoplay, clears the visual effects, and returns the volume to **50%**.

Headphones are welcome!

## Built With

- **HTML** for the page structure.
- **CSS** for styling and responsive layouts.
- **JavaScript** for interaction and animation.
- **Canvas API** for the strings, ripples, and particles.
- **Web Audio API** for musical tones and delay effects.
- **Local Storage** for remembering the selected color theme.

No frameworks, package installation, or build step are required.

## Getting Started

Download or clone this repository, then open **index.html** in a modern web browser.

Keep the icon files alongside **index.html** so they can load correctly.

You can also serve the project locally with Python:

```
python3 -m http.server 8000
```

Then open [**http://localhost:8000**](http://localhost:8000/) in your browser.

Audio begins after a user interaction, such as clicking **Enable sound**.

## Project Files

| File | Purpose |
| --- | --- |
| `index.html` | Complete app, including styles and JavaScript |
| `favicon.svg` | Scalable browser icon |
| `favicon.ico` | Browser icon in multiple sizes |
| `favicon-32.png` | 32 × 32 PNG icon |
| `apple-touch-icon.png` | 180 × 180 iPhone Home Screen icon |
| `robots.txt` | Search engine crawling instructions |
| `sitemap.xml` | Homepage URL for search engines |

## Hosting

Neon Strings is a static website and can be hosted on GitHub Pages or another static hosting service.

Before publishing, update **sitemap.xml** to use your website’s final public URL.

## About the Project

Created by **Greg Christian**, with assistance from ChatGPT, and inspired by an interactive glowing-string animation.

The project explores how simple browser technologies can combine music, color, and motion into a playful experience.
