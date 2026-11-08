# VELOX-APP
Velox Launcher
A modern Minecraft: Java Edition launcher built with Python and HTML.

Velox Launcher is a desktop launcher focused on managing Minecraft installations, modded instances, and game content through a clean interface. It integrates with Modrinth and supports several popular mod loaders.
This repository contains the launcher source code. The project is primarily designed for Windows.

Features
Minecraft instances
- Create, edit, duplicate, and delete separate game instances.
- Keep instance game files and configuration isolated.
- Choose a custom icon for an instance.
- Launch an instance directly, including through desktop shortcuts.
- Open instance folders, logs, screenshots, saves, and other game files.
- Back up and manage worlds.
Minecraft versions and mod loaders
- Vanilla Minecraft.
- Fabric.
- Forge.
- NeoForge.
- Quilt.
- Download and manage Java runtimes.
- Configure memory allocation and other launcher settings.
Modrinth integration
Browse and install supported content from Modrinth:
- Mods.
- Resource packs.
- Shaders.
- Browse by category and filter by Minecraft version and mod loader.
- View installed content, remove it, and check for compatible updates.
Modpacks
- Import Modrinth .mrpack modpacks.
- Install modpack files and supported overrides.
- Export instances as .mrpack files.
Accounts
- Microsoft account sign-in.
- Ely.by account support.
- Offline profiles.
- Account selection and management.
Microsoft authentication requires a valid Microsoft OAuth application configuration. The launcher uses a browser-based sign-in flow; it does not ask users to enter their Microsoft password into the launcher.
Skins and capes
- Import skins from PNG files or supported URLs.
- Import skins using a Minecraft username.
- Manage a local skin library.
- Browse supported community skin sources.
- Apply skins and select the player model.
- View and manage supported Microsoft capes.
Other features
- Discord Rich Presence support.
- Launcher news and status information.
- Automatic launcher update checks.
- Storage information and cache management.
- Hardware acceleration setting.
Feature availability may depend on the selected account type, Minecraft version, installed loader, external services, and platform.
Requirements
Running the launcher
- Windows 10 or later is recommended.
- Microsoft Edge WebView2 Runtime.
- Internet connection for downloading Minecraft files, Java runtimes, loaders, and Modrinth content.
WebView2 Runtime:
https://go.microsoft.com/fwlink/p/?LinkId=2124703
On Windows, the data directory is:
%APPDATA%\VeloxLauncher
The launcher keeps its configuration, Minecraft files, instances, downloaded Java runtimes, logs, and custom instance icons in this location.

Removing the source directory or reinstalling the executable does not automatically remove this data directory. Back up important instances and worlds before manually deleting launcher data.
Third-party services and components
Velox Launcher interacts with third-party services and projects, including:
- Minecraft
- Microsoft identity platform
- Modrinth
- Fabric
- Forge
- NeoForge
- Quilt
- Ely.by
- WebView2
- Xyrios
These services and projects are not owned by or affiliated with Velox Launcher unless explicitly stated. Their names and trademarks belong to their respective owners. Their own terms and licenses apply.
Disclaimer
Velox Launcher is an independent third-party project and is not an official Minecraft, Mojang, Microsoft, or Modrinth product.

Minecraft is a trademark of Microsoft Corporation. Velox Launcher is not affiliated with, endorsed by, or sponsored by Microsoft or Mojang.

The launcher downloads game files and content from their respective providers. Users are responsible for ensuring that their use of Minecraft and downloaded content complies with the applicable terms and licenses.
