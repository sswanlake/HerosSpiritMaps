# HerosSpiritMaps
Maps and Tilesets for the game Hero's Spirit - [Official Wiki](https://herosspirit.fandom.com/wiki/Hero%27s_Spirit_Wiki)

.tmx files in the Maps folder can be viewed and edited with [Tiled](https://thorbjorn.itch.io/tiled).  If you'd like to help fill in missing parts of the maps, please DM sswanlake from the Hero's Spirit discord server to request access, and adhere to the following mapping conventions:

+++++++++++++++++++++++++++

MAPPING CONVENTIONS:

Layers:
- Enemies
- NPCs + Signposts (+ save points + [?])
- Items + boulders
- Hide Group
  - Compass Floor
  - Hidden Items
  - Hidden Wall Paths
  - Water Paths
- Floor

+++++++++++++++++++++++++++

- The bottom right corner of the map's tileset is the map's background color
- the background color should go on the Floor layer in places where there's a hidden path, and underneath the [?] blocks, as well as any areas whose tiles cannot be verified (like along an uneven border)
- hidden paths (through walls) and water paths are indicated by the red overlay with diagonal (\) teal stripes and the white bubble-y tile respectively, these go on the corresponding layers
- warp points are indicated with the blue overlay with diagonal (/) violet stripes, these go on the hidden wall layer - if the warp is one way, the warp indicator only goes on the start point not the end point
- hidden triggers and points of interest are marked with the yellow overlay with yellow chevrons, these go on the hidden wall layer
- the [?] blocks go on the layer with the NPCs, signposts, and Save Points, with the item displayed placed on the Hidden layer over it
- Compass floor gets 75% opacity
