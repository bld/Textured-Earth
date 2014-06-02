Textured Earth
==============

This is a model of Earth made of a sphere with two displacement
maps. A specular map displaces the land & ice masses above the
oceans. A topography map adds texture to the land. This exaggerates
the texture more than a topography map alone. It was inspired by the
models [Earth Shot](thingiverse.com/thing:14070) and [Two Color
World](http://www.thingiverse.com/thing:11660).

The license is [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/).

Instructions
------------

The Blender file contains the 1K specular and bump maps from:
planetpixelemporium.com/earth.html

* Go to the Modifier stack of the icosphere.
* Adjust the subdivisions of the 1st modifier to change the resolution.
* Adjust the strength of the 2nd modifier (negative) to change the land & ice displacement above the oceans.
* Adjust the strength of the 3rd modifier to change the topographic displacement on land.
* Export the model as an STL. Enable the "Import-Export: STL format" addon in the user preferences if STL doesn't show up in the "Export" menu.

To wrap your own displacement map on a sphere, it needs a UV
map. Select the sphere. Go to mesh edit mode (Tab). Change the view to
"Front" (numpad 1). Select Mesh -> UV Unwrap -> Sphere Projection. In
the displacement modifier, set the "Texture Coordinate" to "UV".

Print with support material. I originally use it as a part in another
project.
