9 Hands
==============
An RPG/Tactics/Card game developed for mobile devices.
**IT IS HIGHLY RECOMMEND TO READ THROUGH ENTIRELY, AS THERE IS NO TUTORIAL IN GAME.**
Early alpha demo for [Android](https://github.com/GAT27/color9hands_experiment/blob/master/Experiment_9Hand-Default-1.0.0.apk?raw=true)
and [Windows](https://github.com/GAT27/color9hands_experiment/blob/master/Experiment_9Hand-Default-1.0.0.exe?raw=true) available.
Note that there are no animations or effects yet.

#Gameplay:

* Tap on your units on the left to move about and attack the enemy units on the right.

* Tap on the bottom right corner to draw a random trinket to help out your units.

* Defeat all the enemies to proceed to the next stonger wave.

* Units gain some hp and a skill back after each wave, with one leveling up.

* If the mage is defeated, the game is over.

#Interface:

1. Each friendly unit has the following stats around them:
  * **Top-left** Ammo count and rate of fire
  * **Left** Skill points/skill cap and effective defensive/current armor
  * **Bottom** Current courage level and hp bar
  * **Bottom-Right** Unit number
  
2. Enemy units have their health shown and which units are attacking them.

3. Bottom row show your current trinkets (max 9 at a time) along with the current wave, blood money, and scrap.
  * Trinkets are gained by using 100 blood money each.
  * Bloody money is gained by defeating enemies, but only up to 1000 can be stored.
  * Scrap is gained by recycling trinkets and used for fixing weapons, changing tools, and creating souls.
  * Recycling trinkets is done by double tapping a trinket.
  * Select trinkets to use on other trinkers, drag trinkets to use on the playfield.
  * Selecting the mage switches the bottom row to allow spell casting.

#Attacking and Defending:

* Except for the mage, each friendly unit attacks by selecting it then selecting an enemy, then the unit will auto attack until the enemy is defeated.

* Cancel attacking by double tapping the friendly unit.

* Enemies will show where they will attack, you can either move out of the or take the attack.

* Each friendly unit type has different ways of movement, though attacking is paused when this is done.

#Movement:

* Melee units move by selecting them then tapping an empty spot, in which they will walk to.

* Range units move by swiping across them horizontally or vertically, dashing towards their new spot.

* Mage unit move by selecting them then tapping an empty spot, instantly teleporting to it.

#Melee Units:

1. Each one has a special that uses 1 skill point that is done holding on it.

2. **Berserker**

  * 3rd Strongest Attack

  * 4th Fastest Attack

  * Passive: Attack speed increases as health is lowered

  * Special: Buff attack, speed, and defense, and transfer all buffs to friendly units

3. **Twin**

  * 5th Strongest Attack

  * Fastest Attack

  * Passive: Havles attack and targets a second random enemy

  * Special: Quickly attacks random enemies 9 times while being invulnerable to damage

4. **Hammer**

  * 2nd Strongest Attack

  * 5th Fastest Attack

  * Special: Do one large burst damage to selected target

#Range Units:

1. Each one has a passive special that uses 1 skill point.

2. **Arrow**

  * Weakest Attack

  * 2nd Fastest Attack

  * Special: Has a chance to dodge damage when hit

3. **Gun**

  * 4th Strongest Attack

  * 3rd Fastest Attack

  * Passive: Attack is spread out to all enemies but overall attack is increased when more enemies are present

  * Special: Has a chance to gain scrap when attacking

4. **Cannon**

  * Strongest Attack

  * Slowest Attack

  * Special: Has a chance to do increased damage to selected target when attacking

#Mage:

1. Already implemented 12/13 spells, will add description later.

#Trinkets:

1. Already implemented 10/10 trinkets, will add description later.

#Bugs:

1. During soul linking process, starting unit is destroyed. {Known fix not yet implemented, crash}

2. With soul link active, end target is destroyed and start target is damaged. {Known fix not yet implemented, crash}

3. Nothing for air 2 cast. {Nothing to test with yet, runs normally}
