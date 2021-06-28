---
title: 'Universal Compiling and (No-)Free-Lunch Theorems for Continuous Variable Quantum Learning'
date: 2021-05-03
permalink: /posts/2021/05/03/Sornborger/
tags:
  - CV QC
  - NFL theorem
  - Quantum Compiling
  - Fock states
  - Squeezed states
---

Summary: 

* Paper suggests short-depth continuous variable algorithms for quantum compilation. Experiements with arbitrary Gaussian operations and Kerr non-linearities are done to show learnability. Theoretical claims for quantum learning theory in the continuous variable setting are made (for the first time). They claim advantages in 
sample complexity when using quantum states of light. 

Details:

* variational compilation of parametrized CV unitaries involves optimization of a parameterized quantum circuit to learn a given target unitary. This can be used in error correciton, tomography, sensing or circuit design. 

* Does using entangles states lead to a "Free lunch?" (that we can learn any unitary with reasonable resources)

* The goal of CV quantum compiling is to take a (possibly
unknown) unitary U and return a gate sequence V ,
executable on a CV quantum computer, that has approximately
the same action as U on any given input state
(up to possibly a global phase factor)

* Hilbert Schmidt inner product is used to find the unitary that estimates the target unitary upto a global phase. This can be related to average gate fidelities (which otherwise needs measurements over all pure states derived from the Haar measure which increases exponentially). 

* DV systems use Bell states to measure HS cost. For Cv systems, Two-Mode-Squeezed States (TMSS) are a natural analogue of Bell states. The layout of CV circuits that can measure this distance are proposed. If coherent states are used, since they are easier to produce experimentally, a truncation of energy can be used whilst obtaining the HS cost. 

* what about barren plateaus as CV systems scale? yes, they do see them. Hence a local 2-mode meausremnt based cost function is proposed like in ref 14 for the DV training. However, gradients still vanish as the squeezing is increased. When using coherent states, this problems is avoided by increasing the energy truncation with number of modes. 

* Numrical tests are done for arbitrary single-mode Gaussian operations, Kerr non-linearities and a general beamsplitter operation.

Recap:
* CV QO

Important refs:
10, 14, 15, 51
