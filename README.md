# GeoNodes for Blender

## Balloon Generator

Inflate and pop a balloon in your animation(Render Default: Cycles) <br> <br>
<img src="images/balloon%20inflation%20and%20pop.gif" width="200" alt="Balloon Gif"> <br>
File to download: [Balloon Generator Blender File](Geometry%20Nodes/Balloon%20Maker.blend) <br>
Input Attributes:
|Input Name|Description|Type|
---|---|---|
Color|The color of the balloon|Color
Burst Point|The Point in your animation where the balloon pops|Boolean
Inflation Starting|Point in your animation where the balloon starts inflating|Boolean
Inflation Speed|How fast the balloon inflates when Inflation Starting is triggered|Value

## Cube with Face Expressions

A Shader (not a geometry node) to have a cube with different colors and facial expressions (Render Default: Cycles) <br>
Color and facial expressions are controlled by custom properties. (under object the last tab)
<br> <br>
![Cube with facial expressions](images/cube%20with%20expressions.gif) <br>
File to download: [Cube with Expressions Blender File](Shader%20Nodes/Cube%20with%20Face%20Expressions.blend) <br>
Input Attributes:
|Input Name|Description|Type|
---|---|---|
Color|The color of the Cube|Value
Color Brightness|The Brightness of the color of the cube|Value
Face Expression|The current face expression as number|Integer


## Height Map Visualization

Helps you visualize a height map 3-dimensional and colorize it. (Render Default: Cycles) <br> <br>
![Height Map Image](images/Height%20Map%20Visualization.png) <br>
File to download: [Height Map Blender File](Geometry%20Nodes/Height%20Map%20Visualization.blend) <br>
Input Attributes:
|Input Name|Description|Type|
---|---|---|
Geometry|The Grid you need to visualize the map|Grid
Height Map Image|The image of a height map|Image
Color High Zone|Color of the 'high' zone (top of mountains)|Color
Color Ground Zone|Color of the 'ground' zone (bottom of the mountains)|Color
Color Ground-High Transition|Color of the zone between ground and high zone|Color
Height Difference|The higher the value, the higher the mountains|Value
Add Fog| Adds Fog to your height map|Boolean
Fog Size|Sets the size of the fog bubble|Value

## Planet Generator

When you want to create different planets and suns this geometry node group is for you. (Render Default: Cycles) <br> <br>
![Planet Generator Gif](images/Planet%20Generator.gif)  <br>
File to download: [Planet Generator Blender File](Geometry%20Nodes/Planet%20Generator.blend) <br>
Input Attributes:
|Input Name|Description|Type|
---|---|---|
Type|Choose which kind of solar object you want to generate|Menu Selection
Generation Seed|Seed to get different kinds of planets/suns|Value
Resolution|Resolution of the planet/sun|Integer
Add Rotation|Should the planet/sun rotate?|Boolean
Rotation Speed|Speed the planet/sun shall rotate (when add rotate is checked)|Value
Land - Ocean(Earth)|Distrubution of land and ocean on your planet|Value
Clouds(Earth)|How cloudy your planet will be|Value
Add Atmosphere|Check if u want an atmosphere around ur planet|Boolean
Atmosphere Size|Controls the size of the atmosphere|Value
Holografic|Check if u want to have an holografic-like design|Boolean
Color(Sun)|Which color the sun shall have|Color
