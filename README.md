# DP Line Fitting Algorithm - Line Fitting using Dynamic Programming

This repository contains a C++ code file that implements the DP Line Fitting Algorithm for finding the best-fitting line through a set of points.

## Line Fitting using Dynamic Programming

The `Q2.cpp` file in this repository implements the DP Line Fitting Algorithm. This algorithm aims to find the best-fitting line that minimizes the sum of squared errors between the line and a set of given points.

### Explanation

The `Q2.cpp` code performs the following steps:

1. Input the number of points and the coordinates of each point.
2. Sort the points based on their x-coordinates in ascending order.
3. Initialize an array `dp` to store the minimum sum of squared errors up to the current point.
4. Iterate through each point and compute the error for all possible lines formed with previous points.
5. Update the `dp` array with the minimum error.
6. The last element of the `dp` array will contain the minimum sum of squared errors for the best-fitting line.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/mrdetective007/DP_Line_Fitting_Algorithm.git
```

2. Navigate to the `Line_Fitting` directory:

```bash
cd DP_Line_Fitting_Algorithm/Line_Fitting
```

3. Compile and run the C++ code:

```bash
g++ Q2.cpp -o line_fitting
./line_fitting
```

4. Follow the instructions in the code to input the number of points and their coordinates. The code will output the coefficients of the best-fitting line.

## Conclusion

The DP Line Fitting Algorithm implemented in `Q2.cpp` is a dynamic programming approach to find the best-fitting line through a set of points. By minimizing the sum of squared errors, the algorithm provides a robust line that represents the data distribution.
