# Aquanautics: alpha testing

Build hulls that really float, assemble them into rafts and sail them. This repository holds the alpha builds for testers: download the jar below and drop it into your `mods` folder.

**Current build:** [`aquanautics-1.0.1-alpha.jar`](aquanautics-1.0.1-alpha.jar) (see [CHANGELOG.md](CHANGELOG.md))

## Requirements
- Minecraft **1.21.1** with **NeoForge 21.1.265** or later
- **Sable 2.0.6** or later (required: physics for the vessels)
- Optional: **Patchouli** (in-game guide book), **Jade** (shows block weights), **JEI**

## Getting started
1. Build a hull on the water. The **Sealed Barrel** and the **Stone/Metal Keels** can be placed straight onto the water surface.
2. Put a **Rudder** at the stern (the way you face when placing it becomes the bow) and right-click it to assemble the raft.
3. **Sneak + right-click** the rudder to take the helm: W/S ahead/astern, A/D to turn, `~` throttle lock, Left Shift to leave.
4. Craft the **Ultimate Guide to Aquanautics** (Sealed Barrel + Book, needs Patchouli) for everything else: sails, masts, mooring, the Gauge, weights.

## What to test
This alpha is **tier 1 only** (rafts: up to 64 blocks, one rudder, up to 3 blocks/s). Tier 2 parts are disabled.

Dev tools are included in these builds: the **Dev Assembler** (no block limit) and sneak + right-click with a **stick** to read a block's density.

## Known issues
- **With Sodium installed, water shows inside hulls.** Sable only hides hull water on the vanilla renderer. Hulls still float correctly; it is only visual.
- Worlds from earlier test builds may have missing blocks (old Wooden Keels and 3x3 sails).

## Reporting bugs
Open an issue in this repository with what you did, what happened and what you expected. Logs (`logs/latest.log`) and a screenshot help a lot.
