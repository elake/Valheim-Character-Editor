# Location Editor

* This is a fork of Valheim Character Editor, with minor changes added to edit the location of your character.
* I made this change for myself after our server disconnected while we were on a boat, and everyone was stranded in the ocean.
* It works just like the original valheim character editor:
  * Select your character
  * Select your world
  * Enter a new location
  * Save
* I didn't add any input validation or error handling, so don't enter any invalid values.
* Make sure to back up your character files in case something goes wrong. 
 
Below is the readme from the original repo, with the screenshot swapped out to reflect my change.

# Stuck in the ocean?

If you don't have anyone at your base to fetch the coordiantes, try this:
 1. Make a new character and connect to your world.
 2. Go to your base.
 3. Log out, and use this to get the coordinates from the new character.

# Valheim Character Editor

This repository is licensed under the GNU General Public License v3.0.

![alt text](https://raw.githubusercontent.com/elake/Valheim-Character-Editor/main/GUI.PNG)

This program creates a backup of your character data with each application. If you happen to lose your character or anything related to it, you can go to "C:\Users\\[username]\AppData\LocalLow\IronGate\Valheim\characters" and recover it.

Tested on Valheim 0.146.11 and Windows 10 x64 20H2. Not tested online.

Always use at your own risk. I am not responsible for the lost of any information from your character or any other harm to your copy of Valheim.

Related to the skin colors, please note that the default in-game skin tone is limited to a gray scale from 0% to ~70% black. Take this in mind when applying a new color so you can get the desired tone.

# Usage
  1. If Valheim is running, close it.
  2. Open ValheimCharacterEditor.
  3. Choose your character and the new customization you want to apply.
  4. Apply the customization.
  5. Enjoy.
 
# Known problems
  - Steam sync seems to be causing problems like character duplicates or restoring your character file. Disabling it is recommended.

# Whats coming next
  - Inventory editor.
