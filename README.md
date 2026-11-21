# FiestaSMP world backup

This is the raw `world` folder from FiestaSMP at **fiestamc.neocities.org**. Snapshot date: **2026-11-21**. It is the Overworld and includes player data. The Nether and End are in the other repos.

## Download it

Open [Releases](https://github.com/open-fiestasmp/world/releases), pick `snapshot-2026-11-21`, then download **Source code (zip)** and extract it. The folder with `level.dat` is the world save. **Code → Download ZIP** gets the latest branch instead.

## Put it in Minecraft

**Single-player:** copy the extracted folder with `level.dat` into your Java Edition `saves` folder. To bring in the other dimensions too, copy `DIM-1` from `world-nether` and `DIM1` from `world-the-end` into the save's root. Back up an existing save before replacing anything.

**Paper server:** stop the server and back up its worlds first. Replace `world` with this folder. For the other dimensions, use the `world-nether` repo as `world_nether` and `world-the-end` as `world_the_end`. Don't merge files into a running world. Use a Minecraft/Paper version that can read this save.

## About this backup

This is an unofficial FiestaSMP community backup. It is not affiliated with or endorsed by Mojang or Microsoft, and it does not give anyone a license to Minecraft or their other material.

Backed up and published using Fiesta tools by `gautam652`.
