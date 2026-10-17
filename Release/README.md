# Crysis Singleplayer Trainer

A comprehensive singleplayer cheat mod for **Crysis 1** (64-bit) built with the c1-mod-sdk. Features an ImGui overlay with ESP, aimbot, weapon mods, movement hacks, spawners and more.

> **Singleplayer only.** This mod is intended for offline/singleplayer use.

## Installation

1. Copy the `Mods` folder into your Crysis installation directory (e.g. `D:\Games\Crysis\`)
2. The final path should be: `Crysis\Mods\MyMod\Bin64\MyMod.dll`
3. Launch Crysis with the mod: add `-mod MyMod` to launch options, or use a mod launcher

## Controls

- **INSERT** or **F1** - Toggle menu
- Menu is fully mouse-driven via ImGui

## Features

### ESP / Visuals
- 2D Box (Skeleton), 3D Box, Bone ESP
- Name, Distance, Health Bar
- Snaplines with visibility check
- Item ESP (Weapons, Ammo, Vehicles, Mission items)
- Glow / Silhouette ESP
- Configurable colors for all elements

### Aimbot
- Bone selection (Head / Chest / Nearest Bone)
- Visibility check
- Bullet prediction / lead
- Adjustable FOV and smoothing
- Silent Aim
- Magic Bullet

### Weapon
- No Recoil / No Spread
- Infinite Ammo / Infinite Clip
- No Overheat / No Spin-Up
- Auto Fire / Rapid Fire (safe, rate-limited)
- No Weapon Sway / No Bobbing
- No Weapon Animations / No Weapon Lowering
- No Fire Shake / No Switch Delay
- Instant Reload
- Damage Multiplier

### Player
- God Mode / Infinite Health
- Infinite Energy
- Invisibility (Cloak)
- One Hit Kill
- No Fall Damage
- No Camera Recoil
- Unlimited Inventory (no weapon carry limit)
- Force Nano Mode (Armor / Speed / Strength / Cloak)
- Custom Gravity / Jump Height Override
- Out-of-map boundary bypass (no kill zone when god mode active)

### Movement
- **Noclip / Fly** - WASD + Space/Ctrl, Shift = fast (works with vehicles)
- **Bunny Hop (Half-Life Style)** - Full Quake/HL1 air-strafe movement engine
  - PM_AirAccelerate / PM_Friction ported from Quake source
  - 5 physics sub-steps per frame for accuracy
  - Unlimited speed cap
  - Auto-jump (hold Space)
- Speed Hack with multiplier
- Third Person (persistent, survives vehicle enter/exit)
- Teleport (Save / Load / To Crosshair)

### World
- Freeze / Set Time of Day
- Slow Motion
- Disable AI
- No Fog / Wireframe / Fullbright

### Spawners
- **Vehicle Spawner** - Spawn vehicles at player or crosshair position
- **Entity Spawner** - Spawn NPCs (Grunt, Civilian, Trooper, Scout, Hunter, Alien, Shark) via Lua
- **Item Spawner** - Give weapons to inventory, spawn at crosshair, or give all items
- **Kill All Enemies** utility

### Other
- Custom Crosshair (Cross / Dot / Circle with size and color)
- Force Enter Vehicle
- Config Save / Load (persists all settings)

## Building from Source

### Requirements
- Visual Studio 2022+ with C++ desktop workload
- CMake 3.15+
- [c1-mod-sdk](https://github.com/ccomrade/c1-mod-sdk)

### Build
```bash
cmake --preset default
cmake --build build
```

The compiled DLL will be at `Mods/MyMod/Bin64/MyMod.dll`.

## Credits

- Built with [c1-mod-sdk](https://github.com/ccomrade/c1-mod-sdk)
- Bunny hop movement based on the Quake 1 GPL source code by id Software
- ImGui by ocornut

## Disclaimer

This mod is for educational and singleplayer entertainment purposes only. Use at your own risk.
