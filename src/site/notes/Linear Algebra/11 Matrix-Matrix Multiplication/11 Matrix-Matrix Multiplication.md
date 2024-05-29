---
{"dg-publish":true,"permalink":"/linear-algebra/11-matrix-matrix-multiplication/11-matrix-matrix-multiplication/","tags":["MOC"]}
---

# 11 Matrix-Matrix Multiplication
The main idea of modern (post 1950s) linear algebra is to build new technology on simpler technology. Using this main idea, the definition of matrix-matrix multiplication can be developed using the skills we developed from "simpler technology," [[Linear Algebra/10 Matrix-Vector Multiplication/10 Matrix-Vector Multiplication\|10 Matrix-Vector Multiplication]]. Before learning the definition of matrix-matrix multiplication, we need to go over the terminology to describe the matrix-matrix product. 

Let matrices $A \in \mathbb{R}^{m \times p}$ and $X \in \mathbb{R}^{p \times n}$. The *output* of the matrix-matrix multiplication is the matrix $B \in \mathbb{R}^{m \times n}$ (AKA the *product* of $A$ and $X$). 
$$
A \cdot X = B
$$
- $A \in \mathbb{R}^{m \times p}$ is the left argument/left factor
- $X \in \mathbb{R}^{p \times n}$ is the right argument/right factor
- ! The inner dimensions must agree! ($A$ must be **conformable** for right multiplication by $X$)
- If the number of rows of $X$ does not match the number of columns of $A$, we say matrix $A$ is **nonconformable** for matrix-matrix multiplication on the right side by $X$

This operation is a map between vector spaces
$$
\mathbb{R}^{m \times p} \times \mathbb{R}^{p \times n} \mapsto \mathbb{R}^{m \times n}.
$$
{ #c2fc8c}



---
# Notes
Lessons after 6 focus on applications of matrix-matrix multiplication.

- [[Linear Algebra/11 Matrix-Matrix Multiplication/11.1 Anatomy of Matrix-Matrix Multiplication\|11.1 Anatomy of Matrix-Matrix Multiplication]]
- [[Linear Algebra/11 Matrix-Matrix Multiplication/11.2 Matrix-Matrix Multiplication via Linear Combination of Columns\|11.2 Matrix-Matrix Multiplication via Linear Combination of Columns]]
- [[Linear Algebra/11 Matrix-Matrix Multiplication/11.2.1 Example of Matrix-Matrix Multiplication via Linear Combination of Columns\|11.2.1 Example of Matrix-Matrix Multiplication via Linear Combination of Columns]]
- [[Linear Algebra/11 Matrix-Matrix Multiplication/11.3 Matrix-Matrix Multiplication via Linear Combination of Rows\|11.3 Matrix-Matrix Multiplication via Linear Combination of Rows]]
- [[Linear Algebra/11 Matrix-Matrix Multiplication/11.3.1 Example of Matrix-Matrix Multiplication via Linear Combination of Rows\|11.3.1 Example of Matrix-Matrix Multiplication via Linear Combination of Rows]]
- [[Linear Algebra/11 Matrix-Matrix Multiplication/11.4 Matrix-Matrix Multiplication via Dot Products\|11.4 Matrix-Matrix Multiplication via Dot Products]]
- [[Linear Algebra/11 Matrix-Matrix Multiplication/11.4.1 Example of Matrix-Matrix Multiplication via Dot Products\|11.4.1 Example of Matrix-Matrix Multiplication via Dot Products]]
- [[Linear Algebra/11 Matrix-Matrix Multiplication/11.5 Matrix-Matrix Multiplication via Outer Products\|11.5 Matrix-Matrix Multiplication via Outer Products]]
- [[Linear Algebra/11 Matrix-Matrix Multiplication/11.6 Algebraic Properties of Matrix-Matrix Multiplication\|11.6 Algebraic Properties of Matrix-Matrix Multiplication]]
- [[Linear Algebra/11 Matrix-Matrix Multiplication/11.7 Applications for Mass Spring Chain\|11.7 Applications for Mass Spring Chain]]

