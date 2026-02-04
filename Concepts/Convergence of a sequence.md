#### Definition 2.2.3A
A sequence ($a_n$) converges to a real number $a$ if, for every positive number $\epsilon$, there exists an $N \in \mathbb N$ such that whenever $n \geq N$ it follows that $|a_n -a| < \epsilon$.

#### Definition 2.2.3B: Topological version
A sequence ($a_n$) converges to $a$ if, given any $\epsilon$-neighborhood $V_\epsilon(a)$ of $a$, there exists a point in the sequence after which all of the terms are in $V_\epsilon (a)$. In other words, every $\epsilon$-neighborhood contains all but a finite number of the terms of ($a_n$).

Can write it as a limit if it converges. 

A natural number $N$ is the point where the sequence ($a_n$) enters $V_\epsilon(a)$, never to leave. The smaller the $\epsilon$-neighborhood, the larger $N$ might have to be.

---
Template for a proof that $x_n$ converges to $x$: 
- Let $\epsilon > 0$ be arbitrary
- Demonstrate a choice for $N \in \mathbb N$ (done prior to doing the formal proof)
- Now, show that $N$ actually works
- "Assume $n \geq N$"
- With $N$ well chosen, it should be possible to derive $|x_n - x| < \epsilon$

Examples: [[Example 2.2.5]], [[Example 2.2.6]]