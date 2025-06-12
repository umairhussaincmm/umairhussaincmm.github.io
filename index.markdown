---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
Welcome to Umair Hussain's personal page!

![Umair Hussain](/images/dp2.jpg)

## About
I am a data scientist with a PhD in computational mechanics, applying data science methods to physics-informed problems. My work leverages a strong foundation in electrochemical modeling, physical simulations, and numerical methods to develop interpretable and efficient solutions for scientific and engineering applications. I specialize in combining data-driven approaches with physics-based modeling, particularly in the context of Li-ion battery systems. I am also proficient in the open-source FEM library [deal.II](https://www.dealii.org/), and have contributed a standalone code to the [deal.II code gallery](https://www.dealii.org/current/doxygen/deal.II/code_gallery_Crystal_Growth_Phase_Field_Model.html).

## Educational Background
**Direct Ph.D. (M.S.+Ph.D.) (2019-2025):** at [Indian Institute of Technology Madras, Chennai](https://mech.iitm.ac.in/meiitm/)

**Bachelor of Technology in Mechanical Engineering (2015-2019):** *passed with 9.66 CPI* from [Jamia Millia Islamia, New Delhi](https://www.jmi.ac.in/mechanical)

**Intermediate (2015):** *passed with 88.4% of marks* from [Senior Secondary School (Boys), AMU, Aligarh](https://www.amu.ac.in/schools/saiyyid-hamid-senior-secondary-school-boys/home-page)

**High School (2013):** *passed with 10 CGPA* from [Bishop Conrad Senior Secondary School, Bareilly (CBSE Board)](https://bcsbareilly.com/)

## Research Work
My PhD research focused on modeling the electrochemical responses of Li-ion battery anodes using a multiphysics approach. I developed a robust phase field model with stress-coupled diffusion and Butler-Volmer reaction kinetics to study the effects of phase separation and mechanical deformation (elastic and plastic) on voltammetry during (dis)charging cycles. 

To push the boundaries further, I built a generalized multiphase field solver and extended it for use in large-scale simulations using MPI and PETSc. I also contributed to the data-driven modeling by developing Gaussian process regression models that mapped voltammetric features to microstructural properties like grain size.

### Publications
1. [**U. Hussain**, G. Phanikumar, and N. Swaminathan, “Mapping of multiphase field model parameters to physical factors in order to simulate desired phase transformations,” Computational Materials Science, vol. 226, p. 112 227, Jun. 2023, issn: 0927-0256.](https://doi.org/10.1016/J.COMMATSCI.2023.112227)
2. [**U. Hussain**, N. Swaminathan, and G. Phanikumar, “Numerical voltammetry of phase separating materials using phase field modeling,” *Journal of The Electrochemical Society*, vol. 171, no. 7, p. 070502, 2024.](https://doi.org/10.1149/1945-7111/ad59cc)
3. [**U. Hussain**, N. Swaminathan, and G. Phanikumar, “A multi-phase field framework application to the study of the peritectic reaction for an arbitrary material system,” in Recent Advances in Mechanics of Functional Materials and Structures, P. Kumari and S. K. Dwivedy, Eds., Singapore: Springer Nature Singapore, 2024, pp. 231–240, isbn: 978-981-99-5919-8.](https://doi.org/10.1007/978-981-99-5919-8_20)
4. [A. K. Agrawal, N. Swaminathan, and **U. Hussain**, “Probabilistic modelling of the nonlinear mapping between voltammograms and the grain size of the electrode material in Li-ion batteries using optimally tuned Gaussian process regression models,” *Journal of The Electrochemical Society*, vol. 172, no. 1, p. 013501, 2025.](https://doi.org/10.1149/1945-7111/ada0b6)



## Skills
- **Computational Modeling:** Phase field modeling, finite element method, plasticity, stress-coupled diffusion, voltammetry diagnostics
- **Programming Languages:** C++, Python, MATLAB, LaTeX
- **Software & Libraries:** deal.II, PETSc, ParaView, SageMath, PyTorch, Scikit-learn, Pandas, NumPy
- **Technical Capabilities:** Parallel Computing, Git, Linux

**What is Phase-field modelling?**

Phase-field modeling is a thermodynamically robust technique used to simulate microstructure evolution by defining a continuous order parameter that smoothly transitions between phases. This approach removes the need to explicitly track interfaces and is ideal for studying phase separation, grain growth, solidification, and other diffusion-driven phenomena.


**FEM Implementation Of Phase-field Models**

The Phase-field modelling has been solved using different numerical methods like, Finite Differences (FD), Finite Volume (FV) or Fourier spectral methods. But with
the role of stresses and deformations in the microstructure evolution now being highlighted more, FEM seems to be a better choice for solving the PF equations.
The Finite Element Method has been popular in dealing with mechanics related problems more conveniently than the other numerical methods. My solvers are implemented using the modern C++ FEM library [deal.II](https://www.dealii.org/), enabling robust and scalable simulations of complex electrochemical systems.

**Sample Problems To Benchmark The Deal II codes**

1. [Unsteady Heat Equation (Parabolic Equation)](https://umairhussaincmm.github.io/heat-equation/)

2. [Dendritic Crystal Growth Problem](https://umairhussaincmm.github.io/kobayashi/)

3. [Two-Phase Lithiation](https://umairhussaincmm.github.io/2phaselith/)

**Problems Validated Using The Generalised Multi-Phase Field Deal II Code**

1. [Peritectic Reaction Problem](https://umairhussaincmm.github.io/peritectic/)
