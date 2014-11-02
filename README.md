TC-Testworld
============

World used to test features of Terrain Control.

Included tests:

* Virtual biomes using ReplaceToBiomeName (YellowWool biome)
* SurfaceAndGroundControl (YellowWool biome)
* Biome inheritance (YellowWoolIsle biome)
* Isle biome (YellowWoolIsle biome)
* Various BO3 spawn tests (YellowWool biome)
    * Yellow BO3s should only spawn on the yellow wool
    * Red BO3s should only spawn on the red wool, in high quantities
    * Orange BO3s should spawn on any type of wool
    * Gray wool should spawn on any solid block except yellow wool, even under terrain overhangs
* ReplacedBlocks with and without height limits (ReplacedBlocks biome)
* RiverWaterLevel should be ignored in ReplacedBlocks biome, as it has UseWorldWaterLevel: false
* 1x1 and 2x2 trees growing from saplings (Redwood and DarkOak, YellowWool(Isle) biome)
* CustomHeightControl that causes giant cave around y = 10 (ReplacedBlocks biome)
* Small cobblestone BO3 structure of two pieces spawns (ReplacedBlocks biome)
