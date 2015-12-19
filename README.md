# Midterm II project

In this project, we numerically estimate the temperature of the phase transition of the two-dimensional ferromagnetic Ising model on a triangular lattice with nearest neighbor interactions.

We began with a code that was developed to calculate the temperature of the phase transition of a square lattice. This algorithm utilized the monte carlo integration technique know as the Metropolis Algorithm. The following are the changes implemented on the square lattice code to make it useful for a triangular lattice. 

* the total numbers of neighbors were changed from 4 to 6.

Afterwards, the program was run for a 64x64 lattice grid which produced 40 points for each energy. A graph was generated where the phase transition temperature occurs at the specific heat maximum. From the graph, we determine the the phase transition temperature of a triangular lattice to be approximately Tc = 3.6(dimensional units) 

The initial code was provided by Dr. Michael Rozman.

This project is a collaboration between myself and
* Paul Young
* Christine Caron



