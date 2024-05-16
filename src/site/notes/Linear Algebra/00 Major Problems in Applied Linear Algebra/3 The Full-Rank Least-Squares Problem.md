---
{"date created":"Monday, April 1st 2024, 9:30:09 pm","date modified":"Wednesday, April 3rd 2024, 8:10:55 pm","time spent":"25 min","tags":null,"links":"[[00 Major Problems in Applied Linear Algebra]]","dg-publish":true,"permalink":"/linear-algebra/00-major-problems-in-applied-linear-algebra/3-the-full-rank-least-squares-problem/","dgPassFrontmatter":true}
---

Types: *N/A*
Examples: *N/A*
Constructions: [[Calculus 3/01 Vectors in 2D/1.4 Two Norms in 2D\|1.4 Two Norms in 2D]]
Generalizations: *N/A*

Properties: *N/A*
Sufficiencies: *N/A*
Questions: *N/A*

> [!question] The Full-Rank Least-Squares Problem
> Let $m$, $n \in \mathbb{N}$ with $m \geq n$. Let $A \in \mathbb{R}^{m \times n}$ be a "given" full-rank matrix and $\vec{b} \in R^{m}$ be a given vector. Then, the **full-rank least-squares problem** is to find all $\textcolor{red}{\vec{x}} \in \mathbb{R}^{n}$ to minimize the [[Calculus 3/01 Vectors in 2D/1.4 Two Norms in 2D\|2-norm]] of the residual vector:
> $$
> \lvert \lvert A \cdot \textcolor{red}{\vec{x}} - \vec{b} \rvert  \rvert _{2}
> $$

Just like the [[Linear Algebra/00 Major Problems in Applied Linear Algebra/1 The Matrix-Vector Multiplication Problem\|1 The Matrix-Vector Multiplication Problem]] and the [[Linear Algebra/00 Major Problems in Applied Linear Algebra/2A The Nonsingular Linear-Systems Problem\|2A The Nonsingular Linear-Systems Problem]], we can describe the **full-rank least-squares problem** using the function $f:\mathbb{R}^{n}\to R^{m}$ with
$$
f(\vec{x}) = A \cdot \vec{x} = \sum_{k=1}^{n} x_{k}A(:,k)
$$
Based on this definition, we have:
- the domain of $f$ is $\mathbb{R}^n$
- the codomain of $f$ is $\mathbb{R}^{m}$
- the range of $f$ is a subset of $\mathbb{R}^{m}$ and most likely not equal to $\mathbb{R}^{m}$

The **full-rank least-squares problem** is a backward problem because we start with the function description (defined my matrix $A$) and we are given one specific output value $\vec{b}$ in the CODOMAIN of $f(\vec{x})$. We are trying to find all possible input values $\textcolor{red}{\vec{x}}$ in the domain that produce output value $f(\textcolor{red}{\vec{x}})$ "as close as possible" to the vector $\vec{b}$. 

---
Using the definition of the least-squares problem, we can classify all [[Linear Algebra/00 Major Problems in Applied Linear Algebra/2A The Nonsingular Linear-Systems Problem\|2A The Nonsingular Linear-Systems Problem]] as least-squares problems. For linear systems problems, since $\vec{b}$ begins in the range of $f(\vec{x})$, we know that
$$
\min_{\textcolor{red}{\vec{x}} \in \mathbb{R}^{n}} \lvert \lvert \vec{b} - A\textcolor{red}{\vec{x}} \rvert  \rvert_{2} = 0 
$$
for each solution. *However, not all least-squares problems are linear systems problems.* If $\vec{b} \in \mathbb{R}^{m}$ with $b \not\in \text{Rng}(f)$, we know that $f(\vec{x}) \neq \vec{b}$ for all $\vec{x} \in \mathbb{R}^{n}$. This is the focus of the least-squares problem. Thus, the least-squares problem is a generalization of the linear systems problem that allows us to create "best-fit" approximations to noisy data.