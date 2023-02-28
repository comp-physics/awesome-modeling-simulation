# Awesome Modeling & Simulation <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome Badge"/> [![LinkCheck Action Status](https://github.com/comp-physics/awesome-modeling-simulation/workflows/LinkChecker/badge.svg)](https://github.com/comp-physics/awesome-modeling-simulation/actions)

Resources for learning about modeling and simulation.
This document is a work in progress, but nevertheless contains useful information.
Background expected in linear algebra and a typical calculus sequence.

_Disclaimer:_ Most linked content is _not_ licensed, owned, or maintained by S. H. Bryngelson, nor can I ensure the correctness of any of the below resources. 
Use for educational purposes and at your own risk.

## Table of contents 

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Linear algebra refresher](#linear-algebra-refresher)
- [Discrete versus continuous time models](#discrete-versus-continuous-time-models)
- [Analysis of dynamical systems](#analysis-of-dynamical-systems)
  - [1D dynamical systems](#1d-dynamical-systems)
  - [2D+ dynamical systems](#2d-dynamical-systems)
- [Numerical methods for ODEs and PDEs](#numerical-methods-for-odes-and-pdes)
- [Cellular automata](#cellular-automata)
- [Markov chain model](#markov-chain-model)
- [Discrete-event simulation and queuing models](#discrete-event-simulation-and-queuing-models)
- [Input-output analysis](#input-output-analysis)
- [Creating dynamical systems from observations](#creating-dynamical-systems-from-observations)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Linear algebra refresher 

- [Gilbert Strang lectures on Linear Algebra ](https://www.youtube.com/playlist?list=PL49CF3715CB9EF31D)

- [Introduction to Linear and Matrix Algebra (Nathaniel Johnston) (textbooks)](https://link.springer.com/book/10.1007/978-3-030-52811-9)

- [Linear Algebra Done Right (Axler, Sheldon Jay) (textbooks)](https://linear.axler.net/)

- [Numerical Linear Algebra (Lloyd N. Trefethen, David Bau III) (textbooks)](https://www.amazon.com/Numerical-Linear-Algebra-Lloyd-Trefethen/dp/0898713617)

## Discrete versus continuous time models

- [Linear System Representation- MATLAB & Simulink Documentation](https://www.mathworks.com/help/control/linear-system-modeling.html?s_tid=CRUX_lftnav)

- [Basic Models- including continuous and discrete time models](https://www.mathworks.com/help/control/fixed-coefficient-models.html)

## Analysis of dynamical systems

### 1D dynamical systems

- [One dimensional Systems (video)](https://www.youtube.com/watch?v=YNIm2Op7UPg)

- [Geometric Approach 1D systems](http://www.ccs.fau.edu/~fuchs/pub/Huys_nonlin.pdf)

- [Princeton Notes for 1D systems (Pillow Lab)](http://pillowlab.princeton.edu/teaching/mathtools21fall/notes/notes_Dynamics.pdf)

- [Cornell Notes for 1D systems (Jonathan Victor)](http://www-users.med.cornell.edu/~jdvicto/jdv/mathcourse1617/mathcourse1617_Drover.pdf)

### 2D+ dynamical systems

- [Two dimensional linear systems (video)](https://www.youtube.com/watch?v=QrHRaA93Nrg)

- [Two dimensional nonlinear systems fixed points (video)](https://www.youtube.com/watch?v=9yh9DmNqdk4)

- [Bifurcations in two dimensional systems (video)](https://www.youtube.com/watch?v=oqKAVqe71vw)

- [Cornell Notes for 2D systems (Jonathan Victor)](http://www-users.med.cornell.edu/~jdvicto/jdv/mathcourse1617/mathcourse1617_Boie.pdf)

- [Introduction to Complex Systems (Dirk Brockmann)](https://rocs.hu-berlin.de/courses/complex-systems-2021/script/2-d-systems/)

## Numerical methods for ODEs and PDEs

- [Numerical Analysis 9th Ed (textbooks)](https://www.amazon.com/Numerical-Analysis-9th-Book-Only/dp/B0059JHM6M)

- [Differential equations (3Blue1Brown video playlist)](https://www.youtube.com/playlist?list=PLZHQObOWTQDNPOjrT6KVlfJuKtYTftqH6)

## Cellular automata

- [2D cellular automata demo (github repo)](https://github.com/Chakazul/Lenia) 

- [Cellular Automata Simulator](https://www.fourmilab.ch/cellab/manual/chap1.html)

## Markov chain model

- [Markov chain application: Google’s PageRank algorithm (slides)](https://www2.math.upenn.edu/~kazdan/312F12/JJ/MarkovChains/markov_google.pdf)

- [Markov Chains & PageRank](https://disco.ethz.ch/courses/fs16/ti2/lecture/chapter11.pdf)

## Discrete-event simulation and queuing models

- Notes and Papers

  - [Discrete-event simulation of queuing systems](https://phyweb.physics.nus.edu.sg/~phytaysc/articles/queue.pdf)
  
  - [Discrete-Event Simulation](https://www.cs.bu.edu/faculty/matta/Teaching/cs655-papers/shankar-des.pdf)

- Explanatory videos by MATLAB Tech Talks

  - [What Is Discrete Event Simulation](https://www.youtube.com/watch?v=21WQB0E-6-M)

  - [Why Use Discrete Event Simulation](https://www.youtube.com/watch?v=adkeGlcqBAo)

  - [Leveraging Stochastic Processes](https://www.youtube.com/watch?v=3EiniZbyeV0)

  - [In context of Operations Research](https://www.youtube.com/watch?v=YkUT3fFrjpg)
  
  - [Example of DES in digital communication systems](https://www.youtube.com/watch?v=w6SSng58DEw)

- Implementation/Code Examples

  - [Event discrete simulation with SimPy (video)](https://www.youtube.com/watch?v=Bk91DoAEcjY)

  - [Simulating a Queue (video)](https://www.youtube.com/watch?v=WEA8m3j-Jqk)
  - [Examples of using Python to write discrete-event simulations] (https://www.youtube.com/watch?v=0KvA92ykPKI) 
  - [Python code example] (https://github.com/mwong009/simulation)

## Input-output analysis

- [Textbook about control systems (book, via GitHub repo)](https://github.com/lugh56/control-and-system-book)

## Creating dynamical systems from observations

  - [An Experimentalist’s Introduction to the Observation of Dynamical Systems](https://www.worldscientific.com/doi/10.1142/9789814415729_0012)
  
  - [Introduction to Learning Dynamical Systems](https://cs.brown.edu/research/ai/dynamics/tutorial/Documents/DynamicalSystems.html)

  - [Learning Dynamical Systems from Partial Observations](https://arxiv.org/pdf/1902.11136.pdf)

  - [Learning Dynamical Systems from Data](https://www.sciencedirect.com/science/article/pii/S0167278922002500)
