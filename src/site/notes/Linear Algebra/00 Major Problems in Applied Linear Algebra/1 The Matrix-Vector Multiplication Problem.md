---
{"date created":"Monday, April 1st 2024, 2:05:58 pm","date modified":"Friday, April 26th 2024, 5:12:34 pm","time spent":"21 min","tags":["Topic/Linear_Algebra","Type/Definition"],"links":"[[00 Major Problems in Applied Linear Algebra]]","lesson":null,"dg-publish":true,"mathlink":null,"permalink":"/linear-algebra/00-major-problems-in-applied-linear-algebra/1-the-matrix-vector-multiplication-problem/","dgPassFrontmatter":true}
---

Types: *N/A*
Examples: *N/A*
Constructions: *N/A*
Generalizations: [[Linear Algebra/00 Major Problems in Applied Linear Algebra/2A The Nonsingular Linear-Systems Problem\|2A The Nonsingular Linear-Systems Problem]]

Properties: *N/A*
Sufficiencies: *N/A*
Questions: *N/A*

> [!definition|*] Problem 1: The Matrix-Vector Multiplication Problem
> Let $m,n \in \mathbb{N}$. Let $A \in \mathbb{R}^{m \times n}$ be a given matrix and $x \in \mathbb{R}^{n}$ be a given vector. Then the matrix-vector multiplication problem is to find an unknown vector $b \in R^{m}$ such that
> $$A \cdot \vec{x} = \color{RED} \vec{b}$$

$$
[A]_{\underset{ rows }{ m } \times \underset{ columns }{ n }} \cdot [x]_{n \times 1} = \color{RED} [b]_{m \times 1}
$$
When doing matrix-vector multiplication, the inner dimensions must agree! This is a "forward problem." Let's define the function
$$
f:\underbrace{ \mathbb{R}^{n} }_{ \text{domain} }\to \underbrace{ \mathbb{R}^{m} }_{ \text{codomain} }
$$
given by
$$
f(\vec{x}) = A \cdot \vec{x}.
$$
The range of $f$ is contained in $\mathbb{R}^{m}$ but may not be equal to $\mathbb{R}^{m}$ depending on the entries in the columns of matrix $A$. 