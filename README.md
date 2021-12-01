Popcorn Battle Armor
====================

An addition to RogueTech that reduces the armor values of all battle armor to near-tabletop values, within reason.

Installation
------------

 1. Download the repository.
 2. Open your Steam\steamapps\common\BATTLETECH\Mods folder
 3. Paste in the folders.
 4. Overwrite any existing JSON files.

Repeat after every RogueTech update.

Methodology
-----------

 * Total armor = Armor value from sheet * Number of Units * 5
 * Armor per location = Total armor divided amongst mech locations, prioritizing arms and torso before legs and head.
 * Rear armor approx half of front armor value, rounded down to nearest 5, max 10.
 * Structure approx half of front armor value, rounded down to nearest 5.

Example
-------

Inner Sphere Standard Battle Armor <Base>:

Total  armor = 9 points * 4 units * 5 = 180
 * Head: 15 armor, 5 structure
 * LA: 25 armor, 10 structure
 * LT: 25 armor, 10 structure
 * CT: 25 armor, 10 structure
 * RT: 25 armor, 10 structure
 * RA: 25 armor, 10 structure
 * LL: 20 armor, 10 structure
 * LL: 20 armor, 10 structure
