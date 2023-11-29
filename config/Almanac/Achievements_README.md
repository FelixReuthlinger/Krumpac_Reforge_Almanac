# Almanac Achievements
Users can customize and create their own achievements by manipulating the files within this folder.
`If almanac recognizes a folder named: 'AchievementData' in config/Almanac folder, then it will use the files within
as data for achievements.`
## Features
- Server shares achievements data to peers
- Create custom passive or active effects
- Create achievements for players to reach
- Use in-game assets to customize your achievements
## Unique Name
Make sure each achievement has a unique name or else it will be ignored - no white spaces, use underscore
## Active vs Passive
If cooldown is set to anything higher than 0, power is set as guardian power. Effects only applied while active, and countdown is running.
## Modifiers
```
Modifier key : description
```
```yml
Attack : Damage multiplier
HealthRegen : Health regeneration multiplier
StaminaRegen : Stamina regeneration multiplier
RaiseSkills : Experience multiplier
Speed : Speed multiplier
Noise : Noise multiplier
MaxCarryWeight : Modify carry weight
Stealth : Stealth multiplier
RunStaminaDrain : Run stamina drain multiplier
DamageReduction : Damage reduction multiplier
FallDamage : Fall damage multiplier
BaseHP : Modify base health
BaseStamina : Modify base stamina
BaseEitr : Additive base eitr
MeleeDMG : Additive melee damage
RangedDMG : Additive ranged damage
FireDMG : Additive fire damage
FrostDMG : Additive frost damage
LightningDMG : Additive lightning damage
PoisonDMG : Additive poison damage
SpiritDMG : Additive spirit damage
ChopDMG : Additive chop damage
PickaxedDMG : Additive pickaxe damage - Only works on ore veins
BluntDMG : Additive blunt damage
PierceDMG : Additive pierce damage
SlashDMG : Additive slash damage
EikthyrPower : On click, switches forsaken power to eikthyr
ElderPower : On click, switches forsaken power to elder
BonemassPower : On click, switches forsaken power to bonemass
ModerPower : On click, switches forsaken power to moder
YagluthPower : On click, switches forsaken power to yagluth
QueenPower : On click, switches forsaken power to seeker queen
```
## Sprite Name
You can use any loaded prefabs (ex:HardAntler) with icons or you can choose from almanac's custom icons:
```
Icon key : description
```
```yml
almanac_bone_skull : white bone skull
almanac_sword_blue : basic sword with a blue hilt
almanac_sword_brown : basic sword with a brown hilt
almanac_arrow : basic arrow
almanac_cape_hood : hooded cape
almanac_bottle_empty : empty bottle
almanac_bottle_blue : bottle with blue fluid
almanac_fish_green : green fish
almanac_bow : basic bow
almanac_necklace : silver necklace with red gem
almanac_mushroom : red mushroom
almanac_gold_coins : stack of gold coins
almanac_key_silver : silver key
almanac_bone_white : white femur bone
almanac_book_red : red book
almanac_bottle_green : bottle with green fluid
almanac_crown_gold : golden crown
almanac_gem_red : red gem
almanac_gold_bars : stack of gold bars
almanac_silver_coins : stack of silver coins
almanac_wood_log : one wood log
almanac_wood_stack : stack of wood logs
```
## Available Trackers - Achievement Type
List of currently available types of trackers to use:
```
achievement type key : description
```
```yml
Fish : tracks total currently known fish - goal irrelevant
Materials : tracks total currently known materials - goal irrelevant
Consumables : tracks total currently known consumables - goal irrelevant
Weapons : tracks total currently known weapons - goal irrelevant
Swords : tracks total currently known swords - goal irrelevant
Axes : tracks total currently known axes - goal irrelevant
Polearms : tracks total currently known atgeirs - goal irrelevant
Spears : tracks total currently known spears - goal irrelevant
Maces : tracks total currently known maces - goal irrelevant
Knives : tracks total currently known knives - goal irrelevant
Shields : tracks total currently known shields - goal irrelevant
Staves : tracks total currently known staves - goal irrelevant
Arrows : tracks total currently known arrows - goal irrelevant
Bows : tracks total currently known bows - goal irrelevant
Valuables : tracks total currently known sellable items - goal irrelevant
Potions : tracks total currently known mead bases - goal irrelevant
Trophies : tracks total currently known trophies - goal irrelevant
Creatures : tracks total currently known creatures - goal irrelevant
MeadowCreatures : tracks total currently known meadow creatures - goal irrelevant
BlackForestCreatures : tracks total currently known black forest creatures - goal irrelevant
SwampCreatures : tracks total currently known swamp creatures - goal irrelevant
MountainCreatures : tracks total currently known mountain creatures - goal irrelevant
PlainsCreatures : tracks total currently known plains creatures - goal irrelevant
MistLandCreatures : tracks total currently known mistlands creatures - goal irrelevant
EikthyrKills : tracks total eikthyr kills - use goal to set up threshold
ElderKills : tracks total elder kills - use goal to set up threshold
BonemassKills : tracks total bonemass kills - use goal to set up threshold
ModerKills : tracks total moder kills - use goal to set up threshold
YagluthKills : tracks total yagluth kills - use goal to set up threshold
QueenKills : tracks total seeker queen kills - use goal to set up threshold
Deaths : tracks total player deaths - use goal to set up threshold
DistanceRan : tracks total distance ran - use goal to set up threshold
DistanceSailed : tracks total distance sailed - use goal to set up threshold
TotalKills : tracks total enemy kills - use goal to set up threshold
TotalAchievements : tracks total achievements - use goal to set up threshold
TrollKills : tracks total troll kills - use goal to set up threshold
SerpentKills : tracks total serpent kills - use goal to set up threshold
CultistKills : tracks total fenring cultists kills - use goal to set up threshold
StoneGolemKills : tracks total stone golem kills - use goal to set up threshold
TarBlobKills : tracks total tar blob kills - use goal to set up threshold
DeathByFall : tracks total deaths by falling - use goal to set up threshold
Trees : tracks total trees chopped - use goal to set up threshold
DeathByTree : tracks total death by trees - use goal to set up threshold
DeathByEdge : tracks total death by falling off edge of world - use goal to set up threshold
TimeInBase : tracks total time in base - use goal to set up threshold
TimeOutOfBase : tracks total time out of base - use goal to set up threshold
ArrowsShot : tracks total arrows shot - use goal to set up threshold
GoblinShamanKills : tracks total goblin shaman kills - use goal to set up threshold
DrakeKills : tracks total drake kills - use goal to set up threshold
WraithKills : tracks total wraith kills - use goal to set up threshold
ComfortPieces : tracks total known comfort pieces - goal irrelevant
GreydwarfShamanKills : tracks total greydwarf shaman kills - use goal to set up threshold
DvergerKills : tracks total dverger kills - use goal to set up threshold
DvergerFireKills : tracks total dverger fire mage kills - use goal to set up threshold
DvergerFrostKills : tracks total dverger frost mage kills - use goal to set up threshold
DvergerSupportKills : tracks total dverger support mage kills - use goal to set up threshold
TotalJumps : tracks total jumps - use goal to set up threshold
TotalCraftsOrUpgrades : tracks total crafts and upgrades of items - use goal to set up threshold
TotalBuilds : tracks total built pieces - use goal to set up threshold
EnemyHits : tracks total hits against creatures - use goal to set up threshold
PlayerKills : tracks total player kills - pvp - - use goal to set up threshold
HitsTaken : tracks total hits taken - use goal to set up threshold
ItemsPicked : tracks total items picked up - use goal to set up threshold
DistanceWalked : tracks total distance walked - use goal to set up threshold
DistanceInAir : tracks total air time - use goal to set up threshold
MineHits : tracks total pickaxe mine hits - use goal to set up threshold
CreatureTamed : tracks total successful tame - use goal to set up threshold
FoodEaten : tracks total food eaten - use goal to set up threshold
SkeletonSummoned : tracks total f riendly skeleton summoned - use goal to set up threshold
DeathByDrowning : tracks total death by drowning - use goal to set up threshold
DeathByBurning : tracks total death by drowning - use goal to set up threshold
DeathByFreezing : tracks total death by freezing - use goal to set up threshold
DeathByPoisoned : tracks total death by poisoned - use goal to set up threshold
DeathBySmoke : tracks total death by smoke - use goal to set up threshold
DeathByWater : tracks total death by water - use goal to set up threshold
DeathByCart : tracks total death by cart - use goal to set up threshold
DeathBySelf : tracks total suicides - use goal to set up threshold
DeathByStalagtite : tracks total death by stalagtite - use goal to set up threshold
BeesHarvested : tracks total bees harvested - use goal to set up threshold
SapHarvested : tracks total sap harvested - use goal to set up threshold
TrapsArmed : tracks total traps armed - use goal to set up threshold
StacksPlaced : tracks total stacks placed - use goal to set up threshold
BossKills : tracks total boss kills - use goal to set up threshold
CustomKills : tracks total custom defeat keys - set defeat key attribute with this type and use goal to setup threshold
GoalLore : tracks known lore against goal - use goal to set up threshold
```
## Resistance Modifier
This can be used to apply damage modifiers `on the player`,
It can be read as list if seperated by commas.
(ex: Fire = Weak, Frost = Resistant)
### Acceptable resistances:
```yml
Blunt
Slash
Pierce
Chop
Pickaxe
Physical : Pickaxe, Chop, Pierce, Slash, Blunt
Elemental : Fire, Frost, Lightning
Fire
Frost
Lightning
Poison
Spirit
```
### Acceptable modifier:
```yml
VeryWeak
Weak
Normal
Resistant
VeryResistant
```
## Activation animation
Only applies to active powers that use the 'F' key to engage forsaken power (aka guardian power)
Working animations: 
```yml
knife_stab0
bow_fire
knife_secondary
swing_axe0
axe_secondary
swing_pickaxe
swing_hoe
swing_hammer
unarmed_attack0
unarmed_kick
atgeir_attack0
atgeir_secondary
battleaxe_attack0
battleaxe_secondary
throw_bomb
dual_knives0
dual_knives_secondary
swing_longsword0
sword_secondary
mace_secondary
swing_sledge
spear_poke
spear_throw
staff_fireball0
staff_rapidfire
attack_abort
staff_shield
staff_summon
greatsword0
greatsword_secondary
eat
emote_drink
reload_crossbow_done
crossbow_fire
fishingrod_throw
Wave
Sit
Challenge
Cheer
NoNoNo
ThumbsUp
Point
BlowKiss
Bow
Cower
Cry
Despair
Flex
ComeHere
Headbang
Kneel
Laugh
Roar
Shrug
Dance
Count
```
## Extra
Please come find me on OdinPlus discord if you have any ideas on how to improve the system
Best, Rusty
