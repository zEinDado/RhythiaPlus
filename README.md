# Rhythia+

**Rhythia+** is an unofficial in-game companion overlay for the **Steam version of Rhythia**.

It extends Rhythia with additional community tools, map and skin management, a customizable HUD, interface customization, and quality-of-life features while keeping the original game experience intact.

> **Rhythia+ is currently in active development.**  
> Only the Steam version of Rhythia is currently supported.

---

## Features

### Control Center

Rhythia+ integrates directly into Rhythia as an in-game overlay.

- In-game Control Center
- Transparent overlay on top of Rhythia
- `F2` opens or closes Rhythia+
- Alternative overlay hotkey
- `Ctrl + Shift + H` toggles the HUD
- Customizable hotkeys
- Animated `[ RHYTHIA+ ]` button integrated into Rhythia's top bar
- Movable and saved top-bar button position
- Session information
- Installed map overview
- Recently used maps
- Quick access to Community, Library, Map Import and HUD controls
- Rhythia+ automatically closes when Rhythia is closed

---

## Community

Browse Rhythia community content directly through Rhythia+.

### Maps

- Official Rhythia map catalog
- Search maps
- Ranked, Legacy and Unranked filters
- Rating filters
- Difficulty filters
- Map covers and previews
- Mapper information
- Duration
- Rating
- Play count
- Description
- Download progress
- Automatic map import
- Detection of already installed maps
- `Already Installed` status
- Direct access to the Map Library
- Open maps on the official Rhythia website
- Catalog refresh
- Pagination

### Profiles

- Global player leaderboard
- Search players and creators
- Profile images
- Profile information and statistics
- Detect whether a creator has uploaded maps
- Detect whether a creator has uploaded skins
- Show creator maps
- Show creator skins
- Open public Rhythia profiles
- Filter Community content by creator

### Skins

- Official Rhythia skin catalog
- Search skins
- Skin previews
- Skin details
- Download progress
- Automatic skin import
- Detection of already installed skins

Supported skin categories include:

- RHS
- Cursors
- Notes
- Borders

---

## Library

Manage locally installed Rhythia content.

### Maps

- Automatic detection of installed maps
- Search installed maps
- Drag & Drop importing
- Map removal
- Compact action menus

Supported map formats include:

```text
.sspm
.rhm
.zip
```

### Skins

- Automatic detection of installed skins
- Search installed skins
- Filter skins by category
- Remove installed skins

---

## HUD Overlay

Rhythia+ includes a customizable HUD that can remain visible while playing.

Current widgets include:

- Clock & Date
- Session Status
- CPU & RAM Usage
- Cursor Speed Meter

HUD features include:

- Enable or disable the entire HUD
- Enable or disable individual widgets
- Freely move widgets
- Saved widget positions
- Adjustable HUD opacity
- Smart HUD Dodge
- Area-aware click-through behavior

**Smart HUD Dodge** detects when the mouse cursor approaches a HUD widget and temporarily reduces its visibility so important gameplay areas remain unobstructed.

More HUD features are planned.

---

## Customization

Rhythia+ can be visually customized independently from Rhythia.

- Multiple complete interface themes
- Cinematic theme backgrounds
- Custom background images
- Custom accent colors
- Adjustable interface size
- Adjustable background darkness
- Reduced animation option
- Movable Rhythia+ top-bar button

Supported custom background formats:

```text
PNG
JPG
WEBP
BMP
```

---

## Languages

Rhythia+ can automatically detect the language selected in Rhythia.

The overlay language can also be changed manually in Settings.

Supported languages:

- English
- Deutsch
- Русский
- Français
- Español
- Polski
- Birb

Language changes are applied directly inside the overlay.

---

## Offline Support

Rhythia+ can continue to operate without an internet connection.

The following features remain available offline:

- Control Center
- Map & Skin Library
- HUD
- Settings
- Themes
- Customization

Online Community functionality is disabled while offline.

Rhythia+ provides a dedicated offline screen instead of displaying technical network errors.

Available offline actions include:

- Retry Connection
- Open Map Library

Rhythia+ can also automatically retry the connection.

---

# Installation

## 1. Download Rhythia+

Download the latest Rhythia+ release from the **Releases** section of this repository.

Extract the downloaded ZIP archive.

---

## 2. Open the Rhythia installation directory

In Steam:

**Rhythia → Gear icon → Manage → Browse local files**

Your Rhythia installation should be located somewhere similar to:

```text
...\steamapps\common\rhythia\
```

The exact location depends on where your Steam Library is installed.

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
├── ...
└── RhythiaPlus\
    ├── Rhythia+.exe
    └── ...
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

Your path may be different depending on where Steam and Rhythia are installed.

---

## 5. Start Rhythia

Start Rhythia normally through Steam.

Rhythia+ will automatically start together with Rhythia.

When Rhythia is closed, Rhythia+ will automatically close as well.

---

# User Data

Rhythia+ stores persistent user data separately from the program files.

The data directory is located at:

```text
%APPDATA%\RhythiaPlus\
```

This allows Rhythia+ settings to remain separate from the files located inside the Steam Rhythia directory.

Depending on the version, this directory may contain persistent configuration and other Rhythia+ user data.

---

# Updating

Update instructions are provided with each release.

Because persistent Rhythia+ data is stored separately under:

```text
%APPDATA%\RhythiaPlus\
```

program files can be updated without necessarily removing the user's saved configuration.

An integrated automatic update system is planned.

Until then, manual update instructions will be included in the release notes.

---

# Uninstallation

## Remove Rhythia+ while keeping your settings

1. Close Rhythia.
2. Open Steam.
3. Go to:

   **Rhythia → Properties → General → Launch Options**

4. Remove the Rhythia+ launch option.
5. Delete the following folder from the Rhythia installation directory:

```text
RhythiaPlus
```

Rhythia+ will no longer start with Rhythia.

Your saved Rhythia+ user data will remain inside:

```text
%APPDATA%\RhythiaPlus\
```

This can be useful if you plan to reinstall Rhythia+ later.

---

## Completely remove Rhythia+

For a full uninstall:

1. Follow the steps above.
2. Press `Win + R`.
3. Enter:

```text
%APPDATA%
```

4. Delete:

```text
RhythiaPlus
```

This removes the remaining Rhythia+ user data and settings.

> Deleting the `%APPDATA%\RhythiaPlus` folder will remove your saved Rhythia+ configuration.

No original Rhythia files need to be replaced or restored.

---

# Safety & Game Integrity

Rhythia+ is designed as an external companion overlay.

Rhythia+ does **not**:

- use DLL injection
- modify scores
- modify gameplay input
- modify Rhythia's original executable

Rhythia+ focuses on interface, community, library, HUD, customization and quality-of-life functionality.

---

# Compatibility

Currently supported:

- Windows
- Steam version of Rhythia

Other versions of Rhythia are not currently supported.

---

# Development Status

Rhythia+ is under active development.

Features, interface elements and behavior may change between releases.

If you encounter a bug, please report it through the repository's **Issues** section.

Feature suggestions and feedback are also welcome.

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
