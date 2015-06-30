Example code for elastoplatic contact problems

This code is accompanying the paper

J. Frohne, T. Heister, W. Bangerth
Efficient numerical methods for the large-scale, parallel solution of elastoplastic contact problems
-- Accepted for publication in International Journal for Numerical Methods in Engineering

For further information to the source code please check the tutorial step-42
of the open source library deal.II. To run the program you have to install
deal.II as well as Trilinos and p4est.

Once you have installed everthing you can start a computation with the following
command:

mpirun -n 4 ./step-42 filename.prm

"filename.prm" has to be replaced by one of the .prm files.
