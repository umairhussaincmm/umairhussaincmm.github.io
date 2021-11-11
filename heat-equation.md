---
layout: page
title: Crystal Growth Problem
permalink: /heat-equation/
---
The governing equation for the unsteady heat conduction is:

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\partial&space;T}{\partial&space;t}&space;=&space;\alpha&space;\frac{\partial&space;\textsuperscript{2}&space;T}{\partial&space;x&space;\textsuperscript{2}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\partial&space;T}{\partial&space;t}&space;=&space;\alpha&space;\frac{\partial&space;\textsuperscript{2}&space;T}{\partial&space;x&space;\textsuperscript{2}}" title="\frac{\partial T}{\partial t} = \alpha \frac{\partial \textsuperscript{2} T}{\partial x \textsuperscript{2}}" /></a>

The problem is solved in 1D with zero flux condition at left and zero dirichilet boundary condition at right.
For first case the initial temperature distribution is constant and for second it is linear. The FEM results 
are compared with the analytical solution in the following figures:

![Conduction-constant](/images/ConsFvA.png)

![Conduction-linear](/images/LinearFvA.png)