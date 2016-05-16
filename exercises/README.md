## Week 0 Linear Algebra Refresher

Here's a rough outline of the topics we'll cover in lecture. This will also serve as a list of basic linear algebra topics that every data scientist should know. The MIT course is a good reference:  http://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/assignments/

### Morning:

* Vector spaces
    * Definition
    * Examples:
        * R^N
        * Functions f : R -> R
* R^N
    * Subspaces
    * Magnitude
    * Unit vectors
    * Spanning, Independence, Bases
    * Theorem: every basis contains the same number of vectors
    * Dimension
    * Dot product and formula for angle between two vectors
    * Gram-Schmidt
* Linear systems of equations
    * Reduced row echelon form

### Afternoon

* Matrices
    * From linear systems to Ax = b
    * How to multiply two matrices AB = ?
    * Linear maps
        * Representable by a matrix once you choose a basis
    * Special subspaces
        * Kernel, ker(A), Ax = 0
        * Column space, col(A), Ax
        * If A is n x m, dim col(A) + dim ker(A) = m
    * Invertible matrices
        * Question: when does Ax = b have a unique solution?
        * In practice, don't use the inverse to solve Ax = b, just row-reduce
    * Determinants
        * How to compute
        * Formula for inverse
    * Transpose
        * Definition A`
        * If the columns of A are independent, then A`A is invertible
    * QR Decomposition
        * Orthogonal matrix definition
