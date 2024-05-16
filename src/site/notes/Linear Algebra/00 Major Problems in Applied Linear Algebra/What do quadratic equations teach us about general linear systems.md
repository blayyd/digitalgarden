---
{"date created":"Monday, April 1st 2024, 10:06:43 pm","date modified":"Thursday, April 18th 2024, 8:01:08 pm","time spent":"22 min","tags":["Type/Example","Topic/Linear_Algebra"],"links":"[[00 Major Problems in Applied Linear Algebra]]","dg-publish":true,"permalink":"/linear-algebra/00-major-problems-in-applied-linear-algebra/what-do-quadratic-equations-teach-us-about-general-linear-systems/","dgPassFrontmatter":true}
---

Types: *N/A*
Examples: *N/A*
Constructions: *N/A*
Generalizations: [[Linear Algebra/00 Major Problems in Applied Linear Algebra/2B The General Linear-Systems Problem\|2B The General Linear-Systems Problem]]

Properties: *N/A*
Sufficiencies: *N/A*
Questions: *N/A*

> [!example] 
> In algebra and precalculus, the **forward problem** we learn to solve is function evaluation and the **backward problem** is algebra based on the quadratic function. 
> 
> Let $f(x) = x^{2}$. (Remember that this is nonlinear, so this analogy only goes so far.)

Let's solve the forward problem by substituting in a value for $x$. Let $x=2$:
$$
\begin{align}
 & \implies f(x) = f(2) = 2^{2} = 4 \\
 & \implies (2,4) \in f
\end{align}
$$
To solve, the backward problem, we have three options.

# Option 1: Unique Solution
$$
\begin{align*}
f(\textcolor{red}{x}) = \textcolor{red}{x}^{2}&= 0\\
\implies \sqrt{ \textcolor{red}{x}^{2} } &= \sqrt{ 0 }\\
\implies \lvert \textcolor{red}{x} \rvert &= 0\\
\implies x &= 0
\end{align*}
$$

# Option 2: Nonunique solution
$$
\begin{align}
f(\textcolor{red}{x}) = 4  & \implies \textcolor{red}{x}^{2} = 4 \\
 & \implies \sqrt{ \textcolor{red}{x^{2}} } = \sqrt{ 4 } \\
 & \implies \lvert \textcolor{red}{x} \rvert = +2 \\
\hline  \\
 & \implies x = +2 \text{ or } x = -2
\end{align}
$$
The analogy breaks down at the line because there are multiple solutions. In matrix-vector multiplication, if a solution exists and it is not unique, there will be many more than just two solutions.

# Option 3: Output $b \in \text{Codomain}(f)$ but $b \notin \text{Rng}(f)$
$$
f(\textcolor{red}{x}) = -1 \implies \textcolor{red}{x}^{2} = -1
$$

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">




==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
-5   -4    -3   -2   -1   0      1    2     3    4    5 
5

4

3

2

1   

0


-1

-2

-3

-4

-5 
x 
y 


</div></div>

There is no solution in $\mathbb{R}$, but we can "minimize" the "distance" from outputs of $f(x)$ to our chosen value of $b \in \text{Codomain}(f)$.
