## Mod Structure ##

Folder hierarchy goes from 0-5,
0 is required for 1,
1 is required for 2,
2 is required for 3, etc.

--------------
---CONTENTS---
--------------

0-ReferenceGuide
	- Contains overview information for how to work this mod.

0-SCore_GVmod
	- expands functionality and tags in Vanilla 7DTD with minor
	modifications by Goldmanvision (thanks Sphereii!)

1a-SphereII NPC Dialog Windows
	- creates better UI dialog windows for NPC interaction.
	Without this, XNPCCore dialog doesn't display right.

1b-XNPCCore_GVmod
	- expands functionality of SCore NPCs with minor
	modifications by Goldmanvision.

2-SoldierPack_GVmod
	- adds 4 base "soldier" and 1 base "officer" NPCs to the XNPCCore with minor modifications by Goldmanvision.

3a-GVmod_ProjectTemplates
	- adds a template project with SCore and XNPCore. No flavor text.

3b-GVmod_ImmerSim
	- A collection of mods that adds elements of the game for more realism and immersion.
	Elevators, weapons, items, blocks, and more. Full feature list and creator credits available in folder.

3c-GVmod_ModderBackpack
	- a collection of modded blocks and items with specified functionality to fit a wide
	variety of modding purposes with minimal amounts of code. Some blocks and items are
	templates, but most are ready to use in the Prefab Editor or Debug Mode.

4-GVmod_AECv100
	- a proof of concept project with all above mods in a polished presentation.
	All the flavor text. Mmm... flavor text...

5-GVmod_NiftyTags
	- collection of tags and code snippets to copy and paste into your modlet XML.
	This folder does not effect the game or mods. Serves as a cheat sheet.

--------------
-----NOTES----
--------------

When building your own project, folders 4 and 5 are not required in the final build.
Rename folder 3-GV_Mod-ProjectTemplates to whatever you want to call your mod.

Documentation on SCore can be found here.

	A small update was made by Sphereii to expand
	functionality of dialog actions with NPCs allowing
	for NPCs to use action="AddItemSDX" to place an item
	in the PLAYER INVENTORY.

Documentation on XNPCCore can be found here.

Documentation on SoldierPack can be found here.

	Updates were made by Goldmanvision to expand the NPC names,
	factions, and other properties. A full list of changes and
	additions can be found in the XNPCCore_GVmod and SoldierPack_GVmod folders.
