# Vanilla Area Mine

**Vanilla Area Mine** is a Fabric-based client-side mod for Minecraft Java Edition 1.21.11. It allows players to mine a 3×3 area around the targeted block while playing in Survival Mode.

## Features

- 3×3 area mining
- Automatically adjusts the mining area based on the targeted block face
- Toggle keybind
- In-game ON / OFF notifications
- Singleplayer only
- 3×3 mining works only in Survival Mode
- Normal block-breaking behavior in Creative Mode

## Requirements

- Minecraft Java Edition 1.21.11
- Fabric Loader 0.18.4 or newer
- Fabric API
- Java 21 or newer

## Installation

1. Install Fabric Loader and Fabric API.
2. Download `vanillaareamine-1.0.0.jar`.
3. Place the JAR file into your Minecraft `mods` folder.
4. Launch Minecraft using your Fabric profile.

## Controls

1. Open **Options → Controls → Key Binds**.
2. Find the Vanilla Area Mine category.
3. Assign a key to the Toggle action.
4. Press the assigned key to enable or disable 3×3 mining.

## Usage

- **ON:** Mines the surrounding 3×3 area when breaking a block.
- **OFF:** Uses normal block-breaking behavior.
- **Creative Mode:** Uses normal block-breaking behavior.
- **Multiplayer:** 3×3 mining is disabled.

## Building from Source

After downloading the source code, build the project with Gradle:

```bash
gradle build