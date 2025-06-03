# MPI Collective Communication – Part 1

## Overview

This project demonstrates the use of **MPI collective communication operations** in a parallel C++ program using the MPI library. It simulates a simple distributed computation where an array of integers is processed in parallel by multiple processes. The objective is to gain hands-on experience with core collective operations in MPI such as:

- `MPI_Scatter`
- `MPI_Gather`
- `MPI_Bcast`
- `MPI_Reduce`

---

## How to Compile

To compile the MPI program, use the following command in a terminal:

```bash
mpic++ -o mpi_collective mpi_collective.cpp
```
## How to run

To run the compiled MPI program, use the followinh command in a terminal:

```bash
mpirun -np 4 ./mpi_collective
mpirun -np 8 ./mpi_collective
```
