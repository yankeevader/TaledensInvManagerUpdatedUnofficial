# TaledensInvManagerUpdatedUnofficial 
My goal is to create a companion mod for TIM that will dynamically update the script

What does the Companion Mod do?

This mod is a comprehensive configuration gathering tool for Space Engineers that:

Scans the entire game and installed mods to collect detailed information about:

Specifically it will read the data from assemblers and refineries (including basic and survival kits)

Ore mappings (how ores refine into ingots)
Item types
Crafting/production recipes
Game and mod-specific item definitions


Dynamically generates a compact configuration that can be used by Programmable Blocks (PBs)
Automatically updates the Custom Data of all Programmable Blocks with this configuration - will probably change this to conform to the [TIM] tag system
the script would need modification to tag the PB it is running on with the [TIM] tag, this would allow the mod to focus on only specific programmable blocks running TIM

Key features:

Collects vanilla game item and recipe information
Attempts to extract additional data from installed mods
Creates a standardized, compact configuration format
Provides a dynamic way to update item and recipe information across all PBs
Supports both vanilla and modded game content

The primary purpose is to enable the Taleden's Inventory Manager script to have up-to-date, comprehensive information about game items, recipes, and ore conversions without manual configuration, making the script more flexible and adaptable to different game setups and mods.
