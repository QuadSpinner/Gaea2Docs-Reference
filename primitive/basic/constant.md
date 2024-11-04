---
description: >-
  Constant is one of the lowest-level nodes. It is deceptively simple but can be
  very useful.
---

# Constant

## Constant

The Constant node is the most basic primitive available in Gaea. It can create two outputs: a flat terrain of a specified height, or a flat color output.

Constant is rarely used directly, but rather as a mask or second input blended using [combine.md](../../utility/routing/combine.md "mention").



## Properties

| Property     | Description                                                   |
| ------------ | ------------------------------------------------------------- |
| **Constant** |                                                               |
| Output       | The output type.                                              |
|              | **Height:** Create a flat terrain of the specified height.    |
|              | **Color:** Create a flat color output of the specified color. |
| Height       | The height of the blank terrain.                              |
| Color        | The color to use for creating a flat, color output.           |

## Examples

* The uniform height "block" terrain can be used with [combine.md](../../utility/routing/combine.md "mention") in `Max` mode to create a flat area at the specified height in a terrain.
* The uniform color output can be used for blending various textures or combining a flat color on top of an existing color map to modify the tint via various blend modes.



{% hint style="info" %}
Gaea 1's Constant node's noise mode is now available as the [noise.md](noise.md "mention") primitive.
{% endhint %}



