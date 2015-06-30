For further information to the source code of file step-42.cc please check
tutorial step-42 of the open source library deal.II. To run the programm you
have to install deal.II as well as Trilinos and p4est. On www.dealii.org you
will find everthing you need for this purpose.

Once you have installed everthing you can start a computation by the following
command:

mpirun -np 4 step-42 filename

"filename" has to be replaced by one of the files:

default.prm                  its_symbol_halfsphere.prm           p1_global.prm
its_sphere_box.prm           its_symbol_halfsphere_transfer.prm  p2_adaptive.prm
its_sphere_box_transfer.prm  p1_adaptive.prm                     p2_global.prm.

Obviously you can modify the prm-files for your issues.
