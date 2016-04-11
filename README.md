# w3-SortQuests
Witcher 3 mod to sort the list of quests by level.

# Building
Currently built using ScriptStudio. Extra blob content is not copied, remember to do this yourself

# Installing

Copy the modified scripts to your Witcher 3 Mods folder, under a new folder for this mod.

The structure should be:

The Witcher 3 Wild Hunt
|- _redist
|- bin
|- content
|- DLC
|- Mods
   |- modSortQuests
      |- content
		 |- scripts
		 |   |- game
		 |   |   |- gui
		 |   |      |- menus
		 |   |         |- journalMonsterHuntingMenu.ws
		 |   |         |- journalQuestMenu.ws
		 |   |         |- journalTreasureHuntingMenu.ws
		 |   |- local
		 |      |- questArraySort.ws
		 |- blob0.bundle
		 |- metadata.store