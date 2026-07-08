# Custom modlet — summary of effects

Human-readable summary of what `Mods/Custom` changes versus vanilla. Each `Config/*.xml` file below patches the vanilla file of the same name in `Data/Config/`.

## Loot (`loot.xml`)

- Most containers no longer disappear after being looted (`destroy_on_close` off globally); a specific set — backpack, junk, bird nests, shoes, single books, skill-magazine quest rewards, trash/ammo/pile/clothes containers — instead stay as empty husks rather than vanishing or staying full.
- Junk piles and dumpsters no longer drop seeds or stray feathers.
- Bird nests: fewer feathers per nest; egg odds stay at vanilla rates, but there's now a chance of a bonus second egg, and nest variant 01 can now also drop an egg (at the same vanilla-level odds).
- Grills: no longer drop cooked/charred/rotten meat or a hunting knife; the cooking grill tool itself is more common.
- Ovens: no longer drop food or coal; cooking pot and grill tools are more common.
- Dishwashers: no longer drop rotten flesh, animal fat, bone, or a grill; cooking pot is rarer, but now also drops empty jars, beakers, metal pipe, mechanical/electrical parts, and springs.
- Cupboards (cooking tools loot): now also drop empty jars and beakers.
- Water coolers: no longer drop scrap polymers or boiled water; pure mineral water is now medium-low rarity.
- Coffee makers: no longer drop river water or boiled water; a jar of coffee is somewhat more common than vanilla.
- Soda fountains: no longer drop river water, boiled water, or paper; Mega Crush soda is more common and can drop in small stacks, and pure mineral water can now drop too.
- Laundry: no longer drops the basic clothing group; premium clothing is more common, and armor parts can now drop.
- The first "buried supplies" quest reward is guaranteed to include a head lamp (helmet light mod).
- Broken soda/snack vending machines are now openable loot containers instead of dumping their loot on destruction.

## Items (`items.xml`)

- Bone knife and hunting knife gain the `longShaft` tag (compatible with the flaming-weapon mod attachment).
- Zombie and zombie-cop melee attack range slightly reduced.
- All axes (and the starting stone axe) deal Slashing damage instead of their default type.
- Stun baton: once the Intellect Mastery perk reaches level 5, equipping/hitting with the baton charges it further and adds a spark particle effect.
- Ranged/thrown archery damage significantly increased across the board: stone/iron/steel-AP arrows and crossbow bolts, flaming and exploding variants, and the wooden/compound bow & compound crossbow base damage.

## Recipes (`recipes.xml`)

- Vehicle wheel crafting reworked to consume a matching scrap tire/wheel item (4 variants) plus forged iron and scrap polymers, instead of oil.
- Charred meat now requires much less raw meat to craft.

## Blocks (`blocks.xml`)

- Flat tire and wheel decorative blocks can be picked up.
- Broken soda/snack vending machine blocks are converted to lootable containers (paired with the `loot.xml` changes above) instead of dropping loot on destruction.

## Entities (`entityclasses.xml`)

- Zombies can no longer climb ladders, are worse swimmers, and their corpses persist for 10 minutes instead of despawning quickly.
- Timid animals and stags also get the 10-minute corpse persistence.
- No XP is gained from selling items to traders.

## Entity spawn groups (`entitygroups.xml`)

- Desert biome: zombie vultures spawn much rarer than vanilla; rancher zombies (day and night) are rarer.
- Snow biome: chuck zombies (day and night) are rarer.

## Item modifiers (`item_modifiers.xml`)

- Night vision goggles fade the screen effect in/out over 1.2 seconds instead of snapping instantly, on activate, deactivate, and unequip.
- An additional subtle screen-brightening effect plays alongside night vision for better visibility.

## World globals (`worldglobal.xml`)

- Nights are substantially darker — all nighttime ambient light scales (equator, ground, sky, desaturation, moonlight, and their indoor equivalents) are cut significantly from default.

## Spawning (`spawning.xml`)

- Currently empty — reserved for future custom spawn rules.

---
*Generated from the modlet's XML patches; see the `Config/*.xml` files for the exact xpath-level changes.*
