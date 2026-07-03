# Graveyard Keeper Co-op Multiplayer Mod

![Game](https://img.shields.io/badge/Game-Graveyard%20Keeper-8B5E3C?style=for-the-badge)
![Multiplayer](https://img.shields.io/badge/Mode-Co--op%20Multiplayer-2E8B57?style=for-the-badge)
![Mod Loader](https://img.shields.io/badge/Requires-BepInEx-DAA520?style=for-the-badge)
![License](https://img.shields.io/badge/License-BY--NC--SA%204.0-B22222?style=for-the-badge)

A co-op multiplayer mod for Graveyard Keeper that allows players to experience a proper synchronized multiplayer session through either Steam invites or a direct P2P connection.

Play together in the same world, progress together, fight together, and share the workload.

## Features

### Fully Synchronized World

The following world elements are synchronized between players:

* Weather
* NPCs
* Enemies
* Resources
* Quests
* Technologies
* Time
* Combat

### Multiplayer Support

* Supports up to 10 players in one session.
* Each player keeps their own:

  * Inventory
  * Health
  * Energy

### Shared Combat

Enemy positions, attacks, and health are synchronized between players.

Any player can damage enemies, so everyone can participate in combat together in the same world.

### Balanced Loot

Loot drops only once to prevent duplication.

If you want more resources, bring more players and put in more effort.

### Safe Direct P2P Client Saves

When playing through direct P2P, the client’s save is not affected.

This allows players to join a host’s world without overwriting or damaging their own save progress.

## Requirements

This mod requires:

* Graveyard Keeper
* BepInEx mod loader

## Installation

1. Download and install BepInEx.

2. Unpack the BepInEx archive into your Graveyard Keeper game folder.

   This is the folder that contains Graveyard Keeper.exe


3. Launch the game once.

   This allows BepInEx to create the required folders.

4. Close the game.

5. Copy this mod’s `.dll` file into:

   ```text
   Graveyard Keeper\BepInEx\plugins
   ```

6. Launch the game and play.

## How to Connect

There are two supported connection methods:

* Steam connection
* Direct P2P connection

## Steam Connection

1. The host loads their save.

2. The host invites another player through Steam.

3. The other player accepts the Steam invitation.

4. Start playing together.

## Direct P2P Connection

1. On the client machine, open the config file:

   ```text
   Graveyard Keeper\BepInEx\config\com.gkcoop.mod.cfg
   ```

2. Find the `HostIP` string.

3. Enter the host’s IP address.

4. Both players load their saves.

5. The host presses:   `F1`

6. The client presses:   `F2`

7. To disconnect, press:   `F9`

## Controls

| Key  | Action                            |
| ---- | --------------------------------- |
| `F1` | Host direct P2P session           |
| `F2` | Join direct P2P session as client |
| `F9` | Disconnect                        |

## License

This project is licensed under the terms described in [`LICENSE.md`](LICENSE.md).
