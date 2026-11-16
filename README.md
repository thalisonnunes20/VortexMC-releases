# VortexMC

VortexMC is an independent, cross-platform Minecraft launcher for Windows and Linux designed for simple instance management, direct modpack installations, and safe operation.

---

## Features

### Independent Instance Management
- Create and organize isolated Minecraft environments.
- Each instance maintains its own worlds, configuration files, mods, and resource packs. Changes in one profile do not affect any other profile.
- Instances can be launched, modified, duplicated, or removed at any time.
- Direct access button opens the exact instance directory in your system file manager.

### Comprehensive Mod Loader Support
- Full compatibility with Vanilla Minecraft releases.
- Native integration for modern mod loaders:
  - NeoForge
  - Forge
  - Fabric
  - Quilt
- Automatic installation and configuration of the required loader files for every selected profile.

### Mod & Modpack Catalog
- Built-in browser to discover and download content directly from CurseForge.
- Filter content by Modpacks, Mods, or All categories.
- Inspect full modpack information: overview description, changelogs, gallery screenshots, and release dates.
- One-click modpack installer that automatically configures game versions, loader requirements, configuration overrides, and dependent mod libraries.
- Loading indicators provide immediate visual feedback while retrieving catalog data.

### Version Switching and Downgrades
- Upgrade or downgrade existing modpack instances to any earlier or newer version with a single click.
- Preserves existing player saves, worlds, options, and keybindings while replacing and updating version-specific mod files and configurations.

### Dedicated Server File Downloads
- Direct Server Files tab for CurseForge modpacks.
- Allows downloading dedicated server packages (`server.zip` / `server.jar`) for any version of a modpack.
- Downloaded files are placed directly into your system Downloads folder and opened automatically once completed.

### Account Authentication
- Official Microsoft Account login via standard secure device code authentication.
- Offline mode support for custom player nicknames when playing locally or on offline-mode servers.
- Session tokens are stored using native system-level credential protection.

### Custom Storage Location
- Configure where all instances, game versions, and assets are stored on your disk.
- Easily select SSDs or external drives through a simple directory selection dialog in the Settings panel.

### Memory Allocation & Settings
- Dedicated RAM allocation slider to assign memory per instance according to your hardware resources.
- Application logs access button to review launcher diagnostic information in your file explorer.

### Multilingual Support & Interface Themes
- Full dual-language interface with on-the-fly switching between English (US) and Portuguese (BR).
- Interface theme switch between Dark mode and Light mode.

### Integrated Launcher Updates
- Automatic update detection checking against the official distribution repository.
- Detects new releases on startup and through the manual update check button in Settings.
- Delivers platform-specific update packages for Windows and Linux.

### Data Protection & Download Reliability
- Account tokens are encrypted on disk using system-level user security keys.
- Safe archive extraction preventing files from escaping designated instance directories.
- Automated checksum and file size validation during mod downloads with retry capabilities to prevent corrupt or incomplete files.

---

## Installation & Running

### Windows
1. Download the latest `VortexMC-v1.0.0-windows-x64.zip` or `VortexMC-v1.0.0-windows-x64.exe` from Releases.
2. If using the zip file, extract its contents to your preferred folder.
3. Launch `VortexMC.exe`.

### Linux
1. Download `VortexMC-v1.0.0-linux-x64.tar.gz` from Releases.
2. Extract the archive:
   ```bash
   tar -xzvf VortexMC-v1.0.0-linux-x64.tar.gz
   ```
3. Grant execution permissions:
   ```bash
   chmod +x VortexMC
   ```
4. Run the launcher:
   ```bash
   ./VortexMC
   ```

---

## Requirements

- Operating System: Windows 10/11 (64-bit) or modern Linux distribution (x86_64).
- Java Runtime Environment (JRE) matching your target Minecraft version (Java 8 for legacy releases, Java 17/21 for modern releases).
- Internet connection for initial account login, updates, and game downloads.
