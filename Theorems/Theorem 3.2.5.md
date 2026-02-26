A point $x$ is a limit point of a set $A$ if and only if $x = \lim a_n$ for some sequence $(a_n)$ contained in $A$ satisfying $a_n \neq x$ for all $n \in \mathbb N$.

**Proof:**
$(\Rightarrow):$  Assume $x$ is a limit point of $A$. Let $\epsilon = 1/n$. By definition of [[Limit point|limit points]], every neighborhood of $x$ intersects $A$ in some point other than $x$. Hence, for each $n\in\mathbb N$, we can pick a point $$a_n\in V_{1/n}(x)\cap A$$
with the condition that $a_n \neq x$.
Given arbitrary $\epsilon > 0$, choose $N$ s.t. $1/N < \epsilon$. It follows that $|a_n - x| < \epsilon \ \forall \ n \geq \mathbb N$. 
$(\Leftarrow):$  Assume $\lim a_n = x$ where $a_n \in A$ but $a_n \neq x$. Let $V_{\epsilon}(x)$ be an arbitrary $\epsilon$-neighborhood. By the definition of convergence, there exists a term $a_N$ s.t. $a_N \in V_\epsilon (x)$. $\square$

