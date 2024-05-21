# CSE-224 Numerical Analysis Lab

Welcome to the CSE-224 Numerical Analysis Lab repository. This repository contains Jupyter notebooks for various numerical methods used in solving mathematical problems. Each lab focuses on a different method and provides a detailed explanation, implementation, and examples.

## Lab Contents

### 1. Lab 1: Bisection Method
**File:** `Lab01_Bisection.ipynb`  
**Description:**  
This lab introduces the Bisection Method for finding the roots of a polynomial equation. The notebook guides you through creating a user-defined function `bisection_method(f, xl, xu, epsilon)` that returns the root of the equation or an approximate value with an absolute relative approximate error of at most epsilon. 

**Tasks:**
- Implement the Bisection Method function.
- Test the function to ensure it works correctly.
- Generate a plot of **iteration vs relative approx error (%)** for the implemented Bisection Method.

### 2. Lab 2: Newton-Raphson and Secant Methods
**File:** `Lab02_Newton_Raphson_And_Secant.ipynb`  
**Description:**  
This lab covers the Newton-Raphson and Secant Methods for finding roots. It includes a function `func(f, x)` to evaluate the value of the polynomial at a given point and guides you through implementing the Newton-Raphson method.

**Tasks:**
- Implement the Newton-Raphson Method.
- Implement the Secant Method.
- Test the functions with various polynomial equations to validate their correctness.

### 3. Lab 3: False Position Method
**File:** `Lab03_False_Position_Question.ipynb`  
**Description:**  
In this lab, you will learn about the False Position Method for finding roots. The notebook provides detailed steps for creating a function `falseposition(f, xl, xu, epsilon)` that returns the root or an approximate value with an absolute relative approximate error of at most epsilon.

**Tasks:**
- Implement the False Position Method function.
- Write a script to test the function and verify its accuracy.
- Handle polynomials of any size.

### 4. Lab 4: Lagrangian Interpolation
**File:** `Lab04_Lagrangian.ipynb`  
**Description:**  
This lab focuses on Lagrangian Interpolation, a method for constructing a polynomial that passes through a given set of points. The notebook provides theoretical background and practical examples of Lagrangian Interpolation.

**Tasks:**
- Implement the Lagrangian Interpolation method.
- Test the implementation with different sets of data points.
- Generate plots to visualize the interpolated polynomial and the given data points.

## Getting Started

To get started with these notebooks, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/CSE-224-Numerical-Analysis-Lab.git
    ```
2. Navigate to the repository directory:
    ```bash
    cd CSE-224-Numerical-Analysis-Lab
    ```
3. Open the Jupyter notebooks using Jupyter Lab or Jupyter Notebook:
    ```bash
    jupyter lab
    # or
    jupyter notebook
    ```
4. Explore each notebook and follow the instructions provided to complete the tasks.

## Requirements

Make sure you have the following installed on your system:
- Python 3.x
- Jupyter Lab or Jupyter Notebook
- numpy
- matplotlib

You can install the necessary packages using pip:
```bash
pip install numpy matplotlib
