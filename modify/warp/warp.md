# Warp



Warp is a more powerful version of @Displace. It can take the terrain
and "warp" the shape creating more organic shapes. In terrains it can
help create more believable shapes or alter simple shapes into a more
complex formation. In masks, it can help create breakups that can make a
linear mask more random and chaotic without losing its general shape.

#### Comparison to Displace

Unlike @Displace, Warp uses a more complex algorithm while being
significantly faster. (Up 60x in many situations)

By using vector fields, the warping created by this node result in more
comprehensive shapes without creating directional tearing or
over-stretching the original shape.

#### Warp as a Post Process

Warp is also built into the @postprocess for easy access.




# Properties


## Warp

- **Size**: 
- **Strength**: 
- **Z Scale**: 
- Warp Source
  - **PerlinFBM**: <desc>
  - **VoronoiR**: <desc>
  - **VoronoiP**: <desc>
  - **VoronoiA**: <desc>
  - **VoronoiS**: <desc>
  - **VoronoiM**: <desc>
  - **VoronoiD**: <desc>
- **Perturbation**: 
- **Complexity**: 
- **Roughness**: 
- **Normalized**: 
- Edge Behaviour
  - **Edge**: 
  - **Mirror**: Edge pixels are mirrored.
- **Modulation**: 
- **Modulation Direction**: 
- **Seed**: The randomization pattern or seed for the node's process.

## Iterative

- **Iterations**: 
- Mode
  - **Bitmap**: 
  - **VectorField**: <desc>
  - **VectorFieldIntegral**: <desc>



