---
{"dg-publish":true,"permalink":"/linear-algebra/00-major-problems-in-applied-linear-algebra/2-a-the-nonsingular-linear-systems-problem/","tags":["Topic/Linear_Algebra","Type/Definition"]}
---

Types: *N/A*
Examples: *N/A*
Constructions: [[Linear Algebra/00 Major Problems in Applied Linear Algebra/2B The General Linear-Systems Problem\|2B The General Linear-Systems Problem]]
Generalizations: [[Linear Algebra/00 Major Problems in Applied Linear Algebra/1 The Matrix-Vector Multiplication Problem\|1 The Matrix-Vector Multiplication Problem]]

Properties: *N/A*
Sufficiencies: *N/A*
Questions: *N/A*

> [!question] Problem 2A: The Nonsingular Linear-Systems Problem
> 
> Let $n \in \mathbb{N}$. Let $A \in \mathbb{R}^{n \times n}$ be a "given" nonsingular matrix and $\vec{b} \in \mathbb{R}^n$ be a given vector. Then, the nonsingular linear-systems problem is to find an unknown vector $\textcolor{red}{\vec{x}} \in \mathbb{R}^{n}$ such that
> $$
> [A]_{n \times n} \cdot \textcolor{red}{[\vec{x}]_{n \times 1}} = [\vec{b}]_{n \times 1}
> $$

*Claim.* The NLSP is known as a "backward problem". Let $f: \mathbb{R}^{n}\to \mathbb{R}^{n}$ be defined as
$$
f(\vec{x}) = A \cdot \vec{x}
$$
- The input, $\vec{x}$ is unknown and desired.
- The output $\vec{b}$ is known.

Because we begin in the range and work our way towards the domain, we call this a backward problem. 

> [!remark|*]
> We will see that nonsingular matrices are very special (perhaps we might say they are what applied linear algebraists dream about: they are very beautiful):
> $$\text{Rng}(f) = \text{codomain}(f)$$

---
# Relation with [[Linear Algebra/00 Major Problems in Applied Linear Algebra/1 The Matrix-Vector Multiplication Problem\|1 The Matrix-Vector Multiplication Problem]]
A major similarity between matrix-vector multiplication and the nonsingular linear systems problem is that both depend on matrix-vector multiplication. The process of solving the former problem is simply to calculate a product. To solve the later problem, we “reverse engineer” our matrix-vector product in order to find input vectors that produce a given output. However, both problems involve the same underlying matrix-vector multiplication function.
$$
f(\vec{x}) = A \cdot \vec{x}
$$
One of the major difference between the two problems is in the assumptions of matrix $A$. For general matrix-vector products, we only need to create a rectangular $m \times n$ matrix, where $m$ may not be equal to $n$. However, for the NLSP, we need to create a matrix with the same number of rows as columns and this matrix must have a very special columns structure.