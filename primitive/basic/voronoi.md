# Voronoi



Voronoi is a staple of procedural design. It creates sharp, geometric patterns. The version in Gaea, however, is a "geo-variant". We have modified the base Voronoi shape to fit the needs of terrain design from the beginning.

![](/images/ref/Voronoi/Voronoi.webp)



# Properties


| Property | Description| 
| -------- | -----------|
| **Noise** |  |
| Scale | The perceptual scale of the Voronoi shapes. Higher values create more shapes. |
| Jitter | Control the offset of the Voronoi points between symmetrical and chaotic. |
| Function |  |
| | **Euclidean**: Euclidean function. |
| | **Manhattan**: Manhattan function. |
| Form |  |
| | **C**: Voronoi cells with height decided by the cells themselves. |
| | **N**: Voronoi cells with height decided by the nearest neighbor. |
| | **R**: <desc> |
| | **P**: The default look for this geo-variant, suitable for creating mountains. |
| | **A**: A mix between P and M. |
| | **S**: Individual mountains with fully separated boundaries. |
| | **M**: Favors the strongest cell; good for creating a big mountain slope. |
| | **D**: Favors ridges over cell centers. |
| Gain |  |
| Clamp |  |
| Seed | The randomization pattern or seed for the node's process. |
| **Warp** |  |
| Type |  |
| | **None**: <desc> |
| | **Simple**: <desc> |
| | **Complex**: <desc> |
| Frequency |  |
| Amplitude |  |
| Octaves |  |
| **Transform** |  |
| Scale X | The non-uniform scale of the X axis. |
| Scale Y | The non-uniform scale of the Y axis. |
| X |  |
| Y |  |




# Examples
