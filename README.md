# Choreographic-Orbit-Minimizer
A collection of minimisers and numerical integrators developed to investigate choreographic orbits (where particles trajectories display spatial and temporal symmetries) in the Newtonian n-body problem. Full results and methodology are detailed in the accompanying report, 'Numerical Methods in the n-Body Problem'.

## Aim
To benchmark numerical integrators for dynamical systems evolving under Newtonian gravity, and to produce a functional minimisation algorithm that deforms an initial closed curve into a choreographic orbit permitted by Newtonian gravity. 

## Contents
The **Minimiser** implements the functional minimisation algorithm for within the D_2' symmetry group to produce a figure-8 orbit from a given initial curve.
The **Integrators** are a set of symplectic numerical integrators (Euler-Cromer, Leapfrog, Yoshida) I developed, plus a Runge-Kutta 4 method used as a benchmark.

## Report
'Numerical Methods in the n-Body Problem' (included in this repository) covers the motivation, development, and results of the minimiser in full.

## To Run Code
The minimiser content is self contained within the minimiser file, the integrators are separated out and will integrate a given set of initial conditions with the scheme given in the file name.
