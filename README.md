
$Z = \min(U,V)$

$Cov (Z,V) = \int \int z v f(z) f(v) dz dv- E(Z) E(V)$ 

We first find $f(z)$

$$f(z) = \frac{d}{dz} F(z)$$
where  the cumulative density function, $F(z)$ is
$$F(z) = P(Z \leq z)$$ 

We need to find
$$P(Z \leq z)$$

Let A be the event $Z \leq z$, where $z \in [0,1]$

A = event ${\min(u,v) \leq z}$

# By Partition Theorem

$$P(A) = \Sigma P(A \cap B_i)$$

$$P(A) = P((U \leq z) \cap (V > u))+P((V\leq z) \cap (U>v))$$

$$P((U \leq z) \cap (V > u))=P(U \leq z) \times P(V > u)$$
$$=\int_0^z f(u) du \times \int_u^1 f(v)  dv$$
$$=\int_0^z 1 \times \int_u^1 1  dv du $$
$$=\int_0^z 1 \times (1-u) du$$
$$=\int_0^z (1-u) du$$ 
$$=[z-\frac{z^2}{2}]$$ 

Similarly

$$P((V \leq z) \cap (U > v)) =[z-\frac{z^2}{2}]$$


$$P(Z \leq z) = 2[z - \frac{z^2}{2}]$$

Our density functions are:
$$F(z) = 2z - z^2 , z\in[0,1] $$
$$f(z) = z - 2z,     z\in[0,1] $$


$Cov (Z,V) = \int_0^1 \int_0^1 z v f(z) f(v) dz dv- E(Z) E(V)$ 

$$\lim_{\epsilon \to 0} P(170 - \epsilon<X<170 + \epsilon)$$
$$=\lim_{\epsilon \to 0} $$
<IMG  src="https://miro.medium.com/max/734/0*NiiCvqUT_Y2fpNMP.png"  alt="Integral Calculus basics. Integral calculus is a process to… | by ..."/>

<IMG  src="https://www.mathcs.emory.edu/~cheung/Courses/170/Syllabus/07/FIGS/rectangle01.gif"  alt="The Rectangle Method"/>

```

```

$$P((V \leq z) \cap (U > v))$$
$$=\int_0^z  \int_v^1 f(v) f(u)  du dv$$


$$P(Z \leq z)$$








# Cumulative Density

$P(X \leq x) = F(x) = \int_{-\infty}^x f(x) dx$
Z 
