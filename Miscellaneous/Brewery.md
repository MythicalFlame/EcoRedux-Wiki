---
layout: page
title: Brewery
parent: Miscellaneous
nav_order: 1
---

# Brewery
[Brewery](https://github.com/DieReicheErethons/Brewery) is a plugin that lets you create new potions through the cauldron brewing system.

---

## Drunkeness
Some brews have alcohol in them (and some decrease your alcohol level). Alcohol has various effects than can include:
- Stumbling
- Chat being jumbled
- Vomiting
- Hangovers
- Fainting (disconnecting)

---

## Creating Potions
### Brewing
First, place a cauldron filled with water that has a heat source under it (fire, lava, campfire, etc.)\
Next, right click (tap on mobile) the cauldron with your brewing ingredients.\
Finally, wait for your brew to finish and then collect it with a bottle.\

You can click the cauldron with a clock to see the amount of time that has passed since brewing started.

### Distillation
> Note: Not every brew needs a distillation. In addition, some brews require multiple distillations.

To distill a brew, put it in a brewing stand with glowstone as the ingredient. You do not need blaze powder fuel for this.

### Aging
> Note: Not every brew needs to be aged.

Some brews require aging in a barrel. The aging time is based on minecraft days. Not fully aging a drink can result in lower quality.

Some brews also require aging in a barrel made of a specific type of wood.

The available aging structures are as follows:

1. Minecraft Barrel (Uses wood type "oak")\
- Has 6 potion slots\
![](https://camo.githubusercontent.com/f6692fb86fdcb4c47faae315e2cc1dd129365222db5c81fc470752e5379d330d/68747470733a2f2f67616d6570656469612e637572736563646e2e636f6d2f6d696e6563726166745f64655f67616d6570656469612f7468756d622f332f33332f466173732e706e672f31353070782d466173732e706e673f76657273696f6e3d6564386263393832323739353330656134366461633762393332656331623836)

2. Small Barrel\
- Has 9 potion slots\
![](https://camo.githubusercontent.com/72b19a687db21cb6c33274de328f87e4ad12b513e856cb67c7b541d3c9d41e4c/68747470733a2f2f696d6775722e636f6d2f426b4e736935342e706e67)

3. Big Barrel\
- Has 27 potion slots\
![](https://camo.githubusercontent.com/86be3e4a6ab7d08c34138491178c3aa837dcfaf11fe42ceb8b0bc5c4cc3794b4/68747470733a2f2f696d6775722e636f6d2f6b336834716a302e706e67)

### Recipes
> Deprecation Notice: Below recipes are planning on being replaced

Below is the table that contains the list of recipes on EcoRedux.
The alcohol percentage is the percentage at maximum quality.
The special effects are a range. On the left side of the range, you can see the minimum quality effects, and on the right side of the range, you can see maximum quality effects.

| Brew           | Ingredients                                    | Wood Type | Brew Time  | Distill Runs | Days to Age | Alcohol | Special Effects                                                                                    |
| -------------- | ---------------------------------------------- | --------- | ---------- | ------------ | ----------- | ------- | -------------------------------------------------------------------------------------------------- |
| Wheatbeer      | Wheat x3                                       | Birch     | 8 Minutes  | 0            | 2           | 5%      |                                                                                                    |
| Beer           | Wheat x6                                       | Any       | 8 Minutes  | 0            | 3           | 6%      |                                                                                                    |
| Dark Beer      | Wheat x6                                       | Dark Oak  | 8 Minutes  | 0            | 8           | 7%      |                                                                                                    |
| Wine           | Sweet Berries x5                               | Any       | 5 Minutes  | 0            | 20          | 8%      |                                                                                                    |
| Mead           | Sugar Cane x6                                  | Oak       | 3 Minutes  | 0            | 4           | 9%      |                                                                                                    |
| Apple Mead     | Sugar Cane x6, Apple x2                        | Oak       | 4 Minutes  | 0            | 4           | 11%     | Water Breathing I-II (150s)                                                                        |
| Cidre          | Apple x14                                      | Any       | 7 Minutes  | 0            | 3           | 7%      |                                                                                                    |
| Apple Liquor   | Apple x12                                      | Acacia    | 16 Minutes | 3            | 6           | 14%     |                                                                                                    |
| Whiskey        | Wheat x10                                      | Spruce    | 10 Minutes | 2            | 18          | 26%     |                                                                                                    |
| Rum            | Sugar Cane x18                                 | Oak       | 6 Minutes  | 2            | 14          | 30%     | Fire Resistance I (20s-100s), Poison I-0 (30s-0s)                                                  |
| Vodka          | Potato x10                                     | N/A       | 15 Minutes | 3            | 0           | 20%     | Weakness I (15s), Poison I (10s)                                                                   |
| Mushroom Vodka | Potato x10, Red Mushroom x3, Brown Mushroom x3 | N/A       | 18 Minutes | 5            | 0           | 18%     | Weakness I (80s), Confusion (27s), Night Vision (50s-80s), Blindness (12s-2s), Slowness I (10s-3s) |
| Gin            | Wheat x9, Blue Flower x6, Apple x1             | N/A       | 6 Minutes  | 2            | 0           | 20%     |                                                                                                    |
| Tequila        | Cactus x8                                      | Birch     | 15 Minutes | 2            | 12          | 20%     |                                                                                                    |
| Absinthe       | Grass x15                                      | N/A       | 3 Minutes  | 6            | 0           | 42%     | Poison I (15s-25s)                                                                                 |
| Green Absinthe | Grass x17, Poisonous Potato x2                 | N/A       | 5 Minutes  | 6            | 0           | 46%     | Poison I (25s-40s), Harming II, Night Vision (40s-60s)                                             |
| Potato Soup    | Potato x5, Grass x3                            | N/A       | 3 Minutes  | 0            | 0           | 0%      | Regeneration I (0s-1s)                                                                             |
| Coffee         | Cocoa Beans x12, Milk x2                       | N/A       | 2 Minutes  | 0            | 0           | -6%     | Regeneration I (2s-5s), Speed I (30s-140s)                                                         |
| Eggnog         | Egg x5, Sugar x2, Milk x1                      | Any       | 2 Minutes  | 0            | 3           | 10%     |                                                                                                    |

### Sealing
> Note: This section is only relevant for shopkeepers.

If you want to sell your brews in a chestshop, you need to follow some steps.

First of all, craft a sealing table.\
![](https://camo.githubusercontent.com/c7e5aa89fe4acfef69a62b7e10f95622b99ab7ba5f9e4906dcf766309993d564/68747470733a2f2f7a6562726164726976652e64652f696e6465782e7068702f732f614a587057506a5a41576e417656452f646f776e6c6f6164)\
Next, enter your brews into the sealing table.\
You're done! Your brew cannot be sold. Keep in mind that brews that are sealed cannot be modified any further.