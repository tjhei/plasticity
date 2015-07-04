The codes in this directory accompany the paper
   J. Frohne, T. Heister, W. Bangerth
   "Efficient numerical methods for the large-scale, parallel solution
    of elastoplastic contact problems"
   International Journal for Numerical Methods in Engineering, 2015

The source code is contained in the step-42.cc file and is a variation
of the step-42 tutorial program of the open source library deal.II,
see http://www.dealii.org/ . The step-42 tutorial program is, in
essence, an extensively documented version of the program in this
directory, but it has been streamlined slightly for educational
purposes.

To run the program you have to:
- Install deal.II as well as Trilinos and p4est. The deal.II
  installation instructions at http://www.dealii.org/ provide
  extensive documentation on how to do this.
- Run cmake to configure the current directory, using the command line
    cmake -DDEAL_II_DIR=/path/to/dealii .
  where /path/to/dealii is a path to an installed version of deal.II
- Compile the step-42.cc file into an executable using the command
    make
- Run the executable using a command line such as
    mpirun -n 4 ./step-42 filename.prm
  Here, "filename.prm" has to be replaced by one of the .prm files in
  this directory. Obviously, you can also use fewer or more than the 4
  processors selected above -- some of the computations in the paper
  in fact use more than 1,000.

There are a number of input files (*.prm) in this directory that
correspond to the various computations shown in the paper.
