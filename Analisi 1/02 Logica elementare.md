# Proposizioni
[Proposizione] frase di cui ha senso chiedersi se è vera o falsa
{OSS} Non è necessario essere in grado di stabilire la veridicità

# Operazioni tra proposizioni
[Negazione, NOT, $\neg$] dire il contrario
[AND, $\land$] P $\land$ Q è vera se sia P che Q sono vere
[VEL, OR, $\lor$] P $\lor$ Q è vera se almeno una tra P e Q è vera
[AUT, XOR] P AUT Q è vera se solo una tra P e Q è vera
[P $\implies$ Q] se P è vera Q deve essere vera, se P è falsa Q è libero
[P $\iff$ Q] P e Q sono entrambe vere o entrambe false
{OSS} P $\implies$ Q = NOT Q $\implies$ NOT P

{PRP} Negazione di AND e VEL
- NOT (P $\land$ Q) = (NOT P) $\lor$ (NOT Q)
- NOT (P $\lor$ Q) = (NOT P) $\land$ (NOT Q)
# Predicati
[Predicato] proposizione paramentrica (la veridicità varia a seconda dei parametri)
[Quantificatori] $\forall$ (per ogni), $\exists$ (esiste almeno un), $\exists!$ (esiste ed è unico)
{OSS} Un predicato con tutte le variabili quantificate è una proposizione

{PRP} Negazione di quantificatori
- NOT ($\forall$x P(x)) = $\exists$x NOT P(x)
- NOT ($\exists$x P(x)) = $\forall$x NOT P(x)
{OSS} In generale si invertono i quantificatori e si nega il predicato
# Insiemi
[Insieme] collezione di elementi
[Modalità di creazione] per elenco e per proprietà
[Operazioni] unione, intersezione, differenza
[Prodotto cartesiano] insieme di coppie ordinate $(a,b)$ con $a \in A \land b \in B$
[Sottoinsieme] $A \subseteq B$ vuol dire $\forall x$ $x \in A \implies x \in B$
[Insieme delle parti] insieme dei sottoinsiemi
# 4. Esercizi
1. Calcolare formalmente la tavola di verità di NOT Q $\implies$ NOT P e di NOT P $\lor$ Q
2. Calcolare in quanti modi si può quantificare un predicato con k parametri