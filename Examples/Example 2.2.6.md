Show $$\lim \left( \frac{n+1}{n} \right) = 1.$$
The last line should be $\left| \frac{n+1}{n} - 1 \right| < \epsilon$.
Because $\left| \frac{n+1}{n} - 1 \right| = \frac{1}{n}$, this is equivalent to $1/n < \epsilon$ or $n > 1/\epsilon$. Thus, choosing an integer $N$ greater than $1/\epsilon$ will suffice.

**Proof:**
Let $\epsilon > 0$ be arbitrary. Choose $N \in \mathbb N$ with $N > 1/\epsilon$. To verify that this choice of $N$ is appropriate, let $n \in \mathbb N$  satisfy $n \geq N$. Then, $n \geq N$ implies $n > 1/\epsilon$, which is the same thing as $1/n < \epsilon$. Finally, this means, $$\left| \frac{n+1}{n} - 1 \right| < \epsilon \qquad \square$$

