# Color Party Dance Floor Designer

This is a web-based tool for designing and previwing dance floors used in the [Minecraft Color Party minigame](https://github.com/alexbates/ColorParty). 

Color Party is a multiplayer minigame (Spigot plugin) where players must quickly move to the correct color tile to avoid falling. The game consists of 25 rounds that become progressively shorter. At the start of each round, a terracotta block indicating the correct color is placed in each player's inventory. Players then have up to 5 seconds to relocate to that color. Once the time is up, all blocks are removed from the floor—except those of the correct color.

Dance floors are 64×64 grids (4,096 blocks), with each design stored as a JSON file containing coordinate data. This tool makes it easy to draw custom floor patterns and export them for use in the Color Party game.

## Features

- 23 sample dance floor designs
- Drawing tools with selectable terracotta colors, stroke width, and shape
- Undo and Redo support
- Import and edit existing JSON files
- Export designs as JSON for use in the game

## Screenshot

![Color Party Designer Screenshot](https://tamariapp.com/images/ColorPartyDesigner.png)
