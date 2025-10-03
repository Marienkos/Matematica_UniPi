# 1. Numeri complessi
$\mathbb C = \{a+ib\mid a,b\in \mathbb R\}$ dove $a$ è la parte reale, $b$ quella immaginaria e vale $i^2=-1$
Esiste la bigezione $\mathbb C \rightarrow \mathbb R^2$, ossia $a+ib \rightarrow (a,b)$

Somma $+: \mathbb C \times \mathbb C \rightarrow \mathbb C$
- $(a+ib) +_{\mathbb C} (c+id) = (a+_{\mathbb R} c) + i(b+_{\mathbb R}d)$

Prodotto $\cdot : \mathbb C \times \mathbb C \rightarrow \mathbb C$
- $(a+ib)\cdot (c+id) = (ac-bd) + i(ad+bc)$

Avendo $z = a+ib$, la norma $|z|=\sqrt{a^2+b^2}$ il modulo del vettore $(a,b)$
- NOTARE: $z=0$ è l’unico numero uguale alla sua norma

Coniugio: $\mathbb C \rightarrow \mathbb C$
- $z=a+ib, \overline{z}=a-ib$

Inverso moltiplicativo:
- $z\overline z = (a+ib)(a-ib) = |z|^2$
- Se $z=0$ allora $|z| = 0$
- $z\frac{\overline z}{|z|^2} = 1$ per cui $\frac{1}{z} = \frac{\overline z}{|z|^2}$

Di conseguenza $(\mathbb C, +, \cdot)$ è un campo
## 1.1 Forma trigonometrica
Sia dato un vettore di componenti $(a,b)$
- Il suo modulo $\rho = \sqrt{a^2+b^2}$
- L’angolo con il semiasse positivo delle ascisse, anche chiamato argomento, ha formula:
$$\theta = \begin{cases}
\arctan(\frac b a) \text{ se } a>0 \\
\arctan(\frac b a) + \pi \text{ se } a<0 \\
\frac \pi 2 \text{ se } a=0, b>0 \\
-\frac \pi 2 \text{ se } a=0,b<0
\end{cases}$$
Siano dati $z = a+ib = \rho (\cos \theta + i \sin \theta)$ e $w = x(\cos \theta’+i\sin \theta’)$
Allora il loro prodotto $zw = \rho x(\cos (\theta + \theta’) +i\sin (\theta + \theta’))$
Da cui, sapendo che $|zw| = |z| \cdot |w|$ si evince che $|z^n| = |z|^n$
Inoltre sapendo che $\arg(zw) = \arg z + \arg w$, allora $\arg(z^n) = n\arg z$
Se si ha $|z|^n = |w|$ allora
- $|z| = \sqrt[n]{|w|}$
- $n\arg z = \arg w + 2k\pi$ da cui $\arg z = \frac{\arg w} n + \frac{2k\pi}{n}$
## 1.2. Teorema fondamentale dell’algebra
Se $P(z) \in \mathbb C[\mathbb Z]$ non costante allora $\exists z \in \mathbb C$ t.c. $P(z_0) = 0$