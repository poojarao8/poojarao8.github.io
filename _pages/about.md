---
permalink: /
title: "Research Backgroud"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently working as a [Visiting Postdoc](http://www.math.stonybrook.edu/cards/raopooja.html) in the Department of Mathematics at Stony Brook University. My mentor is [Dr. Dennis Sullivan](http://www.math.stonybrook.edu/~dennis/). Prior to my current position, I was a postdoctoral researcher in the Department of Aerospace Engineering at University of Illinois at Urbana-Champaign.

My general area of interest is fluid dynamics and scientific computing. I am interested in studying gas/gas and gas/particle multiphase flows influenced by shock, using high fidelity numerical algorithms. I am also interested in studying coupled heat transfer in porous geometries. For my Ph. D. work in the Department of Applied Mathematics and Statistics at Stony Brook, I studied turbulent mixing in hydrodynamical instabilties such as Richtmyer-Meshkov and Rayleigh-Taylor, using front-tracking method.

---
# Current Work

 
For my current work, I am working on the development of an efficient, parallel implementation of Dennis Sullivan's [Lattice Hydrodynamics model](https://arxiv.org/abs/1811.00086), which is a finite scale model of the fluid written in operations of combinatorial topology, and derived from momentum conservation laws. Interestingly, since the model makes use of operators of combinatorial topology, more modern ideas of cumulants in algebraic topology can be used to deduce more accurate approximations of the non-linear term. We are interested in investigating whether the introduction of these cumulants yield a more efficient and accurate calculation by conducting large scales simulations of high Re flows using this approach and analyzing if its unique development can lend new insights to the “blow-up” phenomenon. Utilizing a hybrid parallelization (MPI/OpenMP) strategy, we plan to run large scale, massively-parallel simulations to investigate this model in this regime.

I also work on developing spectral numerical models using eigenbasis of curl operator, to study incompressible flows in turbulent conditions. These methods will be used to study the potential blow up of Navier-Stokes equations in low viscosity regime.


