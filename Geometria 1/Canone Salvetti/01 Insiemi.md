# 1. Insiemi
A = {a, b, c, …}
$X$, $Y$, $Z$:
- $X \cup Y$ = {$a | a \in X \lor a \in Y$}
- $X \cap Y$ = {$a | a \in X \land a \in Y$}
- $X \cup (Y \cap Z)$ = $(X \cup Y) \cap (X \cup Z)$
- $X \cap (Y \cup Z)$ = $(X \cap Y) \cup (X \cap Z)$
# 2. Applicazioni
Legge che associa un elemento di X a uno di Y
$f: X \rightarrow Y$ vuol dire che a $f(x)$ si associa $f(y)$
$P \subset X \times Y$ è un sottoinsieme tale che $\forall x \in X$   $\exists y \in Y$ t.c. $(x,y) \in P$
## 2.1. Proprietà
$f$ è iniettiva se x diverso y implica f(x) diverso f(y)
$f$ è suggettiva se $\forall y \in Y$  $\exists x \in X$ t.c. $f(x) = y$
- $Im(f) = Y$

Composizione di applicazioni: $(g \circ f)(x) = g(f(x))$
Bigezione: $f$ suggettiva e iniettiva
$f: X \rightarrow Y$ è suggettiva $\iff \exists g: Y \rightarrow X$ t.c.
- $g \circ f = id_X$
- $f \circ g = id_Y$
# 3. Vettori
$\mathbb{R}^2$ = {$(x,y) | x,y \in \mathbb{R}$}
Vettore geometrico: classe di equivalenza di segmenti aventi lunghezza, direzione e verso
Versori (anche ortogonali) $\vec i$ e $\vec j$: $\vec{v}$ diagonale di rettangolo di lati $x\vec{i}$ e $y\vec{j}$
- $\vec{v} = x\vec{i} + y\vec{j}$
## 3.1. Operazioni
Operazione su $X$: applicazione $a: X \times X \rightarrow X$

Somma $+: V \times V \rightarrow V$
- $(\vec u, \vec v) \rightarrow \vec u + \vec v$
- Associatività: $(\vec u + \vec v) + \vec w = \vec u + (\vec v + \vec w)$
- Commutatività: $\vec u + \vec v = \vec v + \vec u$

Prodotto esterno: $\mathbb{R} \times V \rightarrow V$
- $(x, \vec v) \rightarrow x\vec v$
- Associatività: $x(y\vec v) = (xy)\vec v$
- Distributività: $x(\vec u + \vec v) = x\vec u + x\vec v$

Applicazione di operazioni
- Somma: $\vec v + \vec w = (x + x’)\vec i + (y + y’)\vec j$
- Prodotto per costante: $\alpha \vec v = \alpha x \vec i + \alpha x \vec j$
# 4. Insiemi numerici
Campo $\mathbb{K}$: insieme dotato di due operazioni $+, \times$ che verificano una serie di assiomi
1. Associatività della somma: $(x+y)+z = x+(y+z)$
2. Elemento neutro per la somma: $0+x = x+0 = x$
3. Opposto: $\exists x,y$  t.c  $x+y=y+x=0$
4. Commutatività della somma: $x+y = y+x$
5. Associatività del prodotto: $(xy)z = x(yz)$
6. Elemento neutro per il prodotto: $1x = x1 = x$
7. Inverso: $\forall x$ diverso da 0 $\exists y$  t.c.  $xy = yx = 1$ 
8. Commutatività del prodotto: $xy = yx$
9. Distributività: $x(y+z) = xy + xz$

Numeri razionali: $\mathbb{Q}$ = {$\frac a b | a,b\in \mathbb{R}$}
# 5. Esercizi
1. Verificare tutte le proprietà dei campi per l’insieme di elementi 0, 1
2. Dimostrare che l’elemento neutro per la somma è unico
3. Dimostrare che l’opposto alla somma e l’inverso rispetto al prodotto sono unici