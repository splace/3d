[![examples](block-tests.jpg)](../../advancedViewer.html?model=./2003/blocks/blocks-tests.wrl  "click to browse in 3d")

using [X_ITE](https://create3000.github.io/x_ite).
<!--
Block Prototype

Use this proto for building regular grid based things like buildings, arenas, rooms etc.

Overview

By taking advantage of the symmetries of a regular grid, and making sensible assumptions, objects can be built and incrementally refined, more quickly. Also, much less data is require to encode many common shapes. (this general idea is behind the built-in Extrusion node etc.) 
By using this prototype you work in a more 'solid' way, allowing a more three dimensional way of thinking.
This is actually all achieved directly in VRML script, with the  coordinates of the geometry and its texture, being dynamically generated, script simply produces more VRML. This generated VRML can be intercepted and used directly, (removing the need to include this prototype) and so avoiding any size overhead and script running delay, and so then becomes somewhat of an object development system.
	
Example: Textured room with windows

This room is actually 3 block proto shapes, one includes only the surfaces at the 'edge' of the grid, one the surfaces not at the 'edge' and the other the windows, this allows these different parts to have different  textures/materials.  (Note~: the tops of the walls have a different texture to the outside sides of the walls, but these belong to the same shape, this is the prototype automatically spliting a single texture file.)

The three objects reuse the same grid, so if the grid is modified, to say move a window, then all three objects change together to retain the solidity of the geometry.


-->
