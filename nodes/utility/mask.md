
## Mask

Gaea 2 introduces the new `Mask` node which allows you to mask the node/effect **after** it has been created. You can connect the Mask node after an effect has been applied. For example, in a `Mountain > Erosion > Mask scenario`, the Mask will automatically use the applied mask between Mountain and Erosion.

{% hint style="warning" %}
If you're looking for 2D drawing node from Gaea 1, see [draw.md](../primitive/draw.md "mention")
{% endhint %}

If you have multiple nodes that create the "effect" you wish to mask, just connect the second port of the Mask node to the desired "before" node. For example, in `Mountain > Erosion > Sandstone > Thermal2 > Mask`, you would connect the second input to Mountain.

## Properties

This is very useful because when a node is masked directly, a change to the mask will force a rebuild of the entire node. However, a Mask node adds masking as a post-process and is extremely fast.

{% hint style="info" %}
There is no difference in results between the Mask port on a node and the Mask node. It is highly recommended that Mask **node** be used when possible as it will make your builds faster, and adapt your workflow to the modern specifications recommended by Gaea 2.0.
{% endhint %}
