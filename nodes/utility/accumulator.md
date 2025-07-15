# Accumulator

One of the common ways a graph gets clutters with overlapping connections is when multiple Snow, Lake, or Debris nodes are used and their respective masks need to be combined for further use.

The new Accumulator node is a special type of standalone Generator node that can collect all such masks for you without creating several connections.

It works for Snow Mask, Snow Depth, Water Mask, Water Depth, Shore Mask, Debris Mask, Debris Color Index.

{% hint style="warning" %}
The Accumulator will only add nodes that have been built. To ensure all required nodes are built, connect the last node you will use for masking with the Accumulator output to the Accumulator Input. This will not affect the Accumulator but will ensure that all appropriate nodes are built.
{% endhint %}

* Type
  * **SnowMask**: Accumulate all snow as a flat mask.
  * **SnowDepth**: Accumulate all Snow Depth at absolute values.
  * **Rivers**: Accumulate all rivers.
  * **WaterMask**: Accumulate all water as a flat mask.
  * **WaterDepth**: Accumulate all Water Depth in absolute values.
  * **ShoreMask**: Accumulate all Shore masks.
  * **DebrisMask**: Accumulate all DebrisMask (using Max mode)
  * **DebrisColor**: Accumulate just the DebrisColor (using Max mode).

