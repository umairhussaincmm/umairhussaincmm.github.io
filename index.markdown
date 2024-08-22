---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
Welcome to Umair Hussain's peronal page!

![Umair Hussain](/images/dp.jpg)

## About
I am a PhD scholar at IIT Madras, working in the area of computational mechanics & materials modeling. My area of expertise includes phase field modeling, finite element method, computational plasticity and electrochemical modeling. I am also proficient in an open-source FEM library, deal.II.

## Educational Background
**Direct PhD (Started in 2019):** at [Indian Institute of Technology Madras, Chennai](https://mech.iitm.ac.in/meiitm/)

**Bachelor of Technology in Mechanical Engineering (2019):** *passed with 9.66 CPI* from [Jamia Millia Islamia, New Delhi](https://www.jmi.ac.in/mechanical)

**Intermediate (2015):** *passed with 88.4% of marks* from [Senior Secondary School (Boys), AMU, Aligarh](https://www.amu.ac.in/schools/saiyyid-hamid-senior-secondary-school-boys/home-page)

**High School (2013):** *passed with 10 CGPA* from [Bishop Conrad Senior Secondary School, Bareilly (CBSE Board)](https://bcsbareilly.com/)

## Research Work
In my research, I developed a comprehensive multiphysics model using phase field modeling to explore the electrochemical response during lithiation processes. This model enabled an in-depth analysis of how phase separation impacts the electrochemical behavior during battery charging and discharging cycles. To address battery degradation, I investigated the effects of mechanical deformation, focusing on both elastic and elasto-plastic deformations, and their influence on electrochemical responses. Through this work, I demonstrated how voltammograms could be interpreted to uncover underlying physical phenomena within the battery system.

Further advancing the model, I developed a multiphase field solver capable of incorporating more than two phases into the lithiation model, providing a more accurate representation of the material behavior. All solvers were implemented using the C++-based open-source library, deal.II. To enhance computational efficiency, I parallelized the code using MPI and PETSc.

## Skills
- Finite Element Method
- Phase Field Modelling
- Programming Languages
  - C++
  - Python
  - Matlab
  - Latex
- Softwares
  - Deal II
  - Paraview
  - SageMath
  - LaTex
- Linux
- Git

**What is Phase-field modelling?**

The Phase-field modelling has been the backbone of the computational material science. It is a thermodynamically robust modelling technique used to study 
the microstructure evolution. It uses a phase field variable or an order parameter, which takes up a definite value for each phase and varies smoothly over the interface, hence 
eliminating the need to track the interface explicitly. The value of the order parameter is determined by the minimisation of the total Gibbs free energy of 
the system.

**FEM Implementation Of Phase-field Models**

The Phase-field modelling has been using different numerical methods like, Finite Differences (FD), Finite Volume (FV) or Fourier spectral methods. But with
the role of stresses and deformations in the microstructure evolution now being highlighted more, FEM seems to be a better choice for solving the PF equations.
The Finite Element Method has been popular in dealing with mechanics related problems more conveniently than the other numerical methods. Our envisioned solver code 
will be built upon existing FEM libraries, known as [Deal II](https://www.dealii.org/).

**Sample Problems To Benchmark The Deal II codes**

1. [Unsteady Heat Equation (Parabolic Equation)](https://umairhussaincmm.github.io/heat-equation/)

2. [Dendritic Crystal Growth Problem](https://umairhussaincmm.github.io/kobayashi/)

3. [Two-Phase Lithiation](https://umairhussaincmm.github.io/2phaselith/)

**Problems Validated Using The Generalised Multi-Phase Field Deal II Code**

1. [Peritectic Reaction Problem](https://umairhussaincmm.github.io/peritectic/)
