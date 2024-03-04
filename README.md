# Learnability of Linear Port-Hamiltonian Systems
This repository stores the implementation of the paper "Learnability of Linear Port-Hamiltonian Systems", which has been accepted for publication in the Journal of Machine Learning Research (2024). 

# Abstract
A complete structure-preserving learning scheme for single-input/single-output (SISO) linear port-Hamiltonian systems is proposed. The construction is based on the solution, when possible, of the unique identification problem for these systems, in ways that reveal fundamental relationships between classical notions in control theory and crucial properties in the machine learning context, like structure-preservation and expressive power. In the canonical case, it is shown that, up to initializations, the set of uniquely identified systems can be explicitly characterized as a smooth manifold endowed with global Euclidean coordinates, which allows concluding that the parameter complexity necessary for the replication of the dynamics is only O(n) and not O(n2), as suggested by the standard parametrization of these systems. Furthermore, it is shown that linear port-Hamiltonian systems can be learned while remaining agnostic about the dimension of the underlying data-generating system. Numerical experiments show that this methodology can be used to efficiently estimate linear port-Hamiltonian systems out of input-output realizations, making the contributions in this paper the first example of a structure-preserving machine learning paradigm for linear port-Hamiltonian systems based on explicit representations of this model category.

# Key words
Linear port-Hamiltonian system, machine learning, structure-preserving algorithm, systems theory, physics-informed machine learning, unique identification problem, controllable representation, observable representation, canonical representation.

# Implementation
Our implementation is based on the deep learning engine Pytorch. Note that CUDA is needed for execution!
