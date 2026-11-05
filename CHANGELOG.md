# Changelog

## 1.0.3-alpha
- **No liquids on vessels:** a bucket of water, lava or any other liquid can't be poured onto a vessel ("Liquids can't be poured onto vessels"), nor into a slab, stair or other waterloggable block aboard.
- **Water stays out of assembly:** water, kelp, seagrass and bubble columns are no longer pulled into a raft, and waterlogged blocks (slabs, stairs, fences, the rudder...) are drained when the raft is assembled.
- **Fixed:** steering in reverse. When the raft is moving astern, A and D now turn the bow the opposite way, like steering a car in reverse (the autopilot wheel does the same).
- **Rudder recipe:** now also needs an iron ingot, in the slot below the slab.
- **Farming:** crops (wheat, carrots, potatoes, beetroots, melon and pumpkin stems), sugar cane, nether wart, cocoa and sweet berry bushes weigh nothing and don't count toward the 64-block limit. Dirt and farmland still weigh and count. Modded crops are covered if they're in the `#minecraft:crops` block tag.

## 1.0.2-alpha
- **Fixed:** grass blocks weighed less than dirt (150 kg vs 800 kg); grass, dirt, farmland and paths now all weigh like dirt.
- **Fixed:** farmland, crops and sugar cane next to a raft were pulled into it when assembling. Build your farm after assembling.
- **Fixed:** the Gauge's centre of gravity wasn't visible through blocks. A gold "CoG" marker now shows on screen over everything.
- **Farming afloat:** farmland on a vessel always stays wet, and sugar cane grows on any dirt block aboard (no water beside it needed).
- **Cruise control on the raft rudder:** put a lever on the rudder and switch it on. W/S set the speed, A/D hold a turn, and the raft keeps sailing when you leave the helm. It stops on its own if nobody is within 64 blocks or it would sail into unloaded land.
- **Trees count as one block:** a tree grown from a sapling on a vessel counts as a single block toward the limit, however big (its weight still counts). Logs you place yourself still count one each, even next to a tree. Trees grown on land before assembling count per log.
- Guide book: new Cruise Control page and Farming Afloat entry.

## 1.0.1-alpha
- **Fixed:** minecarts (chest and hopper carts) on a vessel's rails weighed nothing and didn't count toward the block limit, so a raft could carry unlimited storage. Minecarts can no longer be placed on vessels ("Minecarts can't be used on vessels"); rails can still be used as decoration.

## 1.0.0-alpha
First alpha: tier 1 (rafts).
- **Rafts:** up to 64 blocks, one Rudder, up to 3 blocks/s (rudder 1 + sails 2). A finished sail counts as one block.
- **Building on water:** Sealed Barrel (floats 10% better than a log), Stone Keel and Metal Keel (ballast). All place on blocks or straight onto water. Keels and the rudder can be disguised as any full block (strip with an axe to change it).
- **Sails:** built on a mast with string, yards and wool carpets; dye them in place.
- **Mooring:** a lead from a fence post on the raft to one on shore.
- **Gauge:** shows a ship's centre of gravity, weight and fore/aft balance, before or after assembly.
- **Ultimate Guide to Aquanautics:** Patchouli book (Sealed Barrel + Book).
- Block weights in Jade, and in item tooltips (advanced tooltips on, hold Ctrl).
