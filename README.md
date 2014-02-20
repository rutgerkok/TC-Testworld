TC-Testworld
============

World used to test features of Terrain Control.

Included tests:

* VirtualBiomes (YellowWool biome)
* SurfaceAndGroundControl (YellowWool biome)
* Various BO3 spawn tests (YellowWool biome)
    * Yellow BO3s should only spawn on the yellow wool
    * Red BO3s should only spawn on the red wool, in high quantities
    * Orange BO3s should spawn on any type of wool
    * Gray wool should spawn on any solid block except yellow wool, even under terrain overhangs
* ReplacedBlocks with and without height limits (ReplacedBlocks biome)
* RiverWaterLevel should be ignored in ReplacedBlocks biome, as it has UseWorldWaterLevel: false
