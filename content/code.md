+++
title = "Code"
weight = 10
draft = false
+++

{{< figure class="image main" src="/images/flem.gif" >}}
I develop numerical models of fluid flow related to Earth surface and interior processes. The codes are available from my <a href="https://bitbucket.org/johnjarmitage">bitbucket repository</a>.

<a href="https://bitbucket.org/johnjarmitage/flem">fLEM</a>: This is a landscape evolution model based on a set of sediment transport equations. The model uses a novel routing algorithm for surface run-off that minimises numerical resolution dependence. THe equations are solved using a finite element scheme built with the FEniCS library.

<a href="https://bitbucket.org/johnjarmitage/mess">MESS</a>: Multigrid Elasto-visco-plastic Strain Solver is a 2D thermo-mechanical code developed by Kenni Peteresn (University of Aarhus) and myself. This 2D code solves for the deformation of the upper mantle and includes the effects of decompression melting. The model uses a finite difference scheme and particle-in-cell approach to solve for the modified Stokes equations.

<a href="https://bitbucket.org/johnjarmitage/melt1d-icesheet">MELT1D</a>: I have developed a model of the percolation of lava through the upper mantle matrix. This model solves for the buoyant driven upwelling of melt assuming it can be captured as a Darcy flow. The model uses a total variance diminishing finite volume scheme in order to capture the migration of the front of melt. I developed this model to explore how deglaciation in Iceland during and after the last glacial maximum impacted volcanic eruptions and the outgassing of CO<sub>2</sub>.

{{< socialLinks >}}

