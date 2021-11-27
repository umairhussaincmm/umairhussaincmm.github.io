---
layout: page
title: Crystal Growth Problem
permalink: /kobayashi/
---

The crystal growth problem is our first step towards understanding the intricacies of the phase field modelling.
The problem solves for the solidification behaviour of an undercooled liquid. It is demonstrated how the 
variation in the value of the dimensionless latent heat parameter (K) leads to change of interface from planar 
to dendritic.

The model solves for the following system of non-linear time dependent equations, solving for the phase variable (p) and 
the temperature field (T). The value p=1 corresponds to solid phase and p=0 corresponds to liquid phase while 
any value in between represents the interface.

<a href="https://www.codecogs.com/eqnedit.php?latex=\tau&space;\frac{\partial&space;p}{\partial&space;t}&space;=&space;\nabla&space;\cdot(&space;\left(\epsilon^2\right)\nabla&space;p)&space;&plus;&space;p(1-p)(p-\frac{1}{2}&plus;m(t))" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\tau&space;\frac{\partial&space;p}{\partial&space;t}&space;=&space;\nabla&space;\cdot(&space;\left(\epsilon^2\right)\nabla&space;p)&space;&plus;&space;p(1-p)(p-\frac{1}{2}&plus;m(t))" title="\tau \frac{\partial p}{\partial t} = \nabla \cdot( \left(\epsilon^2\right)\nabla p) + p(1-p)(p-\frac{1}{2}+m(t))" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\partial&space;T}{\partial&space;t}=\nabla^2T&plus;K\frac{\partial&space;p}{\partial&space;t}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\partial&space;T}{\partial&space;t}=\nabla^2T&plus;K\frac{\partial&space;p}{\partial&space;t}" title="\frac{\partial T}{\partial t}=\nabla^2T+K\frac{\partial p}{\partial t}" /></a>

where,

<a href="https://www.codecogs.com/eqnedit.php?latex=m(t)&space;=&space;\frac{\alpha}{\pi}\tan^{-1}(\gamma(T_e-T))" target="_blank"><img src="https://latex.codecogs.com/gif.latex?m(t)&space;=&space;\frac{\alpha}{\pi}\tan^{-1}(\gamma(T_e-T))" title="m(t) = \frac{\alpha}{\pi}\tan^{-1}(\gamma(T_e-T))" /></a>

The results are summarised in the following figure and they match closely with the figure 5 of [Ryo Kobayashi](https://www.sciencedirect.com/science/article/pii/016727899390120P?via%3Dihub)'s paper.

![Dendiritic Growth](/images/kobayashi-under.jpg)