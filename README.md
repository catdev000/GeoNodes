# GeoNodes for Blender

## Height Map Visualization

Helps you visualize a height map 3-dimensional and colorize it. (Render Default: EEVEE) <br> <br>
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

## Planet Generator

When you want to create a planet similar to earth this geometry node group is for you. (Render Default: Cycles) <br> <br>
![Planet Generator Gif](images/Planet%20Generator.gif)  <br>
File to download: [Planet Generator Blender File](Geometry%20Nodes/Planet%20Generator.blend) <br>
Input Attributes:
|Input Name|Description|Type|
---|---|---|
Type|Choose which kind of planet you want to generate|Menu Selection
Generation Seed|Seed to get different kinds of earthlike planets|Value
Add Rotation|Should the planet/sun rotate?|Boolean
Rotation Speed|Speed the planet/sun shall rotate (when add rotate is checked)|Value
Land - Ocean(Earth)|Distrubution of land and ocean on your planet|Value
Clouds(Earth)|How cloudy your planet will be|Value
Add Atmosphere|Check if u want an atmosphere around ur planet|Boolean
Atmosphere Size|Controls the size of the atmosphere|Value
Holografic|Check if u want to have an holografic-like design|Boolean
Color(Sun)|Which color the sun shall have|Color
