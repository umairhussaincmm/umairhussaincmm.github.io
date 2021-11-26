---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
Welcome to Umair Hussain's peronal page!

![Umair Hussain](/images/dp.jpg)

## Educational Background
**Direct PhD (Started in 2019):** at [Indian Institute of Technology Madras, Chennai](https://mech.iitm.ac.in/meiitm/)

**Bachelor of Technology in Mechanical Engineering (2019):** *passed with 9.66 CPI* from [Jamia Millia Islamia, New Delhi](https://www.jmi.ac.in/mechanical)

**Intermediate (2015):** *passed with 88.4% of marks* from [Senior Secondary School (Boys), AMU, Aligarh](https://www.amu.ac.in/schools/saiyyid-hamid-senior-secondary-school-boys/home-page)

**High School (2013):** *passed with 10 CGPA* from [Bishop Conrad Senior Secondary School, Bareilly (CBSE Board)](https://bcsbareilly.com/)

## Skills
- Finite Element Method
- Phase Field Modelling
- Programming Languages
  - C++
  - Python
  - Matlab
- Softwares
  - Deal II
  - Paraview
  - SageMath
  - LaTex

## Research Work
We are working on a generalised software framework to model the multiphase microstructure evolution using Multiphase field method implemented using 
Finite Element method. The framework would provide a modular interface to the user so that they can choose various parameters and number of phases according 
to their need.

**What is the Phase-field modelling?**

The Phase-field modelling has been the backbone of the computational material science. It is a thermodynamically robust modelling technique used to study 
the microstructure evolution. It uses a phase field variable, which takes up a definite value for each phase and varies smoothly over the interface, hence 
eliminating the need to track the interface explicitly. The value of the phase variable is determined by the minimisation of the total Gibbs free energy of 
the system.

**FEM Implementation of Phase-field Models**

The Phase-field modelling has been using different numerical methods like, Finite Differences (FE), Finite Volume (FV) or Fourier spectral methods. But with
the role of stresses and deformations in the microstructure evolution now being highlighted more, FEM seems to be a better choice for solving the PF equations.
The Finite Element Method has been popular in deeling with mechanics related problems more conveniently than other numerical methods. Our envisioned solver code 
will be built upon exisitng FEM libraries, known as [Deal II](https://www.dealii.org/)

**Sample Problems to Benchmark my Deal II codes**

1. [Unsteady Heat Equation (Parabolic Equation)](https://umairhussaincmm.github.io/heat-equation/)

2. [Dendritic Crystal Growth Problem](https://umairhussaincmm.github.io/kobayashi/)

3. [Two-phase Lithiation](https://umairhussaincmm.github.io/kobayashi/)