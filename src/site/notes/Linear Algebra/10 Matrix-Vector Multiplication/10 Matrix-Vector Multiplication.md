---
{"date created":"Thursday, March 21st 2024, 9:40:39 pm","date modified":"Wednesday, May 15th 2024, 4:51:56 pm","tags":["MOC"],"links":null,"playlist":"https://youtube.com/playlist?list=PLSt7rwoPGTy0W0tzVaqQh3RzlLVzTwW1s","project status":"Done","time estimate":"10h","difficulty":3,"completion time":"12h 31m","dg-publish":true,"permalink":"/linear-algebra/10-matrix-vector-multiplication/10-matrix-vector-multiplication/","dgPassFrontmatter":true}
---

# 10 Matrix-Vector Multiplication
The term *matrix-vector multiplication* is shorthand for one of two different operations:
1. Matrix-column-vector multiplication: Multiply a matrix $A \in \mathbb{R}^{m \times n}$ on the right by a [[Linear Algebra/03 Vector Modeling/3.1 Column Vector\|3.1 Column Vector]] $\vec{x} \in \mathbb{R}^{n \times 1}$ to produce to a column vector
$$
A \vec{x} = \vec{b} \in \mathbb{R}^{m \times 1}
$$
2. Row-vector-matrix multiplication: Multiply a matrix $A \in \mathbb{R}^{m \times n}$ on the left by a row vector $\vec{x}^{T}$ where $\vec{x} \in \mathbb{R}^{ 1 \times n}$ to produce a row vector
$$
\vec{x}^{T} A = \vec{b} \in \mathbb{R}^{1 \times n}
$$

> [!tldr] 
> We think about finding our desired output vector $\vec{b}$ through two different methods:
> 1. Vectorize the data: Generate the output as a [[Linear Algebra/06 Span and Linear Independence/6.1 Linear Combination of Vectors\|6.1 Linear Combination of Vectors]].
> 2. Scalarize the data: Generate the output as a set of individual entries.


---

# Notes

- [[Linear Algebra/10 Matrix-Vector Multiplication/10.1 Matrix-Column-Vector Multiplication via Linear Combinations\|10.1 Matrix-Column-Vector Multiplication via Linear Combinations]]
- [[Linear Algebra/10 Matrix-Vector Multiplication/10.1.1 Example of Matrix-Column-Vector Multiplication via Linear Combinations\|10.1.1 Example of Matrix-Column-Vector Multiplication via Linear Combinations]]
- [[Linear Algebra/10 Matrix-Vector Multiplication/10.2 Matrix-Column-Vector Multiplication via Dot Products\|10.2 Matrix-Column-Vector Multiplication via Dot Products]]
- [[Linear Algebra/10 Matrix-Vector Multiplication/10.2.1 Example of Matrix-Column-Vector Multiplication Using Dot Products\|10.2.1 Example of Matrix-Column-Vector Multiplication Using Dot Products]]
- [[Linear Algebra/10 Matrix-Vector Multiplication/10.3 Properties of Matrix-Column-Vector Multiplication\|10.3 Properties of Matrix-Column-Vector Multiplication]]
- [[Linear Algebra/10 Matrix-Vector Multiplication/10.4 Row-Vector-Matrix Multiplication via Linear Combinations\|10.4 Row-Vector-Matrix Multiplication via Linear Combinations]]
- [[Linear Algebra/10 Matrix-Vector Multiplication/10.4.1 Example of Row Vector Matrix Multiplication via Linear Combinations\|10.4.1 Example of Row Vector Matrix Multiplication via Linear Combinations]]
- [[Linear Algebra/10 Matrix-Vector Multiplication/10.5 Row-Vector-Matrix Multiplication via Dot Products\|10.5 Row-Vector-Matrix Multiplication via Dot Products]]
- [[Linear Algebra/10 Matrix-Vector Multiplication/10.5.1 Example of Row-Vector-Matrix Multiplication via Dot Products\|10.5.1 Example of Row-Vector-Matrix Multiplication via Dot Products]]
- [[Linear Algebra/10 Matrix-Vector Multiplication/10.6 Relation Between Matrix-Vector Multiplication and Matrix Partitions\|10.6 Relation Between Matrix-Vector Multiplication and Matrix Partitions]]
- [[Linear Algebra/10 Matrix-Vector Multiplication/10.7 Properties of Row-Vector-Matrix Multiplication\|10.7 Properties of Row-Vector-Matrix Multiplication]]
- [[Linear Algebra/10 Matrix-Vector Multiplication/10.8 Transpose of a Matrix-Vector Product\|10.8 Transpose of a Matrix-Vector Product]]

