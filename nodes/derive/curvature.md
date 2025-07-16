# Curvature

The **Curvature** node creates a mask where convex areas (such as sharp edges, ridges, protrusions) are selected. It’s a very useful layer in texture creation, often for adding highlights or edge wear on top of an existing texture map.

## Properties

* **Range**\
  Controls the detection sensitivity. Higher values include broader features; lower values focus on sharper, finer details.
* **Type**\
  Defines the direction or method of curvature detection.
  * **Horizontal**\
    Emphasizes curvature in the horizontal direction, isolating horizontal edges.
  * **Vertical**\
    Emphasizes curvature in the vertical direction, isolating vertical edges.
  * **Average**\
    Blends horizontal and vertical detection for uniform, all-direction edge highlights.
* **Falloff**\
  Sets the soft falloff at the maximum edge, controlling how gradually the mask fades from bright edges into flat areas.
