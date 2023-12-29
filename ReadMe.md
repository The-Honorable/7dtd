# Mods that are not included but also being used
- Doughs-UI-RemoveDayAndTime
- KHA21-12CraftQueue
- KHA21-FoodWater
- KHA21-HPBars
- KHA21-LockableInvSlots
- KHA21-RemovePOINames
- KHA21-RemovePOINamesTracker


# Changes included in the mod

## Biome changes

### Snow biome is much colder in all weather patterns, also adjusted the probability of each weather type
- default = 30 from 44
- fog = 20, from 8
- snow left at 40
- storm = 10, from 8
- default min temp changed to 18 from 26
- fog min temp changed to 12 from 20
- snow min temp changed to 9 from 18
- storm min temp changed to 0 from 12
- overall more precipitation when it snows/storms
- overall more fog during foggy times
- overall more wind base +10

### desert biome is much hotter unless it rains, weather probability left default
- default max changed to 120 from 105
- rain min changed to 80 from 95
- rain max changed to 95 from 105
- storm min changed to 70 from 95
- storm max changed to 80 from 105
- added fog/dust to desert biome
- increased amount of fog and wind overall


## Trader Changes

### goal here is to make exploring the preferred method of obtaining items vs quest and buying items
- Price trader sells things adjusted from x3 to x5
- price trader buys things adjusted from .2 to .15
- disabled trader dialog to offer quests
- disabled trader is open/closed blocks which were loud af

## Player changes

### Overall, player is slightly faster, gains slightly less exp, uses slightly more water/food and adjusted starting items
- Increase base player speeds by 10%
- walkspeed changed to 1.7 from 1.53
- runspeed changed to 1.2 to 1.1
- crouchspeed changed to 1.1 from 1.04
- starting items changed to drinkJarBoiledWater=5,foodCanChili=5,meleeToolTorch,armorSantaHat
- playerexp gained from upgrading changed from x5 to -.5 (changed from 5x exp to half exp)
- playerexp gained from harvesting changed to -.3 (30% reduction)
- playerexp gained from killing changed to -.1 (10% reduction)
- playerexp gained from selling changed to -.9 (90% reduction, didnt even know selling things gave exp)

### Perk changes
- well insulated nerfed to 5,10,15 from 10,20,20 for hypo/hyperthermal resists
- well insulated perk level 3 requirement changed to level 10 from level 7

### Survival Quest changes
- skills points changed to 3 from 4 for completion

### Gamestage changes
- daysAliveChangeWhenKilled changed to 10 from 2
- difficultyBonus changed to .5
- lootBonusEvery changed to 25


## Animal changes

### the wife wants to basically only hunt in this game, so chickens/rabbits are nerfed
- chicken movementspeed when panic changed to 1 from 1.3
- rabbit movementspeed when panic changed to 1.2 from 1.55
- chicken sizescale changed to 1.3 from 1 (30% bigger)
- rabbit sizescale changed to 1.3 from 1 (30% bigger)


## Zombie changes

### Goal is disable blood moons and make zombies a constant threat
- remove zombies ability to climb ladders
- overall zombie spawns increased roughly 3x
- downtown and commercial zombie spawns increased 3-5x

## Item changes

### overall reduces gamestages and removing trader quests/increasing prices will increase the reliance on bows/melee. slight buff to them all
- increase stack size of most things
- bullets stack to 1k
- resources stack to 10k

### spear changes
- spear normal attack range increased to 3 from 2.6
- spear power attack range increased to 4.0 from 3.6

### sledgehammer changes
- meleeWpnSledgeT0StoneSledgehammer normal attack stamina loss changed to 15 from 22.3
- meleeWpnSledgeT1IronSledgehammer normal attack stamina loss changed to 22 from 36.7
- meleeWpnSledgeT3SteelSledgehammer normal attack stamina loss changed to 30 from 40.5
- meleeWpnSledgeT0StoneSledgehammer power attack damage changed to 1.5 from 1.25
- meleeWpnSledgeT1IronSledgehammer power attack damage changed to 1.5 from 1.25
- meleeWpnSledgeT3SteelSledgehammer power attack damage changed to 1.5 from 1.25

### fist weapon changes
- all fist weapon attacks per minute changed to 110 from 100
- all fist weapon mod power bonus changed to .2 from .1
- all fst weapon power attack changed to 1.2 from 1
- meleeWpnKnucklesT0LeatherKnuckles entity damage changed to 10 from 7
- meleeWpnKnucklesT1IronKnuckles entity damage changed to 17 from 11.5
- meleeWpnKnucklesT3SteelKnuckles entity damage changed to 28 from 19

### knife/blade changes
- all knife attacks per minute changed to 135 from 120
- meleeWpnBladeT0BoneKnife entity damage changed to 7 from 5
- meleeWpnBladeT1HuntingKnife entity damage changed to 17 from 12
- meleeWpnBladeT3Machete entity damage changed to 30 from 20
- meleeWpnBladeT3Machete attacks per minute changed to 70 from 55


### Bow changes
- gunBowT0PrimitiveBow DamageFalloffRange changed to 40 from 20
- gunBowT0PrimitiveBow MaxRange changed to 120 from 100
- gunBowT0PrimitiveBow sneak damage bonus changed to 2.5 from 2
- gunBowT0PrimitiveBow ModPowerBonus changed to .2 from .1

- gunBowT1WoodenBow DamageFalloffRange changed to 55 from 25
- gunBowT1WoodenBow MaxRange changed to 120 from 100
- gunBowT1WoodenBow sneak damage bonus changed to 2.5 from 2
- gunBowT1WoodenBow ModPowerBonus changed to .2 from .1


- gunBowT3CompoundBow DamageFalloffRange changed to 70 from 34
- gunBowT3CompoundBow MaxRange changed to 150 from 100
- gunBowT3CompoundBow sneak damage bonus changed to 2.5
- gunBowT3CompoundBow ModPowerBonus changed to .2 from .1


- gunBowT1IronCrossbow DamageFalloffRange changed to 95 from 28
- gunBowT1IronCrossbow MaxRange changed to 170 from 100 
- gunBowT1IronCrossbow sneak damage bonus changed to 2.5 from 2
- gunBowT1IronCrossbow ModPowerBonus changed to .2 from .1

- gunBowT3CompoundCrossbow DamageFalloffRange changed to 110 from 40
- gunBowT3CompoundCrossbow MaxRange changed to 200 from 100
- gunBowT3CompoundCrossbow sneak damage bonus changed to 2.5 from 2
- gunBowT3CompoundCrossbow ModPowerBonus changed to .2 from .1


### Healing item changes
- medicalFirstAidBandage healing changed to 15 from 30
- medicalFirstAidKit healing changed to 90 from 180
- drugHerbalAntibiotics infection cure % changed to 7 from 10
- drugAntibiotics cure % changed to 15 from 25

### armor changes
- santa hat cold resist changed to 12,14 from 21.5, 25.5
- Heavy Military armor mobility penalty increased to -.05 from -0.4
- Heavy scrap armor mobility penalty increased to -.06 from -0.6
- Heavy iron armor mobility penalty increased to -.07 from -0.6
- Heavy steel armor mobility penalty increased to -.08 from -0.6


### Skill Magazine Changes
- skill magazines add 2 progression levels instead of 1 now


## loot changes

### water filter is slightly more common now, same with acid
- water filter changed from low to medlow
- acid changed from verylow to low


## Vehicle changes

### things go faster
- bicyle velocity max changed to 8, 5 from 6,4
- mini bike velocity max changed to 11, 5 from 7,4
- motorcycle velocity max changed to 13, 8 from 9.33, 6
- truck velocity max changed to 13, 8 from 9.33, 9
- truck DegradationMax changed to 12k from 8k



