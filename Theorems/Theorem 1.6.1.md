> The open interval $(0, 1) = {x \in \mathbb R: 0 < x < 1}$ is uncountable.

Proof by contradiction:
Assume there exists a function $f: \mathbb N \to (0, 1)$ that is 1-1 and onto. For each $m \in \mathbb N, f(m)$ is a real number between 0 and 1, and we represent it using the decimal notation $$f(m) = .a_{m1}a_{m2}a_{m3}a_{m4}a_{m5}.....$$ $a_{mn}$ is the digit from the set ${0, 1, 2, ..., 9}$ that represents the $n$th digit in the decimal expansion of $f(m)$. The 1-1 correspondence between $\mathbb N$ and (0, 1) can be summarized in the doubly indexed array
$$\begin{array}{c c c l}
\mathbb{N} & & (0,1) & \\[6pt]
1 & \longleftrightarrow & f(1) &= .\, a_{11}\; a_{12}\; a_{13}\; a_{14}\; a_{15}\; a_{16}\; \cdots \\
2 & \longleftrightarrow & f(2) &= .\, a_{21}\; \mathbf{a_{22}}\; a_{23}\; a_{24}\; a_{25}\; a_{26}\; \cdots \\
3 & \longleftrightarrow & f(3) &= .\, a_{31}\; a_{32}\; \mathbf{a_{33}}\; a_{34}\; a_{35}\; a_{36}\; \cdots \\
4 & \longleftrightarrow & f(4) &= .\, a_{41}\; a_{42}\; a_{43}\; \mathbf{a_{44}}\; a_{45}\; a_{46}\; \cdots \\
5 & \longleftrightarrow & f(5) &= .\, a_{51}\; a_{52}\; a_{53}\; a_{54}\; \mathbf{a_{55}}\; a_{56}\; \cdots \\
6 & \longleftrightarrow & f(6) &= .\, a_{61}\; a_{62}\; a_{63}\; a_{64}\; a_{65}\; \mathbf{a_{66}}\; \cdots \\
\vdots & & \vdots & \qquad\vdots
\end{array}
$$
Every real number in (0, 1) is assumed to appear somewhere on this list. Now, define a real number $x \in (0, 1)$ with the decimal expansion $x = .b_1b_2b_3b_4...$ using the rule $$b_n = \begin{cases} 2 & \text{if } a_{nn} \neq 2 \\ 3 & \text{if } a_{nn} = 2 \end{cases}$$