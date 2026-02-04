A function from $A$ to $B$ is a mapping that takes each element $x \in A$ and associates with it a single element of $B$
$$f: A \to B$$
The [[Set|set]] $A$ is called the [[Domain|domain]] of $f$
The [[Range|range]] of $f$ is the subset of $B$ given by $\{y \in B: y = f(x) \text{ for some } x \in A\}$

[[One-to-one]]: $a_1 \neq a_2$ in $A$ implies that $f(a_1) \neq f(a_2)$ in $B$.
[[Onto]]: Given any $b \in B$, it is possible to find an element $a \in A$ for which $f(a) = B$.

1-1 correspondence between sets happens when a function is both 1-1 and onto.
## Examples
- Dirichlet function:
	- $g(x) = \begin{cases} 1 & \text{if } x \in Q \\ 0 & \text{if } x \notin Q \end{cases}$
	- The domain of $g$ is all of $R$, and the range is the set {0, 1}
- Absolute value function:
	- $|x| = \begin{cases} x & \text{if } x \geq 0 \\ -x & \text{if } x < 0 \end{cases}$
	- $|ab|=|a|\cdot |b|\qquad |a+b| \leq |a| + |b|$  - triangle inequality
	- Given three real numbers a, b, and c: $|a-b| = |(a-c) + (c-b)|$
	- By the [[Triangle inequality|triangle inequality]], $|a-b| \leq |a-c| + |c-b|$