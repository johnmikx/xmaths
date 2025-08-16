# **Converge of $a_n = \frac{2n}{n + 1}$ Proof and Plot**

Plots the sequence $a_n = \dfrac{2n}{n + 1}$ and show it approaches the limit $2$.

## **Formal $Epsilon-N$ Proof**

**Prove**: $ \lim_{n\to\infty} \dfrac{2n}{n + 1} = 2$

Compute:
$$
\left|\frac{2n}{n + 1} - 2\right|
= \left|\frac{2n - 2(n + 1)}{n + 1}\right|
= \left|\frac{-2}{n + 1}\right|
= \frac{2}{n + 1}
$$

Given any $\varepsilon > 0$, choose $N$ such that

$$\frac{2}{N + 1} < \varepsilon$$

Solving for $N$ gives one convenient choice: take

$$N =\left\lceil\frac{2}{\varepsilon}\right\rceil.$$

Then for every $n\ge N$ we have $|a_n - 2|\le\dfrac{2}{n + 1}\le\dfrac{2}{N + 1}\le\varepsilon.$

Thus $a_n\to 2$

>***This completes the proof for $a_n = \dfrac{2n}{n+1}$***.

***:)***