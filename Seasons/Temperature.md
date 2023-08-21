---
layout: page
title: Temperature
parent: Seasons
nav_order: 1
---

# Temperature
EcoRedux has a temperature system.
Your temperature is affected by a few modifiers. Having a temperature too low or too high will have bad effects.

The temperature is shown in a display bar above your hotbar. By default, it shows celsius (&deg;C). You can toggle fahrenheit mode with `/togglefahrenheit`.

---

## Modifiers
### Climate
The climate of your region is one of the most important modifiers of your temperature. 

If you are in the climates Arctic/Antarctic, Sub-Arctic/Sub-Antarctic, or Equator, your temperature is constant and is not affected by the below modifiers.\
If you are in any other climate, you instead get a climate temperature modifier that can stack with the below modifiers.

Please see [here](Climate.html) for more information.

### Seasons
The world has a randomly generated base temperature (changed each day) based on the season.
All modifiers are applied onto this base temperature.

| Season | Minimum Base Temperature | Maximum Base Temperature |
| ------ | ------------------------ | ------------------------ |
| Winter | -10&deg;C / -14&deg;F    | 10&deg;C / 50&deg;F      |
| Spring | 10&deg;C  / 50&deg;F     | 25&deg;C / 77&deg;F      |
| Summer | 30&deg;C  / 86&deg;F     | 47&deg;C / 116.6&deg;F   |
| Autumn | 5&deg;C   / 41&deg;F     | 20&deg;C / 68&deg;F      |

### Weather
Weather can also impact the current temperature.

| Weather      | Modifier              |
| ------------ | --------------------- |
| Rain/Snow    | -10&deg;C / -18&deg;F |
| Thunderstorm | -15&deg;C / -27&deg;F |

### Time
The time of day changes your temperature. During the day(ticks 6000-12000), the modifier will be\
+3&deg;C / +5.4&deg;F. During the night, the modifier will be -5&deg;C / -9&deg;F. In between those times, the modifier will gradually change.

### Biomes
The biome you are in may affect your temperature.

| Biome                                                     | Modifier                |
| --------------------------------------------------------- | ----------------------- |
| Badlands/Desert                                           | +15&deg;C / +27&deg;F   |
| Jungle                                                    | +12&deg;C / +21.6&deg;F |
| Savanna, Hot Shrubland                                    | +10&deg;C / +18&deg;F   |
| Amethyst Rainforest                                       | +8&deg;C  / +14.4&deg;F |
| Terralith Caves                                           | +7&deg;C  / +12.6&deg;F |
| Ashen Savanna                                             | +6&deg;C  / +10.8&deg;F |
| Dripstone/Lush Caves, Warm River                          | +5&deg;C  / +9&deg;F    |
| Basalt Cliffs, Cloud Forest                               | -2&deg;C  / -3.6&deg;F  |
| Mountains, Windswept Forest/Hills, Blooming Valley, Taiga | -4&deg;C  / -7.2&deg;F  |
| Frozen/Snowy Biomes                                       | -12&deg;C / -21.6&deg;F |

### Height
If the current season is not Winter, temperature will decrease by 0.08&deg;C / 0.144&deg;F for every block of height above y=64.
If the current season is Winter, temperature will increase by 0.2&deg;C / 0.36&deg;F for every block of height below y=64.

### Water/Powdered Snow
Being in water/powdered snow will affect your temperature. When you get out of the water/powdered snow, the temperature modifier will decrease by 1&deg;C / 1.8&deg;F every 2 seconds until it gets back to zero.

| Season | Modifier              |
| ------ | --------------------- |
| Winter | -20&deg;C / -36&deg;F |
| Other  | -10&deg;C / -18&deg;F |

### Sprinting
If you are cold, sprinting is a quick way to increase your temperature. Sprinting can increase your temperature by up to 4&deg;C / 7.2&deg;F.

### Armor
Wearing armor increases your temperature.

The leather armor temperature bonus will not apply if your temperature exceeds 25&deg;C / 77&deg;F.

| Material          | One Armor Piece           | Full Set               |
| ----------------- | ------------------------- | ---------------------- |
| Leather           | +5&deg;C    / +9&deg;F    | +20&deg;C / +36&deg;F  |
| Iron/Gold/Diamond | +1.25&deg;C / +2.25&deg;F | +5&deg;C  / +9&deg;F   |
| Netherite         | +0.75&deg;C / +1.35&deg;F | +3&deg;C  / +5.4&deg;F |

### Food
If your temperature is under 25&deg;C / 77&deg;F and you have a full hunger bar, you will gain a 15&deg;C / 27&deg;F temperature bonus.
If your temperature is under 25&deg;C / 77&deg;F and you drink a water bottle, your temperature will be decreased by 15&deg;C / 27&deg;F for 5 minutes (effect is not stackable by drinking multiple bottles of water at once).

### Block Effects
Standing near certain blocks can affect your temperature. The block must be accessible (not hidden behind other blocks) for the effect to apply. The closer you stand to the block, the larger the effect will be.

Additionally, if you are inside the lava block itself, your temperature will increase by 1500&deg;C / 2700&deg;F.

| Block              | Range | Full Modifier           |
| ------------------ | ----- | ----------------------- |
| Campfire           | 9     | +15&deg;C / +27&deg;F   |
| Lava               | 7     | +22&deg;C / +39.6&deg;F |
| Fire               | 7     | +16&deg;C / +28.8&deg;F |
| Lantern            | 7     | +7&deg;C  / +12.6&deg;F |
| Torch              | 7     | +5&deg;C  / +9&deg;F    |
| Soul Torch/Lantern | 7     | -7&deg;C  / -12.6&deg;F |
| Soul Campfire      | 7     | -10&deg;C / -18&deg;F   |
| Blue Ice           | 7     | -15&deg;C / -27&deg;F   |
| Soul Fire          | 7     | -16&deg;C / -28.8&deg;F |
| Ice/Packed Ice     | 3     | -6&deg;C  / -10.8&deg;F |

---

## Consequences
To encourage players to keep their temperature in mind while playing, you will get undesirable effects when your temperature is too high or too low

| Temperature                    | Effects                                                                                  |
| ------------------------------ | ---------------------------------------------------------------------------------------- |
| -15&deg;C / 5&deg;F or lower   | Hunger effect, slowness effect, freezing effect (half a heart of damage every 2 seconds) |
| 0&deg;C / 32&deg;F or lower    | Cold breath particle effect                                                              |
| 40&deg;C / 104&deg;F or higher | Sweat particle effect                                                                    |
| 50&deg;C / 122&deg;F or higher | Healing is disabled                                                                      |
| 60&deg;C / 140&deg;F or higher | Slowness effect                                                                          |
| 65&deg;C / 149&deg;F or higher | Player is set on fire                                                                    |