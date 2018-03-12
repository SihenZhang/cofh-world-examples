# [CoFH World 经典实用案例——内含大量实例、截图及纠结于世界生成时所注意的内容](https://www.reddit.com/r/feedthebeast/comments/818y32/the_cofh_word_cookbook_a_huge_list_of_examples/)

**作者：*Fivefingeredfluke***

**翻译：*SihenZhang***

---

CoFH World 是一个非常强大的工具，它可以轻松地将矿石、装饰物、树木或尖刺添加到世界生成当中。虽然每个生成选项的特定设置都可以在 [CoFH 的网站](https://teamcofh.com/docs/world-generator-configuration/) 上找到，但我一直希望能够有更为完整的实例来说明如何使用这些设置。所以我以截图等方式向你展示了大量的 CoFH World 的设置实例。（这些实例都是只由原版和 Thermal Mods 生成的。大多数实例的“频率”都被调的很高，所以在测试过程中很容易被发现。）

## 巨石型生成——雪球
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/snow_balls.json)
- ![Screenshot](https://i.imgur.com/bK6rnCv.png)
- 注意：仅在被归类为 “snowy” 或 “frozen” 的生物群系中生成雪球装饰物。
## 巨石型生成——深层矿物
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/deep_boulder.json)
- ![Screenshot](https://i.imgur.com/xWRvRjd.png)
- 注意：在基岩附近生成由 80% 地狱岩和 20% 下界石英构成的巨石。这是一个如何在生成中使用方块权重的好例子。
## 湖泊型生成——下界烈焰之炽焱湖

- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/nether_lake.json)
- ![Screenshot](https://i.imgur.com/DALkQQp.png)
- 注意：由炽热的烈焰之炽焱构成的湖泊只会在下界生成，并且会有着混有岩浆块和地狱疣块的边缘。这也是一个限制维度的例子。
## 湖泊型生成——隐藏的谐振熔融末影珍珠湖
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/end_lake.json)
- ![Screenshot](https://i.imgur.com/v11DYLK.png)
- 注意：从结果上来说，很难通过截图表现湖泊被隐藏的特点。这个例子将湖泊的 “gap-block” 设置为末地石来达到隐藏真实湖泊的效果。截图中的玻璃应为末地石，请小心挖掘。
## 晶球型生成——浮空熔岩球
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/lava_geode.json)
- ![Screenshot](https://i.imgur.com/Ipzmgiq.png)
- 注意：晶球型生成可以以一种外部的方块来包围另一种内部的方块（在整合包里你可以巧妙地将一些稀有的矿物生成在黑曜石外壳之中）。这个例子中的外部是玻璃，内部是熔岩。如果你不介意漂浮在空中的东西，那么这是一个很好的以“空气”作为材料特征并生成在空中的例子。
## 石笋型生成——沙锥
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/sand_spikes.json)
- ![Screenshot](https://i.imgur.com/xvHi4H5.png)
- 注意：这个例子其实教会了我一些东西。就像你可以对要生成的方块列出一个权重列表，你也可以为你所选的生成器类型列出一个权重列表。在这张截图中你可以看到红砂岩与岩浆块形成的锥刺相对更少一些，大约是砂岩锥刺生成倍率的 60% 。这种加权生成可以被用来做一些东西，诸如 10 个铁矿石矿脉中有 1 个矿脉是由密集铁矿石构成。
## Stalagmite Generation - Oil Wells
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/oil_well.json)
- ![Screenshot](https://i.imgur.com/YsGcehi.png)
- Notes: Although I couldn't quite get the deep oil reservoirs to generated, these oil stalagmites make a pretty good recreation of the old buildcraft oil wells.
## Tree Generation - Solid Gold Trees
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/gold_trees.json)
- ![Screenshot](https://i.imgur.com/M9aRzQ0.png)
- Notes: Couldn't really come up with something creative to do with tree generation, so here's an example of trees made with gold blocks for leaves.
## Spike Generation - End Spikes
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/end_spikes.json)
- ![Screenshot](https://i.imgur.com/cXl2erv.png)
- Notes: Using the shape of ice spikes in vanilla, this creates spikes of obsidian in the end. I didn't intend for the spikes to generate down in the void, but it creates an interesting feature for players without flight to try and throw enderpearls at.
## Fractal Large Vein Generation - Fake End Caves
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/fake_cave.json)
- ![Screenshot](https://i.imgur.com/BIucaI2.png)
- Notes: WARNING: This will cause horrible cascading world gen and would have to be pregened to be usable. The screen shot is from spectator mode while in the end island, so what you see are the pockets of air or fake caves carved out by this generation. Just an interesting idea.
## Plate Generation - Perfect Ore Layers
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/world_layers.json)
- ![Screenshot 1](https://i.imgur.com/B1Femns.png)![Screenshot 2](https://i.imgur.com/22AmEok.png)
- Notes: A bit longer of a json than some of the other examples. This defines a very specific layer for each ore with andesite/granite buffer layers between the ores.
## Cave Distribution - No Strip Mining
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/cave_world.json)
- ![Screenshot 1](https://i.imgur.com/LOnlY63.png)![Screenshot 2](https://i.imgur.com/rUL4YWA.png)
- Notes: Someone in discord brought up the idea of a world where ores only generate in caves to discourage players from doing boring strip mines. The first screen shot shows the world in spectator mode, so you can see where the caves exist. The second screen shot shows a stripped version of the same cave, showing how the ores only stick to where caves generate.
## Stalactite Generation - Spooky Trees
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/spider_trees.json)
- ![Screenshot](https://i.imgur.com/5tXIR2s.png)
- Notes: Using really tiny stalactites, you can add small cobwebs to the underside of some trees. An example of restriction by biome name, these only generate in roofed forests.
## Vein Generation - Weird Petrotheum Lake
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/petro_vein.json)
- ![Screenshot 1](https://i.imgur.com/qRDd9NJ.png)![Screenshot 2](https://i.imgur.com/PrPea7G.png)
- Notes: Using the a vein generation setting with distribution only on the surface, you can make lakes that look a little less normal. These petrotheum lakes often only have small spots sticking above the surface with the body of the fluid below. Only generates in the desert. First screen shot shows how they normally appear, the second screen shot is the same generation method using melon blocks so you can see how much of the fluid generates just below the surface.
## Underfluid Distribution - Cryotheum Ores
- [JSON link 1](https://github.com/superfluke/cofh-world-examples/blob/master/world/00_cryo_lake.json) & [JSON link 2](https://github.com/superfluke/cofh-world-examples/blob/master/world/frosty_ores.json)
- ![Screenshot](https://i.imgur.com/UHqJxRX.png)
- Notes: This one took quite a few tests to get rights and I quite like the end result. Unlike the other examples, this one takes 2 separate jsons. The first creates cryo lakes in snowy/frozen biomes, then the second generates very small clusters of either diamond or lapis under fluid cryotheum. An interesting example of how one generation (the ores) can depend upon the generation of another feature (the cryo lakes).
These last few are the least exciting examples, but are included for completeness.
## Uniform vs. Gaussian Distribution
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/uniform_gaussian.json)
- ![Screenshot](https://imgur.com/sOJxdRf.png)![Ore Distribution Graph](https://i.imgur.com/67Nc4j6.png)
- Notes: While the overall cluster shape is the same, you can see in the distribution graph that uniform has a more even distribution (shockingly) while gaussian is very high at a specific y-level and slowly decrease over a distance. Copper has the normal distribution, while tin is the gaussian distribution
## Cluster vs. Sparse Cluster Distribution
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/sparse_cluster.json)
- ![Screenshot](https://i.imgur.com/mrv9Iex.png)
- Notes: With the same cluster size and cluster count settings, the cluster generation seems to produce more overall with clusters between 1-4 ores large. Sparse Cluster generation produce a lot fewer over all clusters, with most being only 1 ore large. Copper is the normal cluster, while tin is the sparse cluster.
## Large Veins vs. Sparse Large Veins
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/large_vein_test.json)
- ![Screenshot](https://i.imgur.com/oPp2kw3.png)
- Notes: To be honest, I can't really see a difference with the large vein sparse setting turned on. But here's the screenshot anyway so you all can be the judge, copper is the large-veins normal while tin is the large-veins sparse

---

If you made it this far, thanks for checking out this excessively long post :D I hope I inspired some modpack makers to add some cool things to their world or just gave others a working example for messing with world gen. Feel free to steal, remix, or add onto any of these examples. If you'd like to check out my pack which has peat lined lakes and underground boulders made of skystone and custom osmatic steel ore, here's a link to [Undiscovered](https://minecraft.curseforge.com/projects/undiscovered).
