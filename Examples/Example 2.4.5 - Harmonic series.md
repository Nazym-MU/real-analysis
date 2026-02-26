Harmonic series:
$$  
\sum_{n=1}^{\infty} \frac{1}{n}.  
$$
Increasing sequence of partial sums:
$$  
s_m = 1 + \frac{1}{2} + \frac{1}{3} + \cdots + \frac{1}{m},  
$$
appears bounded, but $2$ is no longer an upper bound because
$$  
s_4 = 1 + \frac{1}{2} + \left( \frac{1}{3} + \frac{1}{4} \right)

> 1 + \frac{1}{2} + \left( \frac{1}{4} + \frac{1}{4} \right)  
= 2$$
In general:
$$
s_{2^k}
= 1 + \frac{1}{2}
+ \left( \frac{1}{3} + \frac{1}{4} \right)
+ \left( \frac{1}{5} + \cdots + \frac{1}{8} \right)
+ \cdots
+ \left( \frac{1}{2^{k-1}+1} + \cdots + \frac{1}{2^k} \right)
$$
$$
> 1 + \frac{1}{2}
+ \left( \frac{1}{4} + \frac{1}{4} \right)
+ \left( \frac{1}{8} + \cdots + \frac{1}{8} \right)
+ \cdots
+ \left( \frac{1}{2^k} + \cdots + \frac{1}{2^k} \right)
$$
$$
= 1 + \frac{1}{2}
+ 2\left(\frac{1}{4}\right)
+ 4\left(\frac{1}{8}\right)
+ \cdots
+ 2^{k-1}\left(\frac{1}{2^k}\right)
$$
$$
= 1 + \frac{1}{2}
+ \frac{1}{2}
+ \frac{1}{2}
+ \cdots
+ \frac{1}{2}
$$
$$
= 1 + k\left(\frac{1}{2}\right)
$$
which is unbounded. Thus, despite the incredibly slow pace, the sequence of partial sums of $\sum_{n=1}^{\infty} \frac{1}{n}$ eventually surpasses every number on the positive real line. Because convergent sequences are bounded, the harmonic series diverges.