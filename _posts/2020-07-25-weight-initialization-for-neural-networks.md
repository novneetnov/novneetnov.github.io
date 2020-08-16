---
title: How to properly initialize weights of a neural network
tags: [Deep Learning]
style: fill
color: warning
description: The why, what & how of initialization of Deep Neural Networks 
---

For a neural network to work desirably, the first thing that is required is
to properly initialize the parameter weights. The initial weights will gravitate the
results produced by the network in a certain direction. In other words, it is one of the sources
that biases the network.

First, lets discuss what happens when we initialize the weights to zero.

## ZERO INITIALIZATION
The most intuitive assumption that comes to mind is to initialize all the weights to zero.
However, that doesn't work as the network fails to break symmetry. This means, all the nodes in the network,
behave the exact same way. All the nodes of the first layer get the same input. 

