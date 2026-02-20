<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=200&section=header&text=ScriptsLibrary%20V2.1&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Auto%20Bounty%20%7C%20Blox%20Fruits&descAlignY=60&descColor=aaaaaa" width="100%"/>

<br/>

[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/JP72Sz2CNU)
![Version](https://img.shields.io/badge/Version-V2.1-orange?style=for-the-badge)
![Game](https://img.shields.io/badge/Game-Blox%20Fruits-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![Key](https://img.shields.io/badge/Key%20System-None-blue?style=for-the-badge)

</div>

---

## 📌 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [Skill Settings](#-skill-settings)
- [Discord](#-discord)
- [Copyright](#-copyright--legal)

---

## 🧾 About

**ScriptsLibrary V2.1** is a fully featured **Auto Bounty** script for **Blox Fruits** built with a clean [Rayfield](https://github.com/SiriusSoftwareLtd/Rayfield) GUI. Every setting is adjustable in real time — no editing config files, no key system, no hassle. Just inject, configure, and start farming.

> ⚠️ **For educational purposes only. Use at your own risk. We are not responsible for any bans or consequences resulting from the use of this script.**

---

## ✨ Features

### 🎮 General
| Feature | Description |
|---|---|
| **No Key System** | Inject and run instantly — zero authentication required |
| **Info Screen** | Live HUD showing bounty earned, time elapsed, and current bounty |
| **White Screen Mode** | Disables 3D rendering for maximum performance & low CPU |
| **Bypass Teleport** | Intelligently bypasses teleport detection systems |
| **Race V3 / V4 Support** | Automatically activates Race V3 (`T`) and V4 (`Y`) transforms in combat |
| **Skip Race V4 Users** | Optionally skips targeting players with Race V4 active |
| **Server Hopping** | Auto-hops to a new server when no valid targets are found |
| **Webhook Support** | Sends Discord webhook notifications for kills, hops, and session start |
| **Chat Spam** | Optional configurable chat message spam |
| **Config Saving** | All settings automatically saved and restored between sessions |

### 🎯 Auto Bounty
| Feature | Description |
|---|---|
| **Auto Target** | Automatically finds and locks onto the nearest valid bounty target |
| **Min / Max Bounty Filter** | Only targets players within your specified bounty range |
| **Safe Health Threshold** | Stops attacking and retreats when your HP drops below the set value |
| **Skip Fruit Filter** | Blacklist specific devil fruits to avoid targeting those players |
| **Skip Safezone Targets** | Automatically skips targets hiding in safe zones |
| **Auto Skip Stuck Targets** | Detects targets that aren't losing HP and moves on automatically |
| **Auto Buso Haki** | Automatically activates Buso Haki when in close range |
| **PVP Auto-Enable** | Automatically enables PVP if it gets disabled mid-fight |
| **Hitbox Expansion** | Expands melee hitbox range for easier hits |
| **Camera Shake Disabled** | Removes camera shake for a smoother experience |
| **Anti Idle / AFK** | Virtual user click keeps the session alive |
| **Collision Disable** | Disables character collision to avoid getting stuck |
| **Auto Equip Weapon** | Automatically equips the best available weapon from your loadout |
| **Teleport to Target** | Smoothly teleports and tweens toward your current target |

### ⚔️ Skill System (GUI Controlled)
| Weapon | Skills | Toggles | Hold Time Sliders |
|---|---|---|---|
| **Melee** | Z, X, C | ✅ Per skill | ✅ Per skill |
| **Blox Fruit** | Z, X, C, V, F | ✅ Per skill | ✅ Per skill |
| **Gun** | Z, X | ✅ Per skill | ✅ Per skill |
| **Sword** | Z, X | ✅ Per skill | ✅ Per skill |

Every weapon category has:
- **Master enable/disable toggle**
- **Global skill delay slider** (0s – 10s)
- **Per-skill enable toggle**
- **Per-skill hold time slider** (0s – 10s)

### 📡 GUI Tabs
| Tab | Contents |
|---|---|
| ⚙️ **General** | Race settings, bounty range, safe health, teleport bypass |
| 👊 **Melee** | Full melee skill configuration |
| 🍎 **Blox Fruit** | Full fruit skill configuration |
| 🔫 **Gun** | Full gun skill configuration |
| ⚔️ **Sword** | Full sword skill configuration |
| 📡 **Misc** | Webhook URL, skip fruit list, chat spam |
| ℹ️ **Credits** | Version info, Discord link copy button |
| 🚀 **Start** | Launch button, save config, reset to defaults |

---

## 🚀 Installation

### One-Line Execute (Recommended)
Copy and paste this into your executor:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/ScriptsLibraryV2/ScriptLibrary.BLOXFRUIT-autobounty-/refs/heads/main/main.lua"))()
```

### Requirements
- A supported Roblox executor (Synapse X, KRNL, Fluxus, Solara, etc.)
- **Blox Fruits** game open in Roblox
- `bit32` library support (all major executors support this)

### Steps
1. Open **Blox Fruits** in Roblox
2. Attach your executor
3. Paste the loadstring above into the executor console
4. Execute the script
5. The **ScriptsLibrary V2.1** GUI will appear
6. Configure your settings across the tabs
7. Hit **▶ START** to begin auto bounty

---

## ⚙️ Configuration

| Setting | Default | Description |
|---|---|---|
| Team | `Pirates` | Your in-game team |
| Min Bounty Hunt | `0` | Minimum target bounty |
| Max Bounty Hunt | `30,000,000` | Maximum target bounty |
| Safe Health | `4,000 HP` | Retreat threshold |
| Use Race V3 | `true` | Auto-activate Race V3 |
| Use Race V4 | `true` | Auto-activate Race V4 |
| Skip Race V4 Users | `true` | Skip V4 transformed players |
| Bypass Teleport | `true` | Enable teleport bypass |
| Info Screen | `true` | Show live HUD |
| White Screen | `false` | Disable 3D rendering |

---

## 🎮 Skill Settings

Default configuration per weapon:

**Melee**
```
Delay: 1s
Z → Enabled | HoldTime: 0s
X → Enabled | HoldTime: 0s
C → Enabled | HoldTime: 0s
```

**Blox Fruit**
```
Delay: 2s
Z → Enabled | HoldTime: 0s
X → Enabled | HoldTime: 2s
C → Enabled | HoldTime: 0s
V → Enabled | HoldTime: 0s
F → Disabled | HoldTime: 0s
```

**Gun**
```
Delay: 1s
Z → Disabled | HoldTime: 0s
X → Disabled | HoldTime: 0s
```

**Sword**
```
Delay: 1s
Z → Enabled | HoldTime: 0s
X → Enabled | HoldTime: 0s
```

> All of these are adjustable live through the GUI with sliders and toggles.

---

## 💬 Discord

<div align="center">

### Join our community for updates, support, and announcements

[![Discord Banner](https://img.shields.io/badge/Discord-ScriptsLibrary%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/JP72Sz2CNU)

**[discord.gg/JP72Sz2CNU](https://discord.gg/JP72Sz2CNU)**

- 📢 Script updates & changelogs
- 🐛 Bug reports & support
- 💡 Feature requests
- 🤝 Community & chat

</div>

---

## 📜 Copyright & Legal

```
Copyright © 2024 ScriptsLibrary V2 — All Rights Reserved.

This script and its source code are the exclusive intellectual property
of ScriptsLibrary V2. Unauthorised copying, redistribution, modification,
reselling, or claiming ownership of this script or any part thereof is
strictly prohibited without prior written permission from the author.

ScriptsLibrary V2 is provided for educational and personal use only.
The author holds no responsibility for any account bans, game violations,
or any consequences resulting from the use of this software.

Roblox is a trademark of Roblox Corporation.
Blox Fruits is a trademark of its respective developers.
ScriptsLibrary V2 is not affiliated with or endorsed by Roblox Corporation
or the developers of Blox Fruits.
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:1a1a2e&height=120&section=footer" width="100%"/>

**ScriptsLibrary V2.1** — Made with ❤️

[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord)](https://discord.gg/JP72Sz2CNU)

</div>
