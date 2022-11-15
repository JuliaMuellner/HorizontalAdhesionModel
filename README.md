# HorizontalAdhesionModel

### Overview

In the framework of my Master thesis in the group of [Cell Biophysics and Statistical Physics](https://www.biostatphys.vetmed.uni-muenchen.de/index.html), the role of molecule unfolding in adhesion clusters under load is investigated.

This project provides a minimalist model that explores the dynamics of adhesion clusters in the presence of constant shear forces. It contains python scripts for simulating the dynamics, a python script for data analysis, a Mathematica notebook to compute an analytical solution as well as a data example.

### Files

*HorizontalModel-ParallelizedForce.ipynb*: 
simulates the system’s trajectory.  It is possible to run the code in parallel for different values of the force.

*HorizontalModel-ParallelizedXi.ipynb*:
simulates the system’s trajectory.  It is possible to run the code in parallel for different values of xi.

*HorizontalModel-ForceSteps.ipynb*:
simulates the dynamics and the possible rupture. The force is increased when the system reaches steady state. It is possible to run the code in parallel for different values of xi.

*HorizontalModel-DataAnalysis.ipynb*:
data analysis based on the simulations obtained by the above notebooks.

*ExpansionTerms.nb*:
computation of Taylor expansion terms up to 6th order.

*MeanOcc_SteadyState_xi0-0.2_gp20_gm1_f0-80-4_molinit100-60-20-10_noreac600000_F0-1.pkl*:
example data set. Contains mean occupation numbers for a system in steady state for different xi (0, 0.05, 0.1, 0.15, 0.2) and forces ranging from 0-80 with a stepsize of 4.

*MeanVelocity_SteadyState_xi0-0.2_gp20_gm1_f0-80-4_molinit100-60-20-10_noreac600000_F0-1.pkl*:
example data set. Contains the corresponding velocities to the above mean occupation numbers.

*OrderCorrections_gp10-20_gm1.pkl*:
example data set. Contains the correction terms obtained by the Mathematica notebook.
