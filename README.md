# Crysis Trainer

SP trainer/cheat mod for Crysis 1 (64-bit). Uses c1-mod-sdk + ImGui.

Singleplayer only.

## Install

Drop the `Mods` folder from the release into your Crysis directory and launch with `-mod MyMod`.

## Features

- ESP (box, bone, name, distance, health, snaplines, glow, item esp)
- Aimbot (bone select, vis check, prediction, silent aim, magic bullet)
- Weapon mods (no recoil, no spread, inf ammo, rapid fire, instant reload, damage mult, etc)
- God mode, inf health, inf energy, cloak, one hit kill, no fall damage
- Unlimited inventory (no weapon carry limit)
- Noclip/fly (works in vehicles too)
- HL1-style bunny hop (quake air strafing, unlimited speed)
- Speed hack, third person, teleport
- Vehicle/entity/item spawner
- Kill all enemies
- Custom crosshair
- World stuff (time of day, slow mo, disable AI, no fog, wireframe, fullbright)
- Out of map bypass
- Save/load config

## Controls

INSERT or F1 to open the menu.

## Build

Needs VS 2022+ and CMake.

```
cmake --preset default
cmake --build build
```

Output goes to `Mods/MyMod/Bin64/MyMod.dll`.
