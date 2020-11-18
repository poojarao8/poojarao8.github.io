---
permalink: /
title: "Research backgroud"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I have been working as a [postdoctoral researcher](http://www.math.stonybrook.edu/cards/raopooja.html) in the Department of Mathematics at Stony Brook University. Prior to this, I was a postdoctoral researcher in the Department of Aerospace Engineering at University of Illinois at Urbana-Champaign.

My general area of interest is fluid dynamics and scientific computing. I am interested in studying gas/gas and gas/particle multiphase flows influenced by shock, using high fidelity numerical algorithms. I am also interested in studying coupled heat transfer in porous geometries. For my Ph. D. work in the Department of Applied Mathematics and Statistics at Stony Brook, I studied turbulent mixing in hydrodynamical instabilties such as Richtmyer-Meshkov and Rayleigh-Taylor, using front-tracking method. 

I am working on the development of an efficient, parallel implementation of Dennis Sullivan's [Lattice Hydrodynamics model](https://arxiv.org/abs/1811.00086), which is a finite scale model of the fluid written in operations of combinatorial topology, and derived from momentum conservation laws. Interestingly, since the model makes use of operators of combinatorial topology, more modern ideas of cumulants in algebraic topology can be used to deduce more accurate approximations of the non-linear term. We are interested in investigating whether the introduction of these cumulants yield a more efficient and accurate calculation by conducting large scales simulations of flows using this approach and analyzing if its unique development can lend new insights to the “blow-up” phenomenon. Utilizing a hybrid parallelization (MPI/OpenMP) strategy, we are running massively-parallel simulations to investigate and refine this model.

# Current research: Quantum computing

More recently, I have been studying numerical integration using quantum computing on today's noisy quantum devices. The field of quantum computing, although still in its nascent phase, has seen some significant progress since its inception in the 1980s. However, quantum noise is still a major obstacle for today’s quantum machines, often referred to as the Noisy Intermediate-Scale Quantum (NISQ) devices. Thus, it is important to design algorithms that work around the limitations of the current NISQ devices. One of the most notable algorithms with several applications is the Quantum Amplitude Estimation (QAE) algorithm, but it is prohibitively expensive for NISQ devices. One important application of quantum amplitude estimation is computing integrals. 

With numerical integration as the focus of our study, we are interested in practical algorithms, such as the recently proposed quantum-classical variants of QAE algorithm, namely the maximum likelihood estimation and the iterative amplitude estimation. By implementing them on the IBM Quantum machine using Qiskit, an open source framework for quantum computing, we have analyzed and discussed the implementation and performance of each algorithm from a practical perspective, taking into account the accuracy and the efficiency and the tradeoffs between the two. 

---

