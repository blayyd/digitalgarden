---
{"dg-publish":true,"permalink":"/linear-algebra/16-determinants/16-determinants/","tags":["MOC"]}
---

# 16 Determinants
The determinant is a function that we can use to determine if an $n \times n$ square matrix $A$ is invertible by checking to see if a number is equal to zero (or not). For any $n \in \mathbb{N}$ and $A \in \mathbb{R}^{n \times n}$, we want to create a function
$$
\begin{align}
\det: R^{n \times n} \longrightarrow \mathbb{R},  & &  \begin{cases}
\det(A) \neq 0 \text{ if } A \text{ is invertible}, \\
\det(A) = 0 \text{ if } A \text{ is singular.}
\end{cases}
\end{align}
$$
In other words, we are trying to find out if our matrix is nonsingular. How do we construct such a function? If $A$ is nonsingular, then
$$
E_{t} \dots E_{2} E_{1} A = U
$$
where $E_{j}$ is an elementary matrix (and $E_{j}$ is invertible). However, a nicer looking matrix we want to get to is the [[Linear Algebra/08 Anatomy of Matrices/8.6 Identity Matrix\|8.6 Identity Matrix]].
$$
S_{12} \left( \frac{u_{12}}{u_{11}} \right) D_{n}\left( \frac{1}{u_{mn}} \right) \dots D_{1}\left( \frac{1}{u_{11}} \right) E_{t}\dots E_{1}A = \begin{bmatrix}
u_{11} & u_{12} & \dots & u_{1n} \\
0 & u_{22} & \dots & \vdots \\
\vdots & \ddots & \ddots & \vdots \\
0 & \dots & 0 & u_{mn}
\end{bmatrix}
$$
Then, we see
$$
E_{I} \dots E_{t} \dots E_{2} E_{1} A = I_{n}
$$
where $I \in \mathbb{N}$ is the number of elementary transformations required to transform $A$ into the identity matrix.
- Note: $E_{I} \dots E_{2} E_{1} = A^{-1}$
- & Also note the inverse of the above statement. All nonsingular matrices are "derived" or "constructed" or "created" by [[Linear Algebra/11 Matrix-Matrix Multiplication/11 Matrix-Matrix Multiplication\|11 Matrix-Matrix Multiplication]] of elementary matrices and the identity matrix.

---

# Notes

- [[Linear Algebra/16 Determinants/16.1 Permutation\|16.1 Permutation]]
- [[Linear Algebra/16 Determinants/16.1.1 Permutation of a Set A\|16.1.1 Permutation of a Set A]]
- [[Linear Algebra/16 Determinants/16.1.1 Permutation of a Set A\|16.1.1 Permutation of a Set A]]
- [[Linear Algebra/16 Determinants/16.2 Symmetric Groups\|16.2 Symmetric Groups]]
- [[Linear Algebra/16 Determinants/16.2.1 Inversion of a pair (i, j) with respect to pi\|16.2.1 Inversion of a pair (i, j) with respect to pi]]
- [[Linear Algebra/16 Determinants/16.2.2 Set of All Inversions for a Given pi in Sn\|16.2.2 Set of All Inversions for a Given pi in Sn]]
- [[Linear Algebra/16 Determinants/16.2.3 Sign of a Permutation\|16.2.3 Sign of a Permutation]]
- [[Linear Algebra/16 Determinants/16.2.4 Cycles\|16.2.4 Cycles]]
- [[Linear Algebra/16 Determinants/16.3 Transpositions Generate Permutations\|16.3 Transpositions Generate Permutations]]
- [[Linear Algebra/16 Determinants/16.4 Deriving the Determinant Function\|16.4 Deriving the Determinant Function]]
- [[Linear Algebra/16 Determinants/16.5 Permutation Definition of Determinant\|16.5 Permutation Definition of Determinant]]
- [[Linear Algebra/16 Determinants/16.6 Rule of Sarrus\|16.6 Rule of Sarrus]]
- [[Linear Algebra/16 Determinants/16.2.1 Inversion of a pair (i, j) with respect to pi\|16.2.1 Inversion of a pair (i, j) with respect to pi]]
- [[Linear Algebra/16 Determinants/16.2.2 Set of All Inversions for a Given pi in Sn\|16.2.2 Set of All Inversions for a Given pi in Sn]]
- [[Linear Algebra/16 Determinants/16.2.3 Sign of a Permutation\|16.2.3 Sign of a Permutation]]
- [[Linear Algebra/16 Determinants/16.2.4 Cycles\|16.2.4 Cycles]]
- [[Linear Algebra/16 Determinants/16.3 Transpositions Generate Permutations\|16.3 Transpositions Generate Permutations]]
- [[Linear Algebra/16 Determinants/16.4 Deriving the Determinant Function\|16.4 Deriving the Determinant Function]]
- [[Linear Algebra/16 Determinants/16.5 Permutation Definition of Determinant\|16.5 Permutation Definition of Determinant]]
- [[Linear Algebra/16 Determinants/16.6 Rule of Sarrus\|16.6 Rule of Sarrus]]
- [[Linear Algebra/16 Determinants/16.7 Properties of Determinants\|16.7 Properties of Determinants]]

