# Sorting Algorithms Performance Analysis

## Overview

This project implements and evaluates the performance of various sorting algorithms. The goal is to compare their efficiency in terms of CPU time and the number of comparisons made during the sorting process.

## Implemented Sorting Algorithms

1. **Bubble Sort**
2. **Insertion Sort**
3. **Selection Sort**
4. **Shell Sort**
5. **Merge Sort**
6. **Quick Sort**
7. **IQuick Sort** (Quick Sort with Insertion Sort for small sub-vectors)
8. **Priority Queue Sort** (Heap Sort)

## Features

- **Sorting Algorithms**: Eight different sorting algorithms are implemented to study their performance.
- **Performance Measurement**: Each sorting algorithm returns statistics including the number of comparisons and CPU time taken.
- **Helper Functions**:
  - `is_sorted(v)`: Checks if the vector `v` is sorted.
  - `rand_vec(size, min, max)`: Generates a vector of random integers of specified size and range.

## Files

- `a4_sort_implementations.h`: Contains the implementations of all the sorting algorithms.
- `a4.xlsx`: Excel file containing the experimental data and visualizations.

## Getting Started

### Prerequisites

- C++17 compiler
- Makefile
- Excel or Google Sheets (for viewing the results)

### Compilation and Execution

1. Ensure you have `a4_base.h` and `a4_sort_implementations.h` in the same directory.
2. Compile the test program using the provided makefile command:
   ```bash
   make test_sorts
3. Run the test executable
   ```bash
   ./test_sorts
