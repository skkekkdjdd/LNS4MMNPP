# LNS4MMNPP

This repository contains the implementation of the Learning Guided Variable Neighborhood Search for the Multidimensional Multi-Way Number Partitioning Problem (MMNPP), along with test cases, experimental results, and the appendix data files of the paper in PDF format.

## Features
Implements a neighborhood search algorithm guided by learning algorithm.
Optimized for MMNPP tasks.
Written in C++ with a small percentage of C.

## Usage
To run the algorithm, use the following command:

```bash
./<executable_name> <file_in_name> <n> <m> <k>
```

### Arguments:
- `<file_in_name>`: A letter (`a`, `b`, `c`, `d`, or `e`) indicating the input data file suffix. The full input file path is determined in the `string file_in_name` variable.
- `<n>`: Number of vectors (must not exceed the file's maximum value 500).
- `<m>`: Dimensions of each vector (must not exceed the file's maximum value 20).
- `<k>`: Number of sets.

### Example:

```
./LNS e 100 20 10
```

### Requirements:
C++17 or later is required to compile the program.

## Results
The results of the algorithm's runs on benchmark instances can be found in the results directory.
