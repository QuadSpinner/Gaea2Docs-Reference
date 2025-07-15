
## Warp

Warp can take the terrain and "warp" the shape creating more organic shapes. In terrains it can help create more believable shapes or alter simple shapes into a more complex formation. In masks, it can help create breakups that can make a linear mask more random and chaotic without losing its general shape.

By using vector fields, the warping created by this node result in more comprehensive shapes without creating directional tearing or over-stretching the original shape.

**Warp as a Post Process**

Warp is also built into the Modifier Stack for easy access.

## Properties

### Warp

* **Size**  
  The size of the warp noise.
* **Strength**  
  The strength of the warp noise.
* **Z Scale**  
  Vertical axis scale for the noise.
* **Warp Source:** Choose from various built-in noises as the Warp Source, or provide a custom source.
  * **PerlinFBM / VoronoiR / VoronoiP / VoronoiA / VoronoiS / VoronoiM/ VoronoiD.**
* **Perturbation**:
* **Complexity**  
  The complexity of the warp noise source.
* **Roughness**  
  The roughness of the warp noise. Values beyond 0.5 can be quite harsh.
* **Normalized**  
  Whether the noise is normalized or not.
* **Edge Behavior.**
  * **Edge**:
  * **Mirror**  
  Edge pixels are mirrored.
* **Modulation**  
  The amount of modulation to use from the Modulation input (if connected).
* **Modulation Direction**  
  Direction of the modulation.
* **Seed**  
  The randomization pattern or seed for the node's process.

### Iterative

* **Iterations**  
  Number of Warp iterations to apply.
* Mode: Mode of the iterations.
  * **Bitmap / VectorField / VectorFieldIntegral.**
