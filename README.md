# DMD-for-ergodic-systems
This folder shows the application of Dynamic Mode Decomposition (DMD) algorithm for computing the eigenvalues and eigenfunctions of the Koopman operator  for **dynamical systems with ergodic attractors** following the paper  
"Ergodic Theory, Dynamic Mode Decomposition and Computation of Koopman scpectral properties"
SIAM Journal on Applied Dynamical Systems (also on arXiv), by Hassan Arbabi & Igor Mezic, 2017 (https://arxiv.org/pdf/1611.06664.pdf).


### The examples in the root folder:

* Lorenz_POD: computation of a POD basis for observables on chaotic Lorenz attractor,  
* QPeriodicCavityFlow: computation of Koopman eigenvalues for quais-periodic nonlinear flows using Exact Hankel-DMD,
* VanDerPol_phase: computation of asymptotic phase for trajectories of Van der Pol oscillator.




### The DMD routines in the +DMD folder:

* Hankel-DMD (algorithm suggested in the above paper),

* companion-matrix DMD (Rowley et al 2009, Journal of Fluid Mechanics),
* SVD-enhanced DMD (Schmid 2010, Journal of Fluid Mechanics),
* EXACT_DMD (Tu et al 2015, Journal of Computational Dynamics). 


Send comments and questions to arbabiha@gmail.com.

H. Arbabi

November 2017
