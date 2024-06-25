---
{"dg-publish":true,"permalink":"/linear-algebra/17-general-linear-systems/17-general-linear-systems/","tags":["MOC"]}
---

# 17 General Linear-Systems
Recall the [[Linear Algebra/12 Nonsingular Linear Systems/12.1 The Square Linear-Systems Problem#^2987f6\|NLSP]].
$$
A \cdot \textcolor{red}{\vec{x}} = \vec{b}
$$
where $A \in \mathbb{R}^{n \times n}$ and $\vec{b} \in \mathbb{R}^{n}$ are known. We transformed this into
$$
U \cdot \textcolor{red}{\vec{x}} = \vec{y}
$$
where $U \in \mathbb{R}^{n \times n}$ is an [[Linear Algebra/08 Anatomy of Matrices/8.9 Upper-Triangular Matrix\|8.9 Upper-Triangular Matrix]] with nonzero diagonal elements. We accomplished this through multiplying both sides by a sequence of $t \in \mathbb{N}$ elementary matrices
$$
\begin{align}
U = E_{t} \cdots E_{2} \cdot E_{1} \cdot A, &  & \vec{y}=E_{t} \cdots E_{2} \cdot E_{1} \cdot \vec{b}
\end{align}
$$
To find our final solution, we applied [[Linear Algebra/12 Nonsingular Linear Systems/12.2 Backwards Substitution\|12.2 Backwards Substitution]] to solve the resulting linear system. However, this algorithm only works well for regular coefficient matrices. For more general linear systems, we will develop a general Gaussian Elimination algorithm that can be used to solve all types of linear systems problems.

---

# Notes

- [[Linear Algebra/17 General Linear-Systems/16.2 Row Echelon Form\|16.2 Row Echelon Form]]
- [[Linear Algebra/17 General Linear-Systems/17.1 The General Linear-Systems Problem\|17.1 The General Linear-Systems Problem]]
- [[Linear Algebra/17 General Linear-Systems/17.2 Row Echelon Form\|17.2 Row Echelon Form]]
- [[Linear Algebra/17 General Linear-Systems/17.3 Reduced Row Echelon Form\|17.3 Reduced Row Echelon Form]]
- [[Linear Algebra/17 General Linear-Systems/17.4 Model of Airplane Descent Path to Landing\|17.4 Model of Airplane Descent Path to Landing]]
- [[Linear Algebra/17 General Linear-Systems/17.5 Solving GLSP for Airplane Descent  Path\|17.5 Solving GLSP for Airplane Descent  Path]]
- [[Linear Algebra/17 General Linear-Systems/17.6 Toy GLSP\|17.6 Toy GLSP]]

