# Nuclear Fusion Open Source projects

I have initiated this repository to collect (and maintain?) a list of open-source projects related to (magnetic) Nuclear Fusion.

*Disclaimer*: At the moment, the list is "what I remembered". But I would like to accept any reasonable suggestions.

## General plasma physics libraries / toolboxes
* [**PlasmaPy**](https://github.com/PlasmaPy/PlasmaPy) ![GitHub User's stars](https://img.shields.io/github/stars/PlasmaPy/PlasmaPy?style=flat&label=%E2%AD%90): a collection of functionality commonly needed by plasma scientists and researchers globally

## Data standards / integrated modeling interfaces
* [**OMAS**](https://github.com/gafusion/omas) ![GitHub User's stars](https://img.shields.io/github/stars/gafusion/omas?style=flat&label=%E2%AD%90): OMAS is a Python library designed to simplify the interface of third-party codes with the ITER Integrated Modeling and Analysis Suite.

## Reactor / plant design, systems optimization, and CAD
**Integrated design frameworks**
* [**Bluemira**](https://github.com/Fusion-Power-Plant-Framework/bluemira) ![GitHub User's stars](https://img.shields.io/github/stars/Fusion-Power-Plant-Framework/bluemira?style=flat&label=%E2%AD%90): Bluemira is an integrated inter-disciplinary design tool for future fusion reactors.

**Systems codes / techno-economics**
* [**PROCESS**](https://github.com/ukaea/PROCESS) ![GitHub User's stars](https://img.shields.io/github/stars/ukaea/PROCESS?style=flat&label=%E2%AD%90): PROCESS is a systems code at UKAEA that calculates in a self-consistent manner the parameters of a fusion power plant with specified performance, ensuring that its operating limits are not violated, and with the option to optimise to a given function of these parameters.
* [**FAROES**](https://github.com/PlasmaControl/FAROES) ![GitHub User's stars](https://img.shields.io/github/stars/PlasmaControl/FAROES?style=flat&label=%E2%AD%90): Python package for optimizing fusion power plants, and especially for optimizing properties like their capital cost or levelized cost of energy.

**Parametric CAD**
* [**Paramak**](https://github.com/fusion-energy/paramak) ![GitHub User's stars](https://img.shields.io/github/stars/fusion-energy/paramak?style=flat&label=%E2%AD%90): Create parametric 3D fusion reactor CAD models
* [**ParaStell**](https://github.com/svalinn/parastell)![GitHub User's stars](https://img.shields.io/github/stars/svalinn/parastell?style=flat&label=%E2%AD%90): Create parametric 3D stellarator CAD models

## MHD equilibrium & reconstruction (tokamak + stellarator)
**Grad–Shafranov solvers / equilibrium manipulation (tokamak-oriented)**
* [**FreeGS**](https://github.com/freegs-plasma/freegs) ![GitHub User's stars](https://img.shields.io/github/stars/freegs-plasma/freegs?style=flat&label=%E2%AD%90): Equilibrium framework with freeboundary Grad-Shafranov equation solver.
* [**FreeGSNKE**](https://github.com/FusionComputingLab/freegsnke) ![GitHub User's stars](https://img.shields.io/github/stars/FusionComputingLab/freegsnke?style=flat&label=%E2%AD%90): The code based on FreeGS with implemented direct and evolution mode for solving G-S equation. (Free-boundary Grad-Shafranov Newton-Krylov Evolve)
* [**PLEQUE**](https://github.com/kripnerl/pleque) ![GitHub User's stars](https://img.shields.io/github/stars/kripnerl/pleque?style=flat&label=%E2%AD%90): Framework for easy equilibrium manipulation.

**Equilibrium reconstruction / working with reconstructions**
* [**GSFit**](https://github.com/tokamak-energy/gsfit) ![GitHub User's stars](https://img.shields.io/github/stars/tokamak-energy/gsfit?style=flat&label=%E2%AD%90), Grad-Shafranov Fit. Is a modern tokamak equilibrium reconstruction tool for post-shot experimental analysis.
* [**eqtools**](https://eqtools.readthedocs.io/en/latest/) ![GitHub User's stars](https://img.shields.io/github/stars/PSFCPlasmaTools/eqtools?style=flat&label=%E2%AD%90): eqtools is a Python package for working with magnetic equilibrium reconstructions from magnetic plasma confinement devices.

**3D equilibrium (stellarator / 3D MHD)**
* [**VMEC++**](https://github.com/proximafusion/vmecpp) ![GitHub User's stars](https://img.shields.io/github/stars/proximafusion/vmecpp?style=flat&label=%E2%AD%90): VMEC++ is a from-scratch C++ and Python reimplementation of the Variational Moments Equilibrium Code (VMEC).
* [**SPEC**](https://github.com/PrincetonUniversity/SPEC) ![GitHub User's stars](https://img.shields.io/github/stars/PrincetonUniversity/SPEC?style=flat&label=%E2%AD%90): The Stepped-Pressure Equilibrium Code, an advanced MRxMHD equilibrium solver.
* [**GVEC**](https://gitlab.mpcdf.mpg.de/gvec-group/gvec): Galerkin Variational Equilibrium Code - an open-source software for the generation of three-dimensional ideal MHD equilibria
* [**BIEST**](https://github.com/dmalhotra/BIEST) ![GitHub User's stars](https://img.shields.io/github/stars/dmalhotra/BIEST?style=flat&label=%E2%AD%90): Boundary Integral Equation Solver for Taylor states

## Stellarator optimization & community suites
* [**DESC**](https://github.com/PlasmaControl/DESC) ![GitHub User's stars](https://img.shields.io/github/stars/PlasmaControl/DESC?style=flat&label=%E2%AD%90): Stellarator Optimization Package
* [**STELLOPT**](https://github.com/PrincetonUniversity/STELLOPT) ![GitHub User's stars](https://img.shields.io/github/stars/PrincetonUniversity/STELLOPT?style=flat&label=%E2%AD%90): STELLOPT, the state-of-the-art stellarator optimization code
* [**simsopt**](https://github.com/hiddenSymmetries/simsopt) ![GitHub User's stars](https://img.shields.io/github/stars/hiddenSymmetries/simsopt?style=flat&label=%E2%AD%90): Simons Stellarator Optimizer Code
* [**ESSOS**](https://github.com/uwplasma/ESSOS) ![GitHub User's stars](https://img.shields.io/github/stars/uwplasma/ESSOS?style=flat&label=%E2%AD%90): e-Stellarator Simulation and Optimization Suite
* [**Stellarator-Tools**](https://github.com/ORNL-Fusion/Stellarator-Tools) ![GitHub User's stars](https://img.shields.io/github/stars/ORNL-Fusion/Stellarator-Tools?style=flat&label=%E2%AD%90): This is an umbrella project for the stellarator community tools.

## Transport / turbulence / integrated tokamak modeling
**1D core transport / integrated modeling**
* [**PINT**](https://gitlab.com/qualikiz-group/pyntegrated_model): PINT (Python INTegrated tokamak model) is a minimal integrated modelling suite in Python for tokamak 1D core transport.
* [**TORAX**](https://github.com/google-deepmind/torax) ![GitHub User's stars](https://img.shields.io/github/stars/google-deepmind/torax?style=flat&label=%E2%AD%90): Differentiable tokamak core transport simulator aimed for fast and accurate forward modelling, pulse-design, trajectory optimization, and controller design workflows.
* [**TANGO**](https://github.com/llnl/tango) ![GitHub User's stars](https://img.shields.io/github/stars/llnl/tango?style=flat&label=%E2%AD%90): Transport solver intended for coupling with codes that return turbulent fluxes.

**(Quasi-linear) gyrokinetics / turbulence model**
* [**QuaLiKiz**](https://gitlab.com/qualikiz-group): QuaLiKiz is a quasilinear gyrokinetic code rapid enough to ease systematic interface with experiments.)

## Fluid / hybrid / numerical simulation frameworks
* [**BOUT++**](https://github.com/boutproject) ![GitHub User's stars](https://img.shields.io/github/stars/boutproject?style=flat&label=%E2%AD%90): Plasma fluid finite-difference simulation code in curvilinear coordinate systems
* [**STRUPHY**](https://github.com/struphy-hub/struphy/) ![GitHub User's stars](https://img.shields.io/github/stars/struphy-hub/struphy?style=flat&label=%E2%AD%90): STRUPHY, a structure preserving hybrid code written in Python.
* [**OFT**](https://github.com/hansec/OpenFUSIONToolkit) ![GitHub User's stars](https://img.shields.io/github/stars/hansec/OpenFUSIONToolkit?style=flat&label=%E2%AD%90): Open Flexible Unstructured Simulation Infrastructure with Open Numerics (FUSION) Toolkit (OFT)

## Fast ions / particle orbits / particle loss
* [**ASCOT5**](https://github.com/ascot4fusion/ascot5) ![GitHub User's stars](https://img.shields.io/github/stars/ascot4fusion/ascot5?style=flat&label=%E2%AD%90): High-performance orbit-following code for fusion plasma physics and engineering.
* [**SIMPLE**](https://github.com/itpplasma/SIMPLE) ![GitHub User's stars](https://img.shields.io/github/stars/itpplasma/SIMPLE?style=flat&label=%E2%AD%90): Symplectic Integration Methods for Particle Loss Estimation
* [**BEAMS3D**](https://princetonuniversity.github.io/STELLOPT/BEAMS3D) ![GitHub User's stars](https://img.shields.io/github/stars/PrincetonUniversity/STELLOPT?style=flat&label=%E2%AD%90): High-performance orbit-following code contained in STELLOPT.

## Diagnostics, synthetic diagnostics, ray-tracing, spectroscopy, tomography
**Synthetic diagnostics / tomography**
* [**ToFu**](https://github.com/ToFuProject) ![GitHub User's stars](https://img.shields.io/github/stars/ToFuProject?style=flat&label=%E2%AD%90): Project for an open-source Python library for synthetic diagnostics and tomography for Fusion devices

**Neutral beam / fast-ion diagnostic modeling**
* [**Fidasim**](https://github.com/D3DEnergetic/FIDASIM) ![GitHub User's stars](https://img.shields.io/github/stars/D3DEnergetic%2FFIDASIM?style=flat&label=%E2%AD%90): A Neutral Beam and Fast-ion Diagnostic Modeling Suite*
* [**FILDSIM**](https://github.com/JoseRuedaRueda/uFILDSIM) ![GitHub User's stars](https://img.shields.io/github/stars/JoseRuedaRueda/uFILDSIM?style=flat&label=%E2%AD%90): FILD and INPA diagnostic simulator

**Spectroscopy**
* [**Cherab**](https://github.com/cherab) ![GitHub User's stars](https://img.shields.io/github/stars/cherab?style=flat&label=%E2%AD%90): Cherab Spectroscopy Modelling Framework

**Ray tracing (general / ECRH / x-ray optics)**
* [**XICSRT**](https://github.com/PrincetonUniversity/xicsrt) ![GitHub User's stars](https://img.shields.io/github/stars/PrincetonUniversity/xicsrt?style=flat&label=%E2%AD%90): General purpose, photon based, scientific raytracing code intended for both optical and x-ray raytracing.
* [**Raytrax**](https://github.com/proximafusion/raytrax) ![GitHub User's stars](https://img.shields.io/github/stars/proximafusion/raytrax?style=flat&label=%E2%AD%90): ECRH ray tracing in JAX

## Plasma boundary / PFC engineering / heat loads
* [**HEAT**](https://github.com/plasmapotential/HEAT) ![GitHub User's stars](https://img.shields.io/github/stars/plasmapotential/HEAT?style=flat&label=%E2%AD%90): The Heat flux Engineering Analysis Toolkit (HEAT) is a suite of tools for predicting the heat flux incident upon PFCs in tokamaks, and the associated PFC state (ie temperature).

## Impurity transport / neutrals / radiation
* [**Aurora**](https://github.com/fsciortino/Aurora) ![GitHub User's stars](https://img.shields.io/github/stars/fsciortino/Aurora?style=flat&label=%E2%AD%90): Modern toolbox for impurity transport, neutrals and radiation modeling in magnetically-confined plasmas

## Tokamak simulators (device-specific / surrogate-style)
* [**KSTAR-NN**](https://github.com/jaem-seo/KSTAR_tokamak_simulator) ![GitHub User's stars](https://img.shields.io/github/stars/jaem-seo/KSTAR_tokamak_simulator?style=flat&label=%E2%AD%90): KSTAR tokamak simulator

## Tags to search:

It is not easy to find fusion-related material since most keywords in the field have multiple meanings: `plasma`, `fusion`, `nuclear`, etc. Moreover, most projects do not use tags at all.

* [`stellarator`](https://github.com/topics/stellarator)
* [`stellarators`](https://github.com/topics/stellarators)
* [`tomamak`](https://github.com/topics/tokamak)
* [`tokamaks`](https://github.com/topics/tokamak)
* [`nuclear-fusion`](https://github.com/topics/nuclear-fusion)
* [`plasma`](https://github.com/topics/plasma): Beware of bloody KDE :smile:.
* [`fusion`](https://github.com/topics/fusion)


## Notes:

* [GitHub stars badge](https://shields.io/badges/git-hub-users-stars)
