Projectile Retrieval Mod V7
---------------------------

+) Contents
===========
1.    About
2.    (Un)Installation
3.    Known Issues
4.    Thanks to
5.    Version History
6.    Contact Details


+) Section 1. About
===================
  The Projectile Retrieval Mod has a simple aim - to allow the player to retrieve used projectiles. Primarily intended for arrows (though bolts and bullets are supported), the fact that projectile can be retrieved from the environment after use increases the realism of the game (and besides, it's cool to pick up your spent arrows from the bodies of your fallen enemies).

Players can install the retrieval option for any combination of projectiles. Items that count as projectiles, in regards to this mod, are:
  Arrows, bolts, bullets, darts, throwing daggers and throwing axes
Players can choose the percentage chance of a projectile being retrievable - (values are clamped at 0 and 100). NOTE: Only items making a successful hit can be retrieved. Items which miss the target are lost forever.
Players can then further choose which category of the item will be retrievable, with the following options:


Normal items
Only the default item-type will be retrievable, e.g. a plain, non enchanted arrow will be retrievable, whereas an Arrow of Detonation will not be.

All items as normal items
All items will be retrievable as the default item-type, e.g. a plain, non enchanted arrow will be retrievable as a plain, non enchanted arrow, and an Arrow of Detonation will also be retrievable as a plain, non enchanted arrow.

All items as all items
All items will be retrievable as their actual item-type, e.g. a plain, non enchanted arrow will be retrievable as a plain, non enchanted arrow, whereas an Arrow of Detonation will be retrievable as an Arrow of Detonation.

Degrading Enchantment
Based on the THAC0 of the magical item it will be retrieved as the next lowest magical item or plain item.
    An Arrow of Piercing will be retrieved as an Arrow +2
    An Arrow +2 will be retrieved as an Arrow +1
    An Arrow +1 will be retrieved as a plain arrow
    A plain arrow will be retrieved as a plain arrow

Player's secondary choices are:
  1. Plain non-magical items only retrieved as plain non-magical items
  2. Magical & Plain items retrieved as plain non-magical items
  3. Each item retrieved as itself
  4. Magical items retrieved as a lower magical item and ultimately retrieved as a plain non-magical item.

NOTE: Players should uninstall previous versions of the Projectile Retrieval mod before installing this version, to prevent possible conflicts.


+) Section 2. (un)Installation
==============================
The Projectile Retrieval Mod is distributed using the WeiDU distribution package. To install, unzip the iiProjectileR(xx).zip file (where xx represents the version number of the release), to the BG2 main directory. Then run the "Setup-iiProjectileR.exe" file, and follow the on-screen prompts. 

To uninstall re-run the "Setup-iiProjectileR.exe" file, and follow the on-screen prompts, selecting "Uninstall" as required.


+) Section 3. Known Issues
==========================
Party members that get hit by enemy projectiles will have the projectile created in their invetory. I leave it up to you to imagine how and where
they got those items.


+) Section 4. Thanks to
=======================
  + Avenger        - DLTCEP
  + G3             - WeiDU patching code
  + Wes Weimer     - WeiDU
  + Dmitry Jemerov - Infinity Explorer
  + IESDP          - http://iesdp.gibberlings3.net/
  + Immortaity     - www.clandlan.net
  
  Special thanks to Andy B for recoding the mod, and adding several new features and a bug-fix or two.


+) Section 5. Version History
=============================
V7 [01/01/2007]
 - Corrected inability in some situations to modify items introduced by other mods
 - Proper installation for Easy TUTU now available

V6 [08/12/2006]
 - Fixed bug with bullets not being retrieval when using the 'decrementing magic' option

V5 [20/11/2006]
 - Added support for throwing axes, throwing daggers, and darts
 - Added option to retrieve items at lower magical levels
 - Added option to install all items with the same settings at the same time
 - Re-wrote setup.tra file to be less cryptic
 - Removed groups and subcomponents and replaced with action_readln and lists of numerical choices
 - Updated Spanish Translation (Thanks Immortality!)

V4 [n/a]
  - Internal release

V3 [13/10/2006]
  - Added Spanish Translation (Thanks Immortality!)

V2 [30/09/2006]
  - Added ability to specify chance of projectiles being retrievable

V1 [24/09/2006]
  - Initial Release


+) Section 6. Contact Details
=============================
Feedback, comments, queries, questions and suggestion should be sent to bt_igi / igi (Marc Wrench) and/or Andy B
E-mail: igi@mcwrench.com and/or plainolandyb@yahoo.com
WWW   : http://www.teambg.eu
WWW   : http://www.mcwrench.com