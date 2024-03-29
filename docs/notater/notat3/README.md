# Mengder, inklusjon, snitt, union, komplement.
## Aksiom 3.1
(Likhet av mengder). La $A$ og $B$ være mengder. Da er $A$ og $B$ like hvis og bare hvis de har akkurat de samme elementene. Det vil si:$$(A=B)\iff (\forall x\quad x\in A \iff x\in B)$$

## Definisjon 3.1 
Vi sier at en egenskap $P$ er *mengdedannende* dersom det finnes en mengde $A$ slik at: $$\forall x\quad x\in A\iff P(x)$$ Det følger i såfall av likhetsaksiomet at $A$ er entydig bestemt av $P$. Vi bruker følgende notasjon: $$A=\{x\; :\; P(x)\}$$

## Definisjon 3.2
En mengde $A$ er *tom* dersom den ikke har noen elementer. Det vil si: $$\forall x\quad x\notin A$$

## Aksiom 3.2 
Egenskapen $\langle\langle x\; :\; x\neq x\rangle\rangle$ er mengdedannende, slik at det finnes en tom mengde. Den tomme mengden skrives $\emptyset$.

## Aksiom 3.3 
Gitt et objekt $x$ vil egenskapen $\langle\langle y\; : \; y=x\rangle\rangle$ være mengdedannende. Vi skriver $$\{x\}=\{y\; :\; y=x\}$$ Mengder av denne typen kalles *ettpunktsmengder*.

## Aksiom 3.4 
(Spesialisering). Dersom $A$ er en mengde og $P$ en egenskap, er egenskapen $\langle\langle x\; :\; x\in A\land P(x)\rangle\rangle$ mengdedannende. Vi forkorter: $$\{x\in A\; :\; P(x)\}=\{x\; :\; x\in A\land P(x)\}$$

## Definisjon 3.3
At $A$ er *inkludert* i $B$ skrives $A\subseteq B$ og er definert ved: $$(A\subseteq B)\iff (\forall x \quad x\in A\implies x\in B)$$
 
## Definisjon 3.4
Gitt mengder $A$ og $B$ kan vi definere:<br>
* *snittet* av $A$ og $B$: $A\cap B=\{x\in A\; :\; x\in B\}$
* *differansen* av $A$ og $B$: $A\backslash B=\{x\in A\; :\; \neg(x\in B)\}$
* *unionen* av $A$ og $B$: $A\cup B=\{x\in A\; :\; x\in A\lor x\in B\}$

## Aksiom 3.5 
Gitt mengder $A$ og $B$ er egenskapen $\langle\langle x\; :\; x\in A\lor x\in B\rangle\rangle$ mengdedannende.

## Definisjon 3.5 
Når $B\subseteq A$ er det vanglig å kalle $A\backslash B$ for komplementet til $B$ i $A$ og man kan bruke notasjonen $\mathcal{C}_A(B)=A\backslash B$. Evt. $\mathcal{C}(B)=B^{\mathcal{C}}=A\backslash B$.


