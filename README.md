Inside the .zip you'll find the Quicksort exported and an User Manual on Spanish but here's the translation to English 

# Quick-Sort

# USER MANUAL - QUICKSORT GENERATOR AND SORTER

EXECUTION INSTRUCTIONS
1. Compile the file: javac QuickSortGenerator.java
2. Execute the program: java QuickSortGenerator

USAGE INSTRUCTIONS

When running the program, the following welcome screen will appear:

=== QUICKSORT GENERATOR AND SORTER ===
Generates random numbers between 1 and 100

Enter the array length (1-1000000):

MAIN OPERATION: GENERATION AND SORTING

Function: Generates an array of random integers and sorts them using the optimized QuickSort algorithm.

Steps:

1. Enter the desired array size (between 1 and 1,000,000 elements)
2. The system automatically generates random numbers between 1 and 100
3. The original array is displayed with statistics
4. The QuickSort algorithm is executed with performance measurement
5. The sorted array is displayed with correctness verification

Example with small array (10 elements):

Enter the array length (1-1000000): 10
Generating array of 10 elements...

ORIGINAL ARRAY
Elements: [45, 23, 78, 12, 67, 34, 89, 56, 91, 28]
Statistics: Size=10, Min=12, Max=91, Average=52.30

Executing QuickSort...

SORTED ARRAY
Elements: [12, 23, 28, 34, 45, 56, 67, 78, 89, 91]
Statistics: Size=10, Min=12, Max=91, Average=52.30

PERFORMANCE STATISTICS
Execution time: 0.245 ms
Approximate memory: 1024 bytes
Processed elements: 10
Time per element: 0.024500 ms
Theoretical complexity: 33 operations

VERIFICATION: Array correctly sorted

Example with large array (1000 elements):

Enter the array length (1-1000000): 1000
Generating array of 1000 elements...

ORIGINAL ARRAY
Sample: [67, 23, 89, 45, 12, 78, 34, 91, 56, 28, ..., 43, 87, 19, 65, 92, 31, 74, 48, 83, 26]
(Showing first 10 and last 10 elements of 1000 total)
Statistics: Size=1000, Min=1, Max=100, Average=50.74

Executing QuickSort...

SORTED ARRAY
Sample: [1, 1, 1, 2, 2, 3, 3, 3, 4, 4, ..., 97, 98, 98, 99, 99, 100, 100, 100, 100, 100]
(Showing first 10 and last 10 elements of 1000 total)
Statistics: Size=1000, Min=1, Max=100, Average=50.74

PERFORMANCE STATISTICS
Execution time: 2.847 ms
Approximate memory: 8192 bytes
Processed elements: 1000
Time per element: 0.002847 ms
Theoretical complexity: 9990 operations

VERIFICATION: Array correctly sorted
