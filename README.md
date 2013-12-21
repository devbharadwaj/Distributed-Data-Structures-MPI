README

*	This project is about creating distributed hash tables with MPI
*	And parallel B-Trees with OpenMP

To run MPI code:

$mpiicc Bigtable.c -o Bigtable
$mpirun -np 32 ./Bigtable

To run OpenMP code:

$icc -openmp B-Tree.c -o B-Tree
$./B-Tree

