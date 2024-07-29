# Braid groups and Baxter polynomials

This repository contains the LaTeX source files for my MSc thesis, which I defended in July 2024 at the University of Saskatchewan.

## Abstract

It is well known that the braid group of a simple Lie algebra acts on its integrable representations via products of exponentials of its Chevalley generators.
In particular, the Yangian is an integrable representation, so there is an action of the braid group on this space.
We show that modifying this action induces an action of the braid group on a certain commutative subalgebra of the Yangian by Hopf algebra automorphisms.
By dualizing this modified action, we recover an action of the braid group on tuples of rational functions defined in the work of Y. Tan.
Using this dual action, we prove a conjecture of S. Gautam and C. Wendlandt that the two sufficient conditions for the tensor product of finite-dimensional representations of the Yangian to be cyclic are identical.
One of these conditions involves the aforementioned action of the braid group on rational functions, and the other involves roots of the Baxter polynomials, which have many interesting properties and ties to mathematical physics.


## Building

Install a TeX distribution such as MiKTeX.
Clone the full repository using the following command:

```
git clone https://github.com/noahfriesen/msc-thesis.git
```
then compile the document by calling `latexmk` from the root directory.
