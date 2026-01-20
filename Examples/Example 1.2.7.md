Let $x_1 = 1$, and for each $n \in N$, define $x_{n+1} = \frac{1}{2} x_n + 1$. Show $x_n \leq x_{n+1}$ for all values of $n \in N$.

---
$x_1 = 1, x_2 = 3/2$, so $x_2 \geq x_1$. Show that if we have $x_n \leq x_{n+1}$, then $x_{n+1} \leq x_{n+2}$ by multiplying both sides by 1/2 and adding 1:
$$\frac{1}{2}x_n + 1 \leq \frac{1}{2}x_{n+1} + 1$$
which is exactly $x_{n+1} \leq x_{n+2}$
By induction, claim is proved for all $n \in N \qquad \square$

