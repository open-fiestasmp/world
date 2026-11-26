# fiesta overworld

This is the FiestaSMP Overworld save from 2026-11-26. It has the terrain, builds, player data, stats, advancements and datapacks. The matching Nether and End are in the other two repos.

It's about 47 GB of world files before extraction. Leave extra disk space for the download and the extracted copy. Use Java Edition and test on a copy first if you aren't sure which game version to use.

## download

Open [Releases](https://github.com/open-fiestasmp/world/releases), choose `snapshot-2026-11-26-3`, then download **Source code (zip)**. Extract it. The folder with `level.dat` at its top level is the save. GitHub adds a wrapper folder around it; use that folder as the world folder. `README.md` is just this guide and can be removed after you read it.

## use it in java single-player

1. Close Minecraft.
2. Copy the extracted folder with `level.dat` into your Java Edition `saves` folder. On Windows that's `%appdata%\.minecraft\saves`; on macOS it's `~/Library/Application Support/minecraft/saves`; on Linux it's usually `~/.minecraft/saves`. Custom launchers may use a different game folder.
3. Rename the copied folder to something like `FiestaSMP`.
4. If you want the Nether and End too, download the matching `snapshot-2026-11-26-3` from [world-nether](https://github.com/open-fiestasmp/world-nether) and [world-the-end](https://github.com/open-fiestasmp/world-the-end). Copy the Nether repo's `DIM-1` folder and the End repo's `DIM1` folder into the root of this save. Don't copy their `level.dat` files over the Overworld's. Back up the save before replacing either dimension folder.
5. Start the same Minecraft version the save came from and open the copied world. Don't test an upgrade on your only copy.

## use it on a Paper server

1. Stop the server fully. Don't copy world files while Paper is running.
2. Back up the current `world`, `world_nether` and `world_the_end` folders somewhere else first.
3. Extract the Overworld, Nether and End archives from the same release. Put the extracted folders side by side in the server folder and name them `world`, `world_nether` and `world_the_end`.
4. Keep `level-name=world` in `server.properties` for this layout. If your server or world manager uses different names, make the folder names match that setup.
5. Start the same Paper/Minecraft version the save came from. Check the console before letting players join.

The Overworld repo includes `playerdata`, `stats` and `advancements`. Player inventory and position are tied to UUIDs, so they may not line up if the server's account-auth settings or UUID setup changed.

## extra files

`.world-tier/access` has small region access-time markers. Minecraft doesn't need them to load the save; keep them if you want that access history. This repo is world data only. It doesn't include Fiesta's plugins, proxy setup or server config.

This is a community backup from FiestaSMP. We aren't Mojang or Microsoft, and this doesn't include or grant a Minecraft license.

Backed up and uploaded using Fiesta tools by `gautam652`.
