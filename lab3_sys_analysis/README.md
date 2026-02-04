# Lab 3: Matrix Operations in System Analysis

## 🎯 Purpose
To gain practical experience with core matrix operations essential for system analysis, including multiplication, inversion, spectral analysis, and matrix functions.

## 🛠 Execution Steps

### 1. Arithmetic Operations
* **Matrix Multiplication:** Performed multiplication for various matrix pairs ($C1 \cdot B1, B1 \cdot C1, A1 \cdot B1, A1 \cdot A2$). Verified that matrix multiplication is not commutative.
* **Matrix Inversion:** Calculated the inverse matrix $A1^{-1}$ using the `inv()` function.

### 2. Spectral Analysis
* Calculated the **eigenvalues** and **eigenvectors** of matrix $A1$ using the `eig()` command. This is a crucial step for analyzing system stability.

### 3. Matrix Exponential
* Computed the matrix function $e^{A1 \cdot t}$ using `expm()`. 
* Applied symbolic math (`syms t`) to obtain the analytical expression for the transition matrix.

## 📊 Results
The calculations were performed in MATLAB. The results illustrate the properties of square matrices (2x2) and their transformations.

**Key Technical Outcomes:**
* Matrix Inversion: `inv(A1)`
* Eigenvalues Calculation: `[V, D] = eig(A1)`
* Matrix Exponential: `expm(A1 * t)`

Detailed logs and symbolic outputs are documented in the `solution.m` file.