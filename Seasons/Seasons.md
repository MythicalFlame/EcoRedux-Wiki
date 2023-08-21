---
layout: page
title: Seasons
parent: Seasons
nav_order: 2
---

# Seasons

As part of the RealisticSeasons plugin, EcoRedux has seasons.\
Seasons have various effects on the world.

Seasons have custom colors for grass, water, sky, and leaves. To disable this, run `/toggleseasoncolors`

Seasons also have particles. To disable this, run `/toggleseasonparticles`

RealisticSeasons changes the biome in packets sent to players (visual only) for sub-seasons. This results in your actual biome being hidden from F3. To see your current biome, run `/currentbiome`

---

## List of Seasons
### Winter
- Visual effects (JAVA ONLY)
	- Leaves and grass are light grey
	- Water is dark blue
	- The sky is more white
- Extra spawning
	- Wolves
	- Foxes
	- Polar Bears
	- Snow Golems
- Crops cannot grow without a block above them
- There is a 33% chance every night that sparks will spawn in the sky
- Rain is replaced with snow
- Water freezes if exposed to the sky
- Nights are longer and days are shorter

### Spring
- Visual effects (JAVA ONLY)
	- Leaves in forests are pink
	- Water is light blue
	- The sky is light blue
- Extra spawning
	- Bees
	- Chickens
	- Cows
	- Pigs
	- Sheep
	- Rabbits
- Flowers spawn
- Ice and snow spawned in the Winter (NOT vanilla snow/ice) despawn
- Increased chance of rain/snow
- Firefly particles can spawn
- Nights and days have almost equal lengths

### Summer
- Visual effects (JAVA ONLY)
	- Leaves and grass are vibrant and green
	- Cold biomes have the grass color of plains
	- Water is light blue
	- The sky is light blue
- New spawning
	- Ocelots
	- Pandas
	- Parrots
- Spring flowers are removed
- Sweet berry bushes spawn
- Particles of leaves falling from trees can spawn
- Firefly particles can spawn
- Crops without a block above them grow 2x faster
- Rain and snow are rare
- There is a 0.5% chance every night that shooting stars will spawn in the sky
- Days are longer and nights are shorter

### Autumn
- Visual effects (JAVA ONLY)
	- Leaves are orange, blue, green, yellow, and brown
	- Grass is light brown
	- Water is brown
	- The sky is grey
- New spawning
	- Mooshrooms
	- Foxes
	- Frogs
	- Cave Spiders (at night)
	- Bats above ground (at night)
- Sweet berry bushes spawned in the Summer are removed
- Particles of leaves falling from trees can spawn
- Mushroom patches appear
- Mobs have a 15% chance to spawn with a pumpkin on their head
- Nights and days have almost equal lengths

---

### Subseasons
> Note: This feature is only relevant for Minecraft: Java Edition

> Note: This feature does not affect the Arctic/Antarctic, Sub-Arctic/Sub-Antarctic, and Equator climates.

Seasons do not change instantly. There is a feature called "sub-seasons" that gradually modifies season colors.

Start and End values in the table indicate the amount of progress through the current season.

| Phase | Start | End  | Biome Colors                 |
| ----- | ----- | ---- | ---------------------------- |
| 1     | 0%    | 9%   | 45% last season, 55% current |
| 2     | 9%    | 18%  | 25% last season, 75% current |
| 3     | 18%   | 84%  | 100% current season          |
| 4     | 84%   | 92%  | 25% last season, 75% current |
| 5     | 92%   | 100% | 45% last season, 55% current |