Note this files contain an almost ready Trainworks formatted JSON files for animated card art.

All that is missing is references to sprites.

If you copy any portion of the layering information the associated texture must be ripped from the base game and included in the sprites section.

For speed/performance I'd highly recommend downsizing any background textures (as referenced in base_layer) down to about 210x210 as well as any other images. Image loading in Trainworks is a bottleneck if you feed it several 1000x720+ sized images.