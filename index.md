# FPS Code Suite

[Flow Physics and Simulation (FPS)](https://github.com/flow-physics-simulation/flow-physics-simulation/edit/gh-pages/index.md) is a compuational laboratory for studying a wide range of fluid mechanics phenomena.  

FPS is composed of a range of individual codes, each a different GitHub repository, that can be used together to explore fundamental fluid mechanics phenomena (both linear and nonlinear).

The core code is [LNS3D](https://sscollis.github.io/lns3d/) which is the primary solver for both compressible linear and nonlinear analyses.  In general there are codes for both compressible and incompressible flows, although the primary focus of FPS has been on compressible flow so that the capabilities are more extensive.

## Compressible

Code     |     Description
---------|--------------------------------------------------------
[LNS3D](https://github.com/sscollis/lns3d)    |  Primary 2d3c linear and nonlinear Navier-Stokes solver
[FSC](https://github.com/sscollis/fsc)      |  3D boundary layer similarity solutions
[COMPBL](https://github.com/sscollis/compbl)   |  3D boundary layer similarity solutions
[NPOT](https://github.com/sscollis/npot)     |  Compressible potential flow
[STAB](https://github.com/sscollis/stab)     |  Direct linear stabilty solver (curvature and receptivity included)
[SHOOT](https://github.com/sscollis/shoot)    |  Shooting linear stability solver (curvature and nonparallel)

## Incompressible

Code     |     Description
---------|--------------------------------------------------------
[DYNISO](https://github.com/sscollis/dyniso)   |  Isotropic homogeneous turbulence solver
[PSE](https://github.com/sscollis/pse)      |  Parabolized Stabilty Equation (PSE) solver
[OS-STAB](https://github.com/sscollis/os-stab)  |  Orr-Sommerfeld solver using Conte shooting (Blasius solver included)

## Contact

S. Scott Collis\
flow.physics.simulation@gmail.com
