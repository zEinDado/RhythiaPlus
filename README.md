# Rhythia+

**Rhythia+** is an unofficial in-game companion overlay for the **Steam version of Rhythia**.

It extends Rhythia with additional community tools, map and skin management, a customizable HUD, interface customization, and quality-of-life features — while keeping the original game experience intact.

> **Rhythia+ is currently in active development.**  
> Only the Steam version of Rhythia is currently supported.

---

## Features

### Control Center

- In-game Rhythia+ Control Center
- Opens directly on top of Rhythia
- Quick access to Community, Library and HUD features
- Session information
- Recently used maps
- Integrated animated `RHYTHIA+` button in Rhythia's top bar
- Customizable hotkeys

### Community

Browse official Rhythia community content directly through Rhythia+.

#### Maps

- Browse the official Rhythia map catalog
- Search maps
- Ranked, Legacy and Unranked filters
- Rating filters
- Difficulty filters
- Map covers and detailed information
- Mapper, duration, rating, plays and description
- Download and automatically import maps
- Detect already installed maps
- Open maps on the official Rhythia website

#### Profiles

- Browse the global player leaderboard
- Search players and creators
- View profile information and statistics
- Find maps created by a player
- Find skins created by a player
- Open public Rhythia profiles

#### Skins

- Browse the official Rhythia skin catalog
- Search skins
- Browse categories such as:
  - RHS
  - Cursors
  - Notes
  - Borders
- Preview skins
- Download and automatically import skins
- Detect already installed skins

---

## Library

Manage your locally installed Rhythia content.

### Maps

- Search installed maps
- Automatic map detection
- Drag & Drop importing
- Supported formats include:
  - `.sspm`
  - `.rhm`
  - `.zip`
- Remove installed maps

### Skins

- Automatic skin detection
- Search installed skins
- Filter by skin category
- Remove installed skins

---

## HUD Overlay

Rhythia+ includes a customizable HUD that can stay visible while playing.

Available widgets currently include:

- Clock & Date
- Session Status
- CPU & RAM Usage
- Cursor Speed Meter

HUD features:

- Enable or disable individual widgets
- Freely move widgets
- Saved widget positions
- Adjustable HUD opacity
- Smart HUD Dodge
- Click-through support

More HUD features are planned.

---

## Customization

Rhythia+ can be customized independently from Rhythia.

- Multiple interface themes
- Cinematic backgrounds
- Custom background images
- Supported formats:
  - PNG
  - JPG
  - WEBP
  - BMP
- Custom accent colors
- Adjustable interface size
- Adjustable background darkness
- Reduced animation option
- Movable Rhythia+ top-bar button

---

## Languages

Rhythia+ can automatically detect the language selected in Rhythia.

Currently supported:

- English
- Deutsch
- Русский
- Français
- Español
- Polski
- Birb

The language can also be changed manually inside Rhythia+.

---

## Offline Support

Rhythia+ continues to work without an internet connection.

Offline functionality includes:

- Control Center
- Map & Skin Library
- HUD
- Settings
- Themes and customization

Online Community features are automatically disabled while offline.

---

# Installation

## 1. Download Rhythia+

Download the latest Rhythia+ release from the **Releases** section of this repository.

Extract the downloaded ZIP file.

---

## 2. Open the Rhythia installation directory

In Steam:

**Rhythia → Gear icon → Manage → Browse local files**

Your Rhythia directory should look similar to:

```text
...\steamapps\common\rhythia\
```

---

## 3. Install the RhythiaPlus folder

Move the complete:

```text
RhythiaPlus
```

folder into the Rhythia installation directory.

Example:

```text
rhythia\
├── Rhythia.exe
├── ...
└── RhythiaPlus\
    └── Rhythia+.exe
```

---

## 4. Configure Steam Launch Options

Copy the full path to:

```text
RhythiaPlus\Rhythia+.exe
```

Then open:

**Steam → Rhythia → Properties → General → Launch Options**

Enter:

```text
"YOUR_PATH_TO_RHYTHIA\RhythiaPlus\Rhythia+.exe" --steam %command%
```

Example:

```text
"E:\SteamLibrary\steamapps\common\rhythia\RhythiaPlus\Rhythia+.exe" --steam %command%
```

Your path may be different depending on where Steam or Rhythia is installed.

---

## 5. Start Rhythia

Start Rhythia normally through Steam.

Rhythia+ will automatically start together with the game.

When Rhythia closes, Rhythia+ will also close automatically.

---

# Updating

Update instructions will be provided with each release.

An integrated Rhythia+ update system is planned.

---

# Uninstallation

To completely remove Rhythia+:

1. Close Rhythia.
2. Open Steam.
3. Go to **Rhythia → Properties → General → Launch Options**.
4. Remove the Rhythia+ launch option.
5. Delete the `RhythiaPlus` folder from the Rhythia installation directory.
6. Start Rhythia normally.

No original Rhythia files need to be replaced.

---

# Safety & Game Integrity

Rhythia+ is designed as an external companion overlay.

It does **not**:

- use DLL injection
- modify scores
- modify gameplay input
- modify Rhythia's original executable

Rhythia+ focuses on interface, community, library and HUD functionality.

---

# Development Status

Rhythia+ is still under active development.

Features, interface elements and behavior may change between releases.

If you encounter a bug, please report it through the repository's **Issues** section.

Feature suggestions are also welcome.

---

# Source Code

Rhythia+ is currently distributed as compiled software.

The source code is **not publicly available at this time**.

This may change in the future.

---

# Disclaimer

Rhythia+ is an **unofficial community project**.

It is not affiliated with, endorsed by, or maintained by the official Rhythia developers.

Rhythia and all related trademarks, assets and services belong to their respective owners.
