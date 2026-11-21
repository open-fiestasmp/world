# FiestaSMP Overworld snapshot

Public snapshot of the `world` Overworld folder from the FiestaSMP Minecraft Java server at **fiestamc.neocities.org**. This repo is one part of the server's world backup. Snapshot date is shown on the dated release; Git commit timestamps record each repository update. The Overworld includes player data.

## Download

Open [Releases](https://github.com/open-fiestasmp/world/releases), choose the dated `snapshot-2026-11-21` release, and download **Source code (zip)**. Extract it; the folder containing `level.dat` is the Overworld save. **Code → Download ZIP** downloads the current branch instead.

## Load in Minecraft Java Edition

For single-player, copy the extracted folder containing `level.dat` into your Java Edition `saves` directory and select it under **Singleplayer**. To include the FiestaSMP Nether and End in that single-player save, also download the `world-nether` and `world-the-end` repos and copy their `DIM-1` and `DIM1` folders into this save's root, respectively. Back up any destination save before replacing dimension folders.

For a Paper server, stop it first and back up all existing world folders. Replace the server's `world` folder with this extracted Overworld. To restore all dimensions, also restore `world-nether` as `world_nether` and `world-the-end` as `world_the_end`. Use a compatible Minecraft/Paper version; the standard Paper dimension layout is documented in the [Paper migration guide](https://docs.papermc.io/paper/migration/). Never merge files into a running world.

## Notice

Unofficial community backup of the FiestaSMP `world` save. Not affiliated with, endorsed by, or sponsored by Mojang or Microsoft. This repository grants no license to Minecraft software or other Mojang/Microsoft material; those are subject to their own terms.
Backed up and published using Fiesta tools by `gautam652`.
