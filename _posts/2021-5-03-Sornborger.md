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

* Sucessful numrical tests are done for arbitrary single-mode Gaussian operations, Kerr non-linearities and a general beamsplitter operation.

* for finite-dimensional quantum circuit learning, target function f corresponds to a unitary quantum channel U and the
training set is generalized to a set of quantum state pairs {psi, Upsi}. By defining the generalization error
using a suitable distance on quantum state space, it has been shown that in general an exponential number of training states,|S|~ 2^n , are required to learn an n qubit unitary. 

* an entanglement-enhanced quantum No-Free-Lunch theorem implies that the lower bound of the expected error of a quantum learning algorithm, over all target unitaries U is reduced linearly in r (schmidt rank of entangles pure states used as input). Hence, the number of input-output state pairs needed to
learn a target unitary, U, may be exponentially reduced. (is this different from how Srinivisan uses NFL theorem? classical training data - coherent
states - and quantum training data - entangled coherent-Fock states)

Recap:
* CV QO

Important refs:
10, 14, 15, 51, 53, 54, 59
