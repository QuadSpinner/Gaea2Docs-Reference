# Slope

The **Slope** node creates a selection mask based on the terrain’s slope angle, isolating areas within the specified slope range. Useful for masking steep cliffs, gentle hillsides, or controlling erosion and texturing.

## Properties

* **Range**\
  Sets the minimum and maximum slope angles to include. Only terrain within this range is selected in the mask.
* **Falloff**\
  Controls the soft transition at the range boundaries. Higher values create a smoother, more gradual blend from selected to unselected areas.
* **Type**\
  Defines the slope calculation method.
  * **Accurate**\
    Uses precise slope computation for more realistic, detail-preserving results.
  * **Normalized**\
    Produces a consistent, even distribution across the slope range, useful for stylized or uniform masks.
