# Direkte/invers bilde. Naturlige tall, Peanos aksiomer.
## Definisjon 4.6
La $f: U\to V$ være en avbildning.<br>
Når $A\subseteq U$ definerer vi direktebildet til $A$ som:
<center><img src="./def4.6.png" style="height: 90%"></center>
Når $B\subseteq A$ definerer vi inversbildet til $B$ som: $$f^{-1}[B]=\{x\in U \; :\; f(x)\in B\}$$

### Tall

Hva er egentlig tall? Tanken her, er ikke å si hva tall er, hva deres interne struktur muligens kan være,men å si hva vi kan gjøre med dem, sett utenifra. Vi er vant til å addere og multiplisere tall, og sammenlikne dem, for eksempel, men er disse operasjonene uavhengige av hverandre? Kan de muligens avledes fra et enklere og mer grunnleggende konsept? Her skal vi ta utgangspunkt i en tellemekanisme, som vi tenker oss at består i å legge til én. Vi påstår at $0$ er et naturlig tall, og at hvert naturlige tall n har en suksessor $S(n)$. Vi tenker oss her at $S(n) = n + 1$, men at addisjon vil være en operasjon vi skal definere senere, ved hjelp av $S$. Vi forholder oss i utgangspunktet bare til at mengden $\mathbb{N}$ er utstyrt med et spesielt element $0\in \mathbb{N}$ og en avbildning $S : \mathbb{N} \to \mathbb{N}$. Akkurat hva trenger man å vite om $0$ og $S$ for at alle andre egenskaper ved de naturlige tallene skal kunne utledes? Det vanligste settet med aksiomer for $0$ og $S$ kalles Peanos aksiomer.

### Naturlige tall
**Peanos aksiomer**. Det naturlige tallene utgjør en mengde N slik at følgende gjelder:

## Aksiom 6.1 (Peanos aksiomer)

* Mengden $\mathbb{N}$ er utstyrt med:
    * et valg av element $0\in \mathbb{N}$, kalt null,
    * et avbildning $S : \mathbb{N} \to \mathbb{N}$, kalt suksessorfunksjonen.
* Elementet $0$ er ikke i verdimengden til $S$.
* Avbildningen $S$ er injektiv.
* (Induksonsbevis) La $P$ være en egenskap på $\mathbb{N} slik at:
    * $P(0)$,
    * $\forall n\in\mathbb{N}\; P(n) \implies P(S(n))$.
    * Da holder $\forall n\in\mathbb{N}\; P(n)$.

Vi bemerker at den induserte avbildningen $S : \mathbb{N} \to \mathbb{N} \backslash \{0\}$ må være en bijeksjon:

## Proposisjon 6.1
*Avbildningen $S : \mathbb{N} \to \mathbb{N} \backslash \{0\}$ er surjektiv.*

*Bevis*: Vi viser det ved induskjon. For hver $n\in \mathbb{N}$ har vi $P(n)$ være utsagnet:<br>
(i) Vi har da $P(0)$.<br>
(ii) La $n\in \mathbb{N}$. Utsagnet $P(S(n))$ er sant, dermed er utsagnet $P(n)\implies P(S(n))$ sant.<br>
&nbsp;&nbsp;&nbsp;&nbsp; Det første vi skal gjøre er å definere addisjon på $\mathbb{N}$. Man kan forsåvidt formulere et aksiom om at det finnes en avbilding $+ : \mathbb{N}\times\mathbb{N} \to \mathbb{N}$ slik at, for alle $m, n\in \mathbb{N}$:
$$m+0=m$$
$$m + S(n) = S(m + n)$$

Fra dette kan man utlede alle andre egenskaper ved $+$, ved induksjonsprinsippet.

## Definisjon 6.1
La $A$ være en ikke-tom mengde. En *følge* i $A$ er en avbildning $u : N \to A$. Når $u : N \to A$ er en følge er det vanlig å skrive u$_n$ heller enn $u(n)$, for verdien til $u$ i $n$, også omtalt som leddet til $u$ med indeks $n$.

*Eksempel 1.2* Man kan danne en følge av primtallene...<br>
&nbsp;&nbsp;&nbsp;&nbsp; Gitt en mengde $A$, et element $x\in A$ og en avbildning $f: A\to A$ kan vi ønske å danne en følge viss fire første ledd er: $$x,f(x),f(f(x)),f(f(f(x))),\cdots$$
Følgende teorem gir en presis tolkning av hva vi har i tankene, når vi skriver "..."

## Teorem 6.2
*La $A$ være en ikke-tom mengde. La $x\in A$ og la $f: A\to A$ være en avbildning. Da finnes det en og bare en følge $u : \mathbb{N} \to A$ slik at $u_0=x$ og $\forall n\in \mathbb{N}\quad u_{S(n)} = f(u_n)$*

### Addisjon
## Teorem 6.3 
*Det finnes en og bare en avbildning $+ : \mathbb{N}\times\mathbb{N}\to\mathbb{N}$ slik at:* $$m+0=m$$ $$m + S(n) = S(m + n)$$

## Teorem 6.4
*Regneregler for addisjon. Vi har, for alle $m, n, p \in N$*:
$$(m+n)+p=m+(n+p)$$
$$m+0=0+m=m$$
$$m + n = n + m$$
$$m + p = n + p \implies m = n$$