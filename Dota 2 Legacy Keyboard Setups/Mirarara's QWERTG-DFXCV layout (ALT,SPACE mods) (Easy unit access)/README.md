#Mirarara's Compact Layout QWERTG-DFXCV for Easy Unit Access

This layout is forked from Loopuleasa's Super Compact QWERTG-DFXCV v4.3.
I modified the keyboard layout to fit what I need. Mainly the following,
F1 - Select hero
1 - Select all units
2 - Select other units
Alt+3 - Rune Check Shuffle
Mouse 4 - Control Group 1

I modified it from Loopuleasa's layout such that I have easier access to the above functions.
Each file has a role, and modify what you want in it.

The following instruction is a direct copy from Loopuleasa's readme.md.

##Autoexec engine

```
autoexec.cfg
```
- Manages the core functionality of the other files. It's loaded automatically by dota2. 

##dota2_gameplay_mode folder



This folder contains all the .cfg files that are loaded
and they control the game settings and binds as follows:

```
dota2_functions_active.cfg
```
- This file holds all the aliases and custom defined functions made by the use.

```
dota2_keybinds_default.cfg
dota2_keybinds_space_pressed.cfg
dota2_keybinds_alt_pressed.cfg
```
- These three files are full of "bind" commands which connect one key on your keyboard to a function or command.
- Each one of them is responsible for setting the keybinds for either default mode (no ALT or SPACE key pressed), alt mode (ALT+Key) or space mode (SPACE+Key).
- Basically, when you press ALT, the keys from dota2_keybinds_alt_pressed are active, and when SPACE is pressed, the keys from dota2_keybinds_space_pressed are active.

```
dota2_settings_game.cfg
```
- This file contains all the game tweaks and settings (minimap, camera, various toggles, and many options related directly to the game)

```
dota2_settings_tech.cfg
```
- This file contains all the graphical, visual and technical options that are more related to the computer that is running dota2 and not the game itself.

##dota2_hero_custom_configs folder

Inside this folder, you will have hero custom configs that 
you can load by typing a command in the console. 
They're used to add custom keybinds that were designed 
specifically for a single hero. 
Check the readme inside the folder on how to use them.


