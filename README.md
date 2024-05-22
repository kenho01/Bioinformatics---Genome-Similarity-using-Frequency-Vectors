# Leveraging Parallel Computing to Compare Genome Similarity Using Frequency Vectors

This repository demonstrates the comparison of performance between sequential and parallel execution to identify correlations between the genomes of 40 bacteria using C++. The parts of the sequential code that can be parallelized have been identified, and OpenMP is used to perform these computations in parallel.

## Instructions to Run the Program

1. **Open the Solution:**
   - Launch `CAB401_Assignment2.sln` in your preferred IDE.

2. **Run the Sequential Version:**
   - Replace the current code in `CAB401_Assignment2.sln` with the content from `Assignment2_SequentialCode.cpp`.

3. **Run the Parallel Version:**
   - Replace the current code in `CAB401_Assignment2.sln` with the content from `Assignment2_ParallelCode.cpp`.

4. **Compare Results for Different k-mers:**
   - To compare results using k-mers of different lengths (from 3-mers to 6-mers), change the value of `#define LEN` in the code to the desired length.
