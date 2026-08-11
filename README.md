# Computational Mathematics & Numerical Analysis

Welcome to my portfolio of scientific computing and numerical analysis projects. This repository serves as a comprehensive archive of core algorithms, linear algebra transformations, and optimization models developed during my computational mathematics coursework. 

## Repository Overview & Navigation

To ensure complete academic and computational transparency, all projects in this repository are formatted as **Literate Programming Reports written and executed in Wolfram Language (Mathematica v14.3)**. Rather than separating theoretical proofs from application, **every formal PDF report contains the complete, executable Mathematica source code, algorithmic logic, and custom data visualizations embedded directly alongside the mathematical derivations.** 

You can navigate the specific computational analyses and their associated Mathematica code via the direct links below:

* [📄 The Research Poster "Compressing Complexity: How PCA and NCA Uncover Hidden Structure"](./The%20Research%20Poster%20Compressing%20Complexity.pdf)
  * **Description:** A comprehensive comparative analysis evaluating Principal Component Analysis versus Neighborhood Components Analysis for high-dimensional feature space compression. Includes full Mathematica algorithms for covariance matrix factorization, singular value decomposition, and classification scoring.
  * **Core Concepts:** Matrix Factorization, Spectral Theorem, Principal Component Analysis (PCA), Neighborhood Components Analysis (NCA).
  * **Impact & Code Execution:** Custom Mathematica scripts achieved a 98% classification accuracy on high-dimensional test datasets.

* [📄 Gradient Descent vs. Newton's Method.pdf](./Gradient%20Descent%20vs.%20Newton's%20Method.pdf)
  * **Description:** A deep dive into numerical optimization performance in 2D space. The embedded Mathematica code constructs custom iterative solvers to compare first-order Gradient Descent against second-order Newton's Method, benchmarking step sizes, line search strategies, and convergence trajectories near minimums.
  * **Core Concepts:** Multi-variable Gradient Descent, Second-Order Hessian Matrices, Newton-Raphson Optimization, Convergence Rates, Hessian Curvature Analysis.
  * **Code Implementation:** Fully algorithmic Mathematica script calculating symbolic gradient vectors and numerical inversion of $2 \times 2$ Hessian matrices.

* [📄 Least Squares Curve Fitting.pdf](./Least%20Squares%20Curve%20Fitting.pdf)
  * **Description:** An investigation into optimal parameter estimation for overdetermined system models. The report details both the calculus derivations and the complete Mathematica pipeline used to compute linear and quadratic regression models over noisy observational data.
  * **Core Concepts:** Overdetermined Linear Systems, Residual Sum of Squares (RSS) Minimization, Matrix Transposition Solvers, Linear & Quadratic Fitting.
  * **Code Implementation:** Programmed in Mathematica to evaluate normal equations $(A^T A)^{-1} A^T b$ directly and render comparative error residuals.

* [📄 Polynomial Interpolation & Cubic Splines.pdf](./Polynomial%20Interpolation%20%26%20Cubic%20Splines.pdf)
  * **Description:** A study on continuous curve approximation contrasting global high-degree polynomial interpolation against piecewise natural cubic splines. Highlights the resolution of Runge's phenomenon through localized piecewise smooth approximations.
  * **Core Concepts:** Runge's Phenomenon, Vandermonde Systems, Lagrange Polynomials, Tridiagonal Matrix Systems, Piecewise Natural Cubic Splines.
  * **Code Implementation:** Complete Mathematica routines that construct and solve tridiagonal linear systems for second-derivative continuity boundary conditions.

***

## Technical Stack & Software Architecture

* **Primary Computational Engine:** Wolfram Language (Mathematica v14.3)
* **Core Methodologies:** Numerical Linear Algebra, Hessian-Driven Optimization, Piecewise Spline Interpolation, Least Squares Optimization, and Spectral Feature Reduction.

Each PDF document provides an exhaustive, end-to-end breakdown featuring theoretical derivations, step-by-step Mathematica script execution blocks, and high-resolution vector plots generated directly by the underlying code.
