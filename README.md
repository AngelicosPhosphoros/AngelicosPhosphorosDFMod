# AngelicosPhosphorosDFMod
This is a simple mod for Dwarf Fortress.

Main discussion thread (in Russian): http://forum.dfwk.ru/index.php/topic,2012.0.html
##Changes

### MAGIC

#### Wizards
Wizards is new type of interactions. They are very like to vanilla necromancers (which active too), but can improve their stats and skills.
They are immortal and have some spells:
* Hurl fireball
* Exorcism - remove tag NOPAIN from undead and make them suffer. Also significantly decrease speed, agility and strength.
* Create worker - create special creature from any corpse. Added only to allow wizards to build their towers and must be removed.
Secrets of magic are given by gods of wisdom, nature and light.
Also they have better disease resistance and some mental stats than average people. Also, they learned to enter martial trance.
They shown as blue N with ~

#### Dark Mages
Dark mages is more powerful version of necromancers. However, they worship gods of chaos, not death.
They have much better physical and mental attributes than normal people.
As wizards, they have immortality and some spells:
* Create servant - creates wraith (see next) from good corpses
* Raise a zombie.

#### Dark servants (wraithes)
Wraithes is undead servants of dark mages. They don't feel pain, emotions and they don't need to eat, drink or sleep. However, they are not dummy dulls as zombies. They can though.
Dark servants have more physical strength than living, but they weaker than dark mages and can't improve themselves.
They have some spells:
* Create ghoul - creates ghoul, fast, strong and tough undead. However, they have halved kinestic sense.
* Raise a zombie.

*General tips:* One person can be a wizard and dark mage at one time, but this is only player. Also, wizards can be werebeast or vampire. Both types of mages live in towers and write books.

### CIVILIZATIONS

There are a lot of changes. Now elves are playable in fortress mode and humans can use steel and have trade diplomat. Also added ability to create leather whips and scourges for all civs.

#### Changes of dwarves

There are not a total changes. You can play as always, but they able to create more types of weapons, uses alchemy and have new metals.
Non vanilla weapons:
* Heavy crossbow. Better in close combat, but heavy.
List of new metals:
* Cobalt. Used in dwarven steel production.
* Nickel steel. Produced from 2 iron, 2 pig iron, two flux and nickel bar => 5 bars output. Better than steel as armor.
* Dwarven steel. Produced from 4 iron, 4 pig iron, 2 steel, 4 flux, 6 fuel, 1 cobalt, 1 nickel, 1 copper and 2 adamantine wafers => 15 bars output. Very good weapon and armor metal, cost 160.
Alchemy:
* Used alchemist skill.
* Alchemist lab is needed. Builded from 10 vials, 2 barrels and boulder.
* Philosopher's stone. Very nice and expensive material. Basic cost ~ 250000. Cannot be used as material. To create one bar you need 100 bars of platinum, gold, silver, iron and copper each and 50 boulders of cinnabar. Also, success chance is 10%. Anyway, you can buy it.
* Transmutation of silver to gold. Require something from philosopher's stone as catalyst (which can be used more than one time).
* Transmutation of copper to iron. Require catalyst (philosopher's stone).
Other reactions:
* Encrusting of weapons, shields and armor.
* Creation of wax candles.

#### Elves

There are lot of changes, so you can gain some new experience.

First of all, they have less choice of weapons: only bows, swords, daggers and spears. Also, they have unique weapon - edged bow with two slashing and two piercing attacks.
Second main thing is very specific craft system.
Elves cannot dig, use smelters, mechanisms and forges. However, they have very good materials.
The craft system is based on farms and enchantry.
Firstly, you need special elven wood in farms. Seeds of this plant produced in enchanter's pentagram from any logs (use your wagon). It can be growed whole year.
After growing plant, produce logs in wood grovery workshop.
Elves can form logs into weapons and armor in weaponist workshop but this production is very poor in battle. To improve this, they use enchanter's pentagram. Resulting product are useful enchanted wood items.
Also, enchanted wood items can be improved by creation of moon metal items. Ritual require 5 candles and enchanted wood item.

The last important thing is social organization. You have expedition leader - chief, militia commander with 15-members squad and lieutenants with 5 rangers squads.
Also, there ate druid, quenn and princess in capital. All nobles don't have any requirements or mandates.


P.S. For internal mechanics philosopher's stone, enchanted wood and moon metal is metals.

### ARENA FIGHTING TESTS
#### Testing interactions
*1 wizard vs 5 ghoul, 5 wraith, 1 dark mage*:
No one won this battle, dark mage dead. I stopped test after 1 hour.
*1 mummy vs 3 wraith, 1 dark mage*:
Mummy won.
*1 mummy vs 5 wraith, 1 dark mage*:
Mummy dead.

#### Material test results
*Cutting weapon*:
Adamantine > dwarven steel > moon metal > steel, nickel steel > enchanted wood.
*Blunt weapon and shields*:
Steel, nickel steel > dwarven steel > moon metal, enchanted wood > adamantine.
*Armor*:
Adamantine > dwarven steel > nickel steel > steel.

## File format
All new files have `_AngelicosPhosphoros`suffix, all new objects have `APh_` prefix.
