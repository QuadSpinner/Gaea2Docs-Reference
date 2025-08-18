


The Cracks primitive creates large, cracked patterns on a flat base. You
can use it to mask other nodes or subtract it from other primitives
using the Combine node.

![](/images/ref/Cracks/Cracks.webp)

## Usage

#### Basic Technique

By using Combine to subtract out the Cracks output, you can cut out the
pattern in the main terrain.

![](/images/ref/Cracks/usage-1.webp)

#### Nested Patterns

The default pattern may seem to geometric and simplistic. This is by
design so you have broad room to make modifications.

Create 3 different nodes, one with large cracks, one with medium cracks,
and one with small and combine them for a more believable effect. As a
rule of thumb, you can take the largest size, right-click the `Scale`
slider and select the `Halve` button. Duplicate the node and halve it
again for the next node.

![](/images/ref/Cracks/usage-2.webp)

This may still look too simple for most usage scenarios. So you can add
distortions to the nodes by using the `Displace` option in the
[Modifier Stack](https://app.gitbook.com/s/-MRH8eXs83d5sUGKdsHp/getting-started/user-interface/property-editor/modifier-stack "mention"). This will create more natural-looking cracks.

![](/images/ref/Cracks/usage-3.webp)

{% hint style="info" %}
Remember to modify the `Seed` property under the Displacement post process slider to make each node randomized.
{% endhint %}

When subtracting this pattern out of another terrain, you can get complex, subtle effects.

If you need more elaborate distortions in your patterns, you can add a Warp node to each Cracks node.

![](/images/ref/Cracks/usage-4.webp)



# Properties


## Cracks

- Style
  - **Normal**  
  The default style that creates cracks that gentle slope inward.
  - **Hard**  
  The edges of the cracks are not refined and may show aliasing. This may be useful if the softer edges create artifacts in other nodes.
  - **Classic**  
  The default style from previous versions of Gaea. This is creates very thin cracks without a slope curve.
- **Octaves**  
  The number of crack pattern sets to generate.
- **Scale**  
  The overall size of the cracked pattern.
- **Depth**  
  The depth of the cracks. It also widens the cracks.
- **Jitter**  
  Control the offset of the cracks between symmetrical and chaotic.
- **Warp Strength**  
  The strength of the warp distortion applied to the cracks.
- **Warp Size**  
  The size of the warp distortion applied to the cracks.
- **Seed**  
  The randomization pattern or seed for the node's process.

## Advanced settings

- **Scale X**  
  The non-uniform scale on the X axis.
- **Scale Y**  
  The non-uniform scale on the Y axis.



