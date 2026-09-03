# Choreographic-Orbit-Minimizer

A collection of minimizers and numerical integrators developed to investigate 
choreographic orbits in the Newtonian n-body problem. Full results and 
methodology are detailed in the accompanying report, *Numerical Methods in 
the n-Body Problem*.

## Aim

Produce a functional minimisation algorithm that deforms an initial closed 
curve into a choreographic orbit — one exhibiting both spatial and temporal 
symmetry — permitted by Newtonian gravity.

## Contents

- **Minimizer** — implements the algorithm for the D₂' symmetry group (the 
  figure-8 orbit).
- **Integrators** — a set of symplectic numerical integrators, plus a 
  Runge-Kutta 4 method used as a benchmark.

## Report

`Numerical Methods in the n-Body Problem` (included in this repository) 
covers the motivation, development, and results of the minimizer in full.
