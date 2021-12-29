# Mystery Mods
The *Mystery Mods* are a group of mods that can be added and removed individually while still keeping the base mod, the **Mystery Mod**.
These mods will all be **Fabric** compatible mods, there are no plans for Forge implementation.
### The following mods are part of the *Mystery Mods*:
| Name | Description | Status |
| --- | --- | --- |
| Mystery Mod | Base mod of all *Mystery Mods*; required for all other *Mystery Mods* | early stage of developpment/programming & collection of ideas |
| Mystery RPG | new RPG related items such as artifacts, new weapons, armor, enchanmtments, etc. | early stage of developpment/programing & collection of ideas
| Mystery Dungeons | new dungeons and structures, stronghold overhall with entrance to new dimensions (if *Mystery Dungeons Mod* installed) | early stage of idea collection |
| Mystery Dimensions | new Dimensions accesible through stronghold (if *Mystery Dungeons Mod* installed) or through custom portal (single structure or portalbe similar to nether portal???) | early stage of idea collection |
| Mystery Modpack | Modpack, containing all *Mystery Mods* | basically done since no mod has a proper build yet :) |
This table is subject to change and will be updated when changes occur

### Mystery Mod
The Mystery Mod is the base mod of the *Mystery Mods*. It is the heart of the Mystery Mod project and and connects all Mystery Mods together. It includes ingame tutorials to all the different mods as well as a structured config screen to all the settings of the different mods. It aims to be the most lightweight mod out of all of the *Mystery Mods* by not having any ingame affects such as new items, mobs or else. Serverside it will only hold the mods together and generate the config files.
<details><summary>Mystery Mod brainstorming ideas - Click to expand</summary>
<p>
#### Mystery Mod ideas and plan
- Config and help button for all mystery mods on main menu
- Custom config menu on button click with options:
	- Change skin
	- Change GUI (button style, menu background (panorama for every gui, start animation on game launch, etc) and presets for button arrangement (bedrock edition, lunar client, badlion client styles))
	- Advanced (small tweaks such as debug screen toggle in menu, etc.
	- Help (pixel art of NatanDerBratan and Jonas_Jones explaining all the mystery mods (similar to Minecraft Live mob reveals), when clicking on button “Help” the buttons for all other mods will appear
	- Mystery RPG Mod config
	- Mystery Dungeons config
	- Mystery Dimensions config

</p>
</details>
### Mystery RPG Mod
The Mystery RPG Mod aims to generate an RPG vibe by adding new items such as artifacts, altars, weapons, armor pieces, enchantments, etc. The trick here is to balance the item's rareness and power to make some easy to get items not completely overpowered. To achieve that, we use the oldest trick in the book: endless testing.
<details><summary>Mystery RPG Mod brainstorming ideas - Click to expand</summary>
<p>
#### Mystery RPG Mod ideas and plan
- New Items:
	- 5 artifacts (four obtainable in survival):
		- mystery:generic_artifact
			- test-artifact, not obtainable in survival
			- effects: none
	- mystery:mining_artifact
		- obtainable in survival through crafting of 9 different miners artifact shards
		- effects:
			- lvl0 (shards crafted together):
				- passive: none
				- active: haste 1, fortune 1, regen 1
				- active time: 30s
				- recharge time: 1min
			- lvl1 (used lvl0 artifact 5 times):
				- passive: none
				- active haste 2, fortune 2, regen 2
				- active time: 45s
				- recharge time: 1min30s
			- lvl2 (used lvl0 artifact 10 times):
				- passive: fortune 1
				- active: haste 3, fortune 2, regen 2
				- active time: 50s
				- recharge time: 1min45s
			- lvl3 (used lvl2 artifact 20 times):
				- passive: haste 1, fortune 1
				- active: haste 4, fortune 3, regen 2
				- active time: 1min
				- recharge time: 2min
			- lvl4 (used lvl3 artifact 30 times):
				- passive: haste 1, fortune 2
				- active: haste 5, fortune 4, regen 3
				- active time: 1min20sec
				- recharge time: 2min50s
			- lvl5 (used lvl4 artifact 50 times):
				- passive: haste 1, fortune 3, regen 1
				- active: haste 6, fortune 4, regen 4
				- active time: 1min45s
				- recharge time: 3min55s
			- lvl6 (used lvl5 artifact 75 times):
				- passive: haste 1, fortune 3, regen 1
				- active: haste 7, fortune 5, regen 4
				- active time: 2min45s
				- recharge time 4min
			- lvl7 (used lvl6 artifact 120 times):
				- passive: haste 1, fortune 3, regen 2
				- active: haste 7, fortune 6, regen 5
				- active time: 3min45s
				- recharge time: 4min30s
			- lvl8 (used lvl7 256 times):
				- passive: haste 1, fortune 3, regen 3
				- active: haste 8, fortune 7, regen 6
				- active time: 5min
				- recharge time: 5min
		- mystery:_explorers_artifact
		- mystery:???_artifact
		- mystery:???_artifact


</p>
</details>
### Mystery Dungeons Mod
The Mystery Dungeons Mod aims to properly integrate all new items of the other mods into the game by adding loot chests, portal rooms to a number of different dimensions, and overhauling strongholds. It's second purpose is to make the world more explorer friendly as the vanilla game lacks adventures etc. (1.19 kinda changes that though).
<details><summary>Mystery Dungeons Mod brainstorming ideas - Click to expand</summary>
<p>
#### Mystery Dungeons Mod ideas and plan
- There are no real ideas yet other than loot chests, Stronghold overhaul and connection to Mystery Dimensions Mod trough in structures generated portals
</p>
</details>
### Mystery Dimensions Mod
The Mystery Dimensions Mod adds a variety of new Dimensions but there are no real ideas in terms of implementation and dimension types yet.
<details><summary>Mystery Dimensions Mod brainstorming ideas - Click to expand</summary>
<p>
#### Mystery Dimensions Mod ideas and plan
-no real ideas yet :(
</p>
</details>
### Mystery Modpack
The Mystery Modpack is a modpack of all the *Mystery Mods* 
# Credits
These mods have been/ will be coded by me, Jonas_Jones but the project is being realised together with @NatanDerBratan
Credts to him go for all the textures of the mods and at least 50% of the ideas.
