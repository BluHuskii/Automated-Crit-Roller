# Crit Roller
Do you find yourself forgetting to roll on the critical hit table? The critical fumble table?
Do you find yourself forgetting to roll that pesky loot table after each monster dies?

Then you're like me and this mod is what you need!
Critical-fumble will automatically roll on the critical hit tables in the event of a critical hit! Each hit rolls a special table depending on the type of damage.

Additionally, every time a *targeted* monster is felled by your players, the CR table is rolled! 
To further your convience, the coins dropped can be automatically distributed to your players. This option can be ignored though!
The original credit for the module goes out to JacobMcAuley for the crit tables and the original macros. Myself and Alejo160 on Reddit made a few changes to make the module easier to set up and created a macro to 90% automate the rolls.

## Features:
See the [examples](##Examples) for video demonstrations!
The following features are offered by Critical Fumble. Any feature marked with a **(T/F)** can be disabled or enabled.
1. Critical hits on 20s for any of the values in the [Critical Tables](##Tables) **(T/F)** 
2. Critical fumbles on 1s **(T/F)**
3. Audio based off the damage type on critical hits **(T/F)**
4. LootTable rolling on target creature death **(T/F)**
5. LootTable distribution of wealth to active PCs **(T/F)**
6. Private rolls on both Critical Fumble and Critical Fumble Loot **(T/F)**

## Incompatibilities

Due the requirement of knowing the damage type, I overloaded Dice5e.roll(). If any module overrides this method as well, they will be incompatible. 

## Installation:

To install Critical-Fumble, do the following:

1. [Download the zip file](https://github.com/JacobMcAuley/critical-fumble/archive/master.zip)
2. Extract the folder to your 'public/modules' in Foundry VTT.
3. Reload your application.

Auto-Installation Instructions:

1. Copy this link: https://github.com/JacobMcAuley/critical-fumble/raw/master/module.json
2. Open FoundryVTT and navigate to Add-On Modules
3. Select "Install Module" and paste link into textbox.
4. Click "Install" and watch as the mod is installed
5. Inside of your FVTT game world, navigate the the gears in the top right corner.
6. Select "Manage Modules" and enable Critical Fumble
7. Copy + Paste the Crit Call macro from the CritCall.txt to a new macro on your macro bar
7A. Please DM me if you run in to issues at BluHuskii here on GitHub or on Reddit BluHuskii#0978 on Discord
8. Enjoy!

## Usage

To use Critical-Fumble make sure you've installed the mod using the instructions [here](##Installation).
Critical fumble should be loaded and ready to go upon enabling. To verify, simply check to see if the RollTables were successfully imported. (**NOTE:** You may find that the values display an incorrect number of entries in the table. This is okay and can be disregarded).

**Using Criticals**
To use Critical hits, wait until a player rolls a 1 or the critical range (Player dependent) and the table will be automatically rolled for you!
For spells, be sure that a ranged spell attack is set up, otherwise no table will be rolled.

**Using the LootTable**
Creatures (NPCS) that have a CR level and are targeted using the targeting system will result in a roll on their corresponding CR table once they hit 0hp or lower.

## Tables
The follow tables are included within the module and imported upon start:

**Criticals**
1. Bludgeon
2. Piercing
3. Slashing
4. Acid
5. Cold
6. Fire
7. Force
8. Lightning
9. Necrotic
10. Poison
11. Psychic
12. Radiant
13. Thunder

**Special Tables**
1. Major Injuries
2. Minor Injuries
3. Insanity

**Loot**
1. CR 0-4
2. CR 5-10
3. CR 11-16
4. CR 17+

**Fumbles**
1. Fumble

Currently, there is no table for fumbles on spells. All fumbles share the same Critical-Fumble Fumble table. If anyone is interested in creating a relatively balanced table and would like to incorporate fumbles on spells, feel free to contact me through Discord found through the Feedback section below.


### Table modifications?

If you would like to adjust the table, you should be able to in most instances! Due to recent structure changes in the program. You'll need to adjust any changes in the .db files in the module directory. Look for any of the optional flags for any of the loot based rolls.

Otherwise, you can modify the values in the tables as desired via FVTT.

## Attributions

Super special thanks to [Kakaroto](https://www.patreon.com/kakaroto/) for his code review!
Sound effects obtained from [Zapsplat](https://www.zapsplat.com)  
SVGs obtained from [FontAwesome](https://fontawesome.com). You can find the license by clicking [here](https://fontawesome.com/license)  
Icon-Sword made by [freepik](https://www.flaticon.com/authors/freepik) from [flaticon](https://www.flaticon.com/)  
Icon-dagger made by [srip](https://www.flaticon.com/authors/srip) from [flaticon](https://www.flaticon.com/)  
Icon-psychic made by [Smashicons](https://www.flaticon.com/authors/Smashicons) from [flaticon](https://www.flaticon.com/)  
Critical tables made by [Benjamin Huffman](https://sterlingvermin.files.wordpress.com/2016/09/critical-hits-revisited.pdf)  
Map used in video made by [Cze and Peku](https://www.patreon.com/czepeku/posts)

## Feedback

This module is still in the testing phase and is likely to have unexpect bugs or weird interactions. Please remember to back up your systems before trying new modules. If any gamebreaking or unexpected behavior occurs, please contact me on Discord through PM or the FVTT (preferred) with the name JacobMcAuley#3461. Thank you for trying out Critical-Fumble!

# Donate
Please donate to the origional creator of the module JacobMcAuley here on GitHub!
