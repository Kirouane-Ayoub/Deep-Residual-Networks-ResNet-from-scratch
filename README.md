# Deep-Residual-Networks-ResNet-from-scratch

What is ResNet?

The Residual Blocks idea was created by this design to address the issue of the vanishing/exploding gradient. We apply a method known as skip connections in this network. The skip connection bypasses some levels in between link-layer activations to subsequent layers. This creates a leftover block. These leftover blocks are stacked to create resnets.

![1_SGrc3VC3fbirosDPW0AmMA](https://user-images.githubusercontent.com/99510125/204150163-c450e90f-d975-4dc7-892f-62362a13d503.png)

What problems do ResNets solve?

One of the problems ResNets solve is the famous known vanishing gradient. This is because when the network is too deep, the gradients from where the loss function is calculated easily shrink to zero after several applications of the chain rule. This results in the weights never updating their values and therefore, no learning is being performed.
With ResNets, the gradients can flow directly through the skip connections backward from later layers to initial filters.
