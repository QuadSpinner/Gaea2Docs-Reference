
The **DirectionalWarp** node deforms the terrain using a guide input to control the displacement. This allows for controlled warping effects such as wind-swept erosion, river carving, and other directional deformations.

### **Inputs**

* **Primary Input:** The terrain to be warped.
* **Guide Input:** The directional guide that influences the warping effect. This can be any terrain or pattern used to determine the displacement direction.

## Properties

* **Strength**  
  Controls the intensity of the warping effect. Higher values create more pronounced distortions.
* **Direction**  
  Sets the primary direction of the warp effect.
* **Edge Behaviour:** Defines how the warp effect interacts with terrain edges.
  * **Edge**  
  Determines whether the effect is clipped or extended beyond the bounds of the terrain.
  * **Mirror**  
  Mirrors the warping effect along edges to maintain symmetry. Useful for tiling terrains without visible seams.
