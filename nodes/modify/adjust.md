# Adjust

The Adjust node is pretty much the same as the Modifier Stack, but in node form. It is often a process of trial and error where am adjustment node would need to be replaced with another. Sometimes the node would need to be chained with another.

This node makes that process easier by combining all the common adjustments inside a single node and allowing you to toggle them on and off. Additionally, it has its own [Modifier Stack](https://app.gitbook.com/s/-MRH8eXs83d5sUGKdsHp/getting-started/user-interface/property-editor/modifier-stack "mention") so you can apply further adjustments.



* **Multiply**  
  Multiplies the height of the terrain by the given range.
* **Shaper**  
  Negative values will bulk down the shape, while positive values will bulk up the shape.
* **Clamp**  
  Clamp allows you to control the height of the terrain.
* **Clip**  
  Clips values beyond the specifies range.
* **Drop**  
  Reduces the overall heights of the terrain until the terrain's lowest height is 0.
* **Autolevel**  
  Proportionately stretches the terrain so all values are equally spread between 0 and 1.
* **Equalize**  
  Equally distributes the heights/brightness across the entire range.
* **Strong**  
  Applies a logarithmic-like curve to emphasize the terrain or mask.
* **Invert**  
  Inverts/negates the entire terrain.
