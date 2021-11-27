---
layout: page
title: Two Phase Lithiation
permalink: /2phaselith/
---

The two phase lithiation problem deals with lithium diffusion into a circular silicon anode, which results in 
the formation of a two-phase interface having pure silicon inside and an amorphous Li-Si phase surrounding it. 
This problem is solved using the Cahn-Hilliard equation with the phase lithium concentration (<a href="https://www.codecogs.com/eqnedit.php?latex=\hat{c}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\hat{c}" title="\hat{c}" /></a>) as the phase 
field variable. The governing euation for the problem is:

<a href="https://www.codecogs.com/eqnedit.php?latex=\dot{\hat{c}}&space;=&space;-\nabla.(-M(\hat{c})\nabla&space;\mu)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dot{\hat{c}}&space;=&space;-\nabla.(-M(\hat{c})\nabla&space;\mu)" title="\dot{\hat{c}} = -\nabla.(-M(\hat{c})\nabla \mu)" /></a>

where,

<a href="https://www.codecogs.com/eqnedit.php?latex=\mu&space;=&space;c_{max}RT(ln(\frac{\hat{c}}{1-\hat{c}})&space;&plus;&space;\Omega(1-2\hat{c}))&space;-&space;\kappa&space;\nabla^2&space;\hat{c}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mu&space;=&space;c_{max}RT(ln(\frac{\hat{c}}{1-\hat{c}})&space;&plus;&space;\Omega(1-2\hat{c}))&space;-&space;\kappa&space;\nabla^2&space;\hat{c}" title="\mu = c_{max}RT(ln(\frac{\hat{c}}{1-\hat{c}}) + \Omega(1-2\hat{c})) - \kappa \nabla^2 \hat{c}" /></a>
 
The results are summarised in the following figure and they match closely with the figure 3 of [L. Chen](https://iopscience.iop.org/article/10.1149/2.0171411jes)'s paper.

![Two Phase Lithiaton Model](/images/2phase_all.jpg)