# Fibonacci
[Successione di Fibonacci]
- $F_0 = 0$
- $F_1 = 1$
- $\forall n \ge2$  $F_n = F_{n-1} + F_{n-2}$

{DIM} Formula chiusa
Immaginiamo che $F_n = \alpha^n$: notiamo subito che $a$ non può essere 0
Dunque vale $\alpha^n = \alpha^{n-1} + \alpha^{n-2} \rightarrow \alpha^2 - \alpha - 1 = 0$
Dunque $\alpha = \frac{1+\sqrt 5}{2}$ oppure $\beta = \frac{1-\sqrt 5}{2}$
Singolarmente non reggono, tentiamo una combinazione del tipo $F_n = a\alpha^n + b\beta^n$
$$\begin{cases}
a + b = 0\\
a\alpha + b\beta = 1
\end{cases}$$
Da cui deriva che $F_n = \frac{1}{\sqrt 5}\alpha^n - \frac{1}{\sqrt 5}\beta^n$ è una formula chiusa per i numeri di Fibonacci

{DIM} Generalizzazione
Per tutte le successioni ricorsive lineari a coefficienti costanti vale il seguente procedimento:
- Si tenta la potenza considerando la legge di ricorsione
- Si trovano le radici del polinomio corrispondente
- Si risolve il sistema della combinazione lineare per trovare i coefficientii