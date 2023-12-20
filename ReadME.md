# Quake Rancher
---
## Overview

You’ve landed at your target location. The planet is desolate, quiet, and has no coffee shops anywhere! But you did not come here just for coffee. You came for slimes. Massive colonies of slimes of all types have been discovered on the planet, and it's yours for the taking. The slimes need housing and nourishment in the form of food launched at them at high velocity to produce the new resource Quorts that can be sold on an ever evolving exchange market. Make profit, build and improve your ranch and build the first coffee shop on this planet.

This is a mod made for a class.
---
## Deliverables
- [x] 10 different raiseable slimes
- [ ] 5 Different farm tools (plots, water tanks)
- [ ] Economy system [Food ammo]
- [x] Vaccum Gun modified from the Hyperblaster
- [x] Five components of coffee shop to achieve the winning condition
      
- [X] A shortcut to auto launch into the mod
- [ ] Help Screen to detail how to play your mod in game
- [x] README file in GIT that explains HOWTO install and play/test your mod
- [ ] Updated in game UI to showcase one or more of the mod features
- [X] Mod in seperate folder
---
## Goals
Slimes will drop quorts when the correct ammo (fruit, meat, or veggie) is shot at them. 
1. 10 Slime types
<br>1. Pink (Medic) - Fruit
<br>2. Yellow (Soilder) - Veggie
<br>3. Gray (Gunner) - Meat
<br>4. White (Mutant) - Fruit
<br>5. Blue (Infantry) - Veggie
<br>6. Green (Parasite) - Meat
<br>7. Red (Brain) - Fruit
<br>8. Orange (Flipper) - Veggie
<br>9. Purple (Berserk) - Meat
<br>10. Tarr (Gladiator)

3. Market
<br>QEM (Quort Exchange Market)
<br>Quort exchange system using Console UI
<br>*Use commands buyfloors, buywalls, buyroof, buydoor, and buycoffee*
<br>Complete the cafe and win the game 

5. Base and Tools
<br> Corral - holds slimes/or chickens
<br> Garden - grows fruit/veggies
<br> Jetpack - for reaching higher places
<br> Silo - Hold excess food

7. Vaccum Gun
--*4 slots for…*
<br>1. Food
<br>2. Slimes
<br> Shoots current slot’s contents

---
##What was accomplished
Have a shortcut to mod that launches through Steam
Mod in separate folder named cerulean
README file in GIT that explains HOWTO install and play / test your mod including needed commands and required gun functions
Ten slime types: Made slime types different enemies that are supposed to drop different quorts ( instantly sold for money ) depending on their color
Two of Five tools: A jetpack and a portable teleporter attached to the shotgun. Shoot to save a location then press hte middle mouse button to teleport back. Jetpack is activated after binding the 'j' key.
Economy market: "Food" replaces ammo types bullets (fruit), slugs (veggies), and meat (rockets). Models swapped to reflect change. Machine or chain gun for fruit, Railgun for veggies, and rocket launcher for meat.
Vacuum Gun: Modded Hyperblaster. Pulls enemies to the gun and entities vanish into the gun. 
Cafe parts: Made commands that purchase parts and subtract from the player's wealth. Done through the console.


##Did not complete
Game crashes when attempting to open Help screen. Possibly do to error tracking certain variables on display
UI changes to display mod features are also not working completely because variables are not tracked properly
Vacuum Gun can pull enemies but cannot shoot them out. Not able to create null ammo slots and shoot the different types.
Other tools were to be a garden plot, slime pen, chicken coop and silo. Ran out of time to adjust models needed.
Made quorts for each color type and attached value based off the health pack, but attempting to spawn the item thorough console alone causes the game to crash

---
## Download Instructions
      Compile and build the Game folder under release and add the 'game.dll' file to a new folder with the name 'cerulean' in the Quake 2 folder. From the 'baseq2' folder copy the 'config.cfg' folder and place in the mod folder. In the config file change the following key binds: bind h "cmd help", bind MOUSE3 "cmd ldteleport", bind j "cmd thrust".
---

