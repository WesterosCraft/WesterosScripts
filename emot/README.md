# WesterosCraft WE Scripts

Scripts are all free for use and modification.

## How to install:

### Install Liteloader and Macro/Keybind mod

#### Old Launcher

* Download [Liteloader] (http://www.liteloader.com/download#) for Minecraft 1.11.2. Use the "Extract" method, and give it the path `AppData\Roaming\WesterosCraft\instances\WesterosCraft-1.11.2\mods` (or the OSX equivalent).
* If WesterosCraft crashes after this step, you might need to allocate more memory in the launcher settings.
* Download the [Macro/Keybind mod](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1275039-macro-keybind-mod-1-11-2-version-available) for Minecraft 1.11.2.
* Install the Macro mod by moving the downloaded mod file to `AppData\Roaming\WesterosCraft\instances\WesterosCraft-1.11.2\mods`
* Download the scripts from this repository by clicking on the download icon (on the top right, next to "find files".)
* Extract the download, and move the script .txt files inside to `AppData\Roaming\WesterosCraft\instances\WesterosCraft-1.11.2\liteconfig\common\macros`

#### New Launcher

* Go to the launcher settings.
  * Click the Mods tab.
  * Scroll to Optional Mods.
      * Enable Liteloader
      * Enable Macro/Keybind Mod
  * Click Done
* Download the scripts from this repository by clicking on the download icon (on the top right, next to "find files".)
* Extract the download, and move the script .txt files inside of the following folder:
  * Windows: `AppData\Roaming\.westeroscraft\instances\WesterosCraft-1.11.2\liteconfig\common\macros`
  * macOS: `~/Library/Application Support/.westeroscraft/instances/WesterosCraft-1.11.2/liteconfig/common/macros`
  * Linux: `/home/.westeroscraft/instances/WesterosCraft-1.11.2/liteconfig/common/macros`

### In-Game Setup

* Start minecraft. Open the menu for the Macro/Keybind mod.
* Here you have options: You can either use the Key Bindings page, or you can use the GUI Editor (which you can use to make a page of buttons appear which you click to activate macros).
* Whichever one you choose, when it opens a page saying "Edit macro binding for ...", enter the following: `$$<test.txt>`, where you replace test.txt with the name of the script you want. For instance, if I wanted the "wheatnbarley.txt" script, I would enter `$$<wheatnbarley.txt>`.
* The field scripts are generally simple: Paint the surface of an area with a placeholder block, select it, run the script, and enter the necessary inputs.
* Explanations for the more complicated scripts can be found [here](http://westeroscraft.wikia.com/wiki/Terraforming_Guide).