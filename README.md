# Aquanautics: alpha testing

Build hulls that really float, assemble them into rafts and ships and sail them. This repository holds the alpha builds for testers: download the jar below and drop it into your `mods` folder.

**Current build:** [`aquanautics-1.0.5-alpha.jar`](aquanautics-1.0.5-alpha.jar) (see [CHANGELOG.md](CHANGELOG.md))

## Requirements
- Minecraft **1.21.1** with **NeoForge 21.1.265** or later
- **Sable 2.0.6** or later (required: physics for the vessels)
- Optional: **Patchouli** (in-game guide book), **Jade** (shows block weights), **JEI**

## Getting started
1. Build a hull on the water. The **Sealed Barrel** and the **Stone/Metal Keels** can be placed straight onto the water surface.
2. Put a **Rudder** at the stern (the way you face when placing it becomes the bow) and right-click it to assemble the raft.
3. **Sneak + right-click** the rudder to take the helm: W/S ahead/astern, A/D to turn, `~` throttle lock, Left Shift to leave. A lever on the rudder turns on cruise control.
4. Craft the **Ultimate Guide to Aquanautics** (Sealed Barrel + Book, needs Patchouli) for everything else: sails, masts, mooring, the Gauge, weights.

## What to test
Tier 1 (rafts: up to 64 blocks, one rudder, up to 3 blocks/s) and **tier 2** (ships: Ship Rudder + Ship's Wheel, up to 512 blocks, up to 9.2 blocks/s). New in 1.0.4: tier 2 ships, the Mooring Line and the Bollard.

Dev tools are included in these builds: the **Dev Assembler** (no block limit) and sneak + right-click with a **stick** to read a block's density.

## Known issues
- **With an Iris shader pack on, water shows inside hulls.** Shader packs draw water with their own shaders. Without a shader pack (Sodium alone is fine) hulls are dry. It is only visual: hulls still float correctly.
- Worlds from earlier test builds may have missing blocks (old Wooden Keels and 3x3 sails).

## Reporting bugs
Open an issue in this repository with what you did, what happened and what you expected. Logs (`logs/latest.log`) and a screenshot help a lot.
