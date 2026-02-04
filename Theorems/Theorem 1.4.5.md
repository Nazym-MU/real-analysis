There exists a real number $\alpha \in R$ satisfying $\alpha^2 = 2$.
**Proof:**
Consider $T = \{t \in R: t^2 < 2\}$ and let $\alpha = \sup T$.
Prove the statement by ruling out the possibilities $\alpha^2 < 2$ and $\alpha^2 > 2$.

- Case $\alpha^2 < 2$. Search element $T$ larger than $\alpha$:
	- $$\left( \alpha + \frac{1}{n}\right)^2 = \alpha^2 + \frac{2\alpha}{n} + \frac{1}{n^2} < \alpha^2 +\frac{2\alpha}{n} + \frac{1}{n} = \alpha^2 + \frac{2\alpha +1}{n}$$
	- Assuming $\alpha^2 < 2$ gives space to fit $\frac{2\alpha +1}{n}$ term and keep the total less than 2. Choose $n_0 \in N$ large enough so that $$\frac{1}{n_0} < \frac{2-\alpha^2}{2\alpha + 1}$$
	- This implies $\frac{2\alpha + 1}{n_0} < 2 -\alpha^2$.
	- As a consequence, $\left( \alpha + \frac{1}{n_0} \right)^2 < \alpha^2 + (2-\alpha^2) = 2$
	- Thus, $\frac{\alpha+1}{n_0} \in T$, contradicting the fact that $\alpha$ is an upper bound for $T$.
	- $a^2 < 2$ cannot happen.
- Case $\alpha^2 > 2$.
	- $$\left( \alpha - \frac{1}{n}\right)^2 = \alpha^2 - \frac{2\alpha}{n} + \frac{1}{n^2} > \alpha^2 - \frac{2\alpha}{n}$$