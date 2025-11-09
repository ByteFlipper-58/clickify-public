# Clickify
[![Minecraft 1.20.0-1.20.6](https://img.shields.io/badge/Minecraft-1.20.0--1.20.6-3C8527?style=for-the-badge&logo=minecraft)](https://www.minecraft.net/)
[![Fabric](https://img.shields.io/badge/Fabric-Loader%201.20-blue?style=for-the-badge&logo=fabric)](https://fabricmc.net/)
[![License: All Rights Reserved](https://img.shields.io/badge/License-All%20Rights%20Reserved-critical?style=for-the-badge)](#-license--credits)

> Clickify combines a dual-button auto clicker with a smart bridge assistant so AFK farms and large builds stay clean, repeatable, and fully client-side.
> One universal jar now spans Fabric 1.20.0 – 1.20.6 without rebuilding.

*Read this document in Russian: [README.ru.md](README.ru.md)*

---

## ✨ Key Features

- **Dual-button auto clicker** – independent LMB/RMB profiles (`OFF / HOLD / SPAM`) with cooldown awareness and precise tick speed (0–10).
- **Bridge assistant** – hold `Y` and the mod pilots movement, Shift, sprint, and block placement across `Safe`, `Fast`, `Horizontal`, and `Diagonal` modes.
- **Camera helpers** – optional yaw snapping (90°/45°) and pitch locking for straight, repeatable lanes.
- **Split GUI + JSON config** – Clicker (`O`) and Helper (`U`) live on dedicated screens, while the same values sync to `config/clickify.json`.
- **Native input path** – relies on `KeyBinding` / `InputUtil`, never emulating hardware events.

## 🧩 Compatibility

- Single jar covers every Fabric build from 1.20.0 through 1.20.6.
- Sticks to 1.20 mappings to avoid newer API calls.
- Smoke-tested by compiling against the 1.20 and 1.20.6 toolchains.
- Runtime and metadata guards warn when Minecraft falls outside the supported range.

---

## 🎮 Controls (defaults)

| Action                        | Key | Description                                         |
|-------------------------------|-----|-----------------------------------------------------|
| Open clicker settings         | **O** | Shows the Clicker screen                            |
| Quick toggle auto clicker     | **I** | Enables or disables the clicker instantly           |
| Open helper / bridge settings | **U** | Shows the Helper (bridge assistant) screen          |
| Hold helper (auto bridge)     | **Y** | Engages the selected bridge preset while held       |

---

## 🖥️ GUI Overview

1. **Clicker Screen** – toggles for `Active`, `Respect cooldown`, `Speed`, plus LMB/RMB mode selectors.
2. **Helper Screen** – sections for `Bridge assistant`, `Bridge mode`, `Lock pitch`, `Snap yaw`, `Auto place`, and `Pitch`.

---

## 📄 License & Credits

All rights reserved. Viewing or running the distributed binaries is permitted, but redistribution, modification, or derivative work requires prior written permission from the author.  
Author: [ByteFlipper](https://byteflipper.com)
