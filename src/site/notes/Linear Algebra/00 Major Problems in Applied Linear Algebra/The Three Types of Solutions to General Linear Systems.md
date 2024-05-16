---
{"date created":"Monday, April 1st 2024, 10:32:48 pm","date modified":"Thursday, April 18th 2024, 8:01:05 pm","time spent":"16 min","tags":["Type/Proposition","Topic/Linear_Algebra"],"links":"[[00 Major Problems in Applied Linear Algebra]]","dg-publish":true,"permalink":"/linear-algebra/00-major-problems-in-applied-linear-algebra/the-three-types-of-solutions-to-general-linear-systems/","dgPassFrontmatter":true}
---

Types: *N/A*
Examples: [[Linear Algebra/00 Major Problems in Applied Linear Algebra/What do quadratic equations teach us about general linear systems\|What do quadratic equations teach us about general linear systems]]?
Constructions: *N/A*
Generalizations: [[Linear Algebra/00 Major Problems in Applied Linear Algebra/2B The General Linear-Systems Problem\|2B The General Linear-Systems Problem]]

Properties: *N/A*
Sufficiencies: *N/A*
Questions: *N/A*

> [!proposition] The Three Types of Solutions to General Linear Systems
> In [[Linear Algebra/00 Major Problems in Applied Linear Algebra/2B The General Linear-Systems Problem\|2B The General Linear-Systems Problem]], we will see we have three options for solution type.
> 1. **Unique solution**: Given $\vec{b} \in \text{Rng}(f)$ and $A$ must be ==full-rank==[^1] (full column rank).
> 2. **Nonunique solution**: Given $\vec{b} \in \text{Rng}(f)$ and $A$ rank deficient (aka $A$ is not full rank & not ==one-to-one==).
> 3. **No solution:** Given $\vec{b} \in \text{Codomain}(f)=\mathbb{R}^{m}$ but $\vec{b} \not\in \text{Rng}(f)$. In this case, the GLSP has no solution but we can think about minimizing the distance between $\text{Rng}(f)$ and given $\vec{b}$.  
> 	- Problem 4: [[Linear Algebra/00 Major Problems in Applied Linear Algebra/3 The Full-Rank Least-Squares Problem\|3 The Full-Rank Least-Squares Problem]]
> 	- Problem 6: RDLSP

[^1]: Rectangular but the same properties of nonsingular whole. You can imagine full-rank as the generalization of nonsingular.