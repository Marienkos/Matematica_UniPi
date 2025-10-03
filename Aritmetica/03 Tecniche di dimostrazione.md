# Principio di induzione
{ALG} Principio di induzione
Supponiamo di dover dimostrare la veridicità del predicato $P(n)$ $\forall n \in \mathbb N$. Per farlo serve:
- Passo base: controlliamo $P(0)$
- Passo induttivo: dimostriamo che con $n \ge 0$, $P(n) \implies P(n+1)$

{ALG} Principio di induzione forte
In questo caso dimostriamo la veridicità di $P(n)$ $\forall n \ge n_0$
- Passo base: controlliamo $P(n_0)$
- Passo induttivo: dimostriamo che $\forall n \ge n_0 \text{ , }(P(n_0) \land P(n_0+1) \land … \land P(n)) \implies P(n+1)$