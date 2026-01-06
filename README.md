# Configuración de mods
## Bosses of Mass Destruction
```
"lichConfig": {
	"experienceDrop": 5345,
	"health": 500.0,
	"missile": {
		"damage": 12.0
	},
},
"obsidilithConfig": {
	"health": 600.0,
	"attack": 20.0,
	"experienceDrop": 2045,
},
"gauntletConfig": {
	"health": 500.0,
	"attack": 20.0,
	"experienceDrop": 2045,
},
"voidBlossomConfig": {
	"health": 700.0,
	"armor": 6.0,
	"attack": 16.0,
	"experienceDrop": 2045
},
```
## FallingTree
```
"tools": {
    "damageMultiplicand": 1.05,
    "damageRounding": "ROUND_UP",
    "speedMultiplicand": 1.0,
    "forceToolUsage": true
},
```
## Illager Invasion
```
[invoker]
    participate_in_raids = true
```
## Marium's Soulslike Weaponry
```
"disable_gun_recipes": true,
"disable_recipe_comet_spear": true,
"disable_recipe_withered_wabbajack": true,
"disable_recipe_mjolnir": true,
"disable_recipe_draupnir_spear": true,
"disable_recipe_kraken_slayer_bow": true,
"disable_recipe_kraken_slayer_crossbow": true,
"disable_recipe_excalibur": true,
"withered_demon_spawnweight": 25.0,
```
## RightClickHarvest
```
requireHoe: true,
showServerWarning: false,
```
## Wraith Waystones
```
"worldgen": {
    "unbreakable_generated_waystones": true,
},
"teleportation_cost": {
    "cost_per_block_distance": 0.005,
    "cost_multiplier_between_dimensions": 3.0
},
"discover_with_item": "minecraft:ender_pearl",
"take_amount_from_discover_item": 1,
"permission_level_for_breaking_waystones": "OWNER",
"teleportation_cooldown": {
    "cooldown_ticks_when_hurt": 200,
    "cooldown_ticks_from_abyss_watcher": 144000,
    "cooldown_ticks_from_pocket_wormhole": 144000,
    "cooldown_ticks_from_local_void": 144000,
    "cooldown_ticks_from_void_totem": 200,
    "cooldown_ticks_from_waystone": 600
},
"disable_teleportation_from_dimensions": [
    "minecraft:the_end"
],
"disable_teleportation_to_dimensions": [
    "minecraft:the_end"
],
"ignore_dimension_blacklists_if_same_dimension": false,
```
## Xaero's World Map
```
cave_mode_allowed_dimensions = [minecraft:the_nether]
```
## You're In Grave Danger
```
"loseSoulboundLevelOnDeath": true,
"expConfig": {
    "dropBehaviour": "PERCENTAGE",
    "dropPercentage": 50,
    "keepPercentage": 0
},
"graveRobbing": {
    "enabled": false,
},
"graveTimeout": {
    "enabled": true,
    "afterTime": 30,
    "timeUnit": "MINUTES",
},
"treatBindingCurse": false,
"randomSpawn": {
	"percentSpawnChance": 25,
},
```

# Código de mods
## Better Nether
  - Ítems eliminados de loot tables: Bloque de netherita, Mejora de netherita, Pico de netherita.
## Deeper and Darker
  - Cambiado el crafteo de Warden Upgrade Smithing Template, Reinforced Echo Shard
  - Eliminado el drop de Warden Carapace en vasijas antiguas
