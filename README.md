# 1. Realne funkcije realne varijable

- **Definicija funkcije**: Funkcija je preslikavanje tipa $f: \: A  \to B$, pri čemu su $A$ i $B$ neprazni skupovi, a $a \in A$ i $b \in B$. Funkcija je specijalni oblik relacije koji elementu skupa $A$  pridružuje točno jedan element skupa $B$. Funkciju se označava kao $f(a) = b$. Skup $A$ se naziva domenom funkcije, a $B$ slikom odnosno kodomenom funkcije.

- **Zadavanje funkcije:** 
	1) Numerički (tablično)
	2) Algebarski (formulom)
	3) grafički (grafom)

- **Slika funkcije** je skup $\DeclareMathOperator{\Im}{Im} \Im f = {F(x): x \in A} \supseteq B$
 
- Funkcija čija su domena i kodomena podskupovi skupa realnih brojeva je **realna funkcija realne varijable** ($f: A \to B, \quad A, B \subseteq \mathbb{R}$).

- **Razlika između $f$ i $f(x)$:** $f$ je ime funkcije, a $f(x)$ je element $y$ iz kodomene koji odgovara elementu $x$ iz domene ($f(x) = y$). 

- **Uvjeti jednakosti funkcije:** (1) jednake domene i kodomene (2) jednako pravilo pridruživanja

- **Realna funkcija realne varijable:** funkcija čija su domena i kodomena podskupovi skupa $\mathbb R$. 

- **"Lijepe stvari vezane uz funkcije":** limesi, derivacije i integrali

- **Graf funkcije:** skup točaka ravnine $\Gamma_f = {(x, \; f(x)): \;x \in D_f}$ (opet, $y = f(x)$)

- **Klasifikacija RFRV:** 
	a) algebarske: racionalne (sve "normalne" osim korijena) i iracionalne (korijeni)
	b) transcendentne: eksponencijalne, logaritamske, trigonometrijske, ciklometrijske i druge

- **Algebarska funkcija**: koja ima konačan broj algebarskih operacija (uklj. korijen)

- **Algebarske operacije**: zbrajanje, oduzimanje, množenje, dijeljenje i potenciranje racionalnim brojem (razlomkom)

- **Racionalna funkcija**: kao algebarska, ali potenciranje samo cijelim brojem (nema korijena)

- **Cijela racionalna funkcija**, odnosno polinom n-tog stupnja je funkcija oblika $f(x) = a_n x^n + a{n-1} x^{n-1} + (...) + a_2 x^2 + a_1 x + a_0$ (s uvjetom da su $a_0, a_2, ..., a_{n-1}, a_n \in \mathbb{R}, \; n \in \mathbb{N}, \; a_n \neq 0$ - koeficijenti moraju biti realni da bude RFRV, a najveća  potencija ne smije imati koeficijent $0$, jer je onda to polinom $n-1$-tog stupnja!

- **Prava (razlomljena) racionalna funkcija:** kvocijent dvaju polinoma ($f(x) = \frac {P(x)} {Q(x)}, \; Q(x) \neq 0$

- **Homografska funkcija:** specijalni slučaj racionalne funkcije, oblik $f(x) = \frac {ax+b} {cx+d}$, s uvjetom da $x \neq - \frac d c$ 

## Pravila za računanje domena funkcija 
1) **racionalna funkcija**
	$f(x) = \frac {P(x)} {Q(x)}:\qquad Q(x) \neq 0$
2) **parni korijen**
	$f(x) = \sqrt[2k]{g(x)}: \qquad g(x) \geq 0$
3) **logaritamska funkcija:** 
	$f(x) = \log_a{g(x)}: \qquad g(x) > 0$
4) **ciklometrijske funkcije $\arcsin$ i $\arccos:$**
	$f(x) = \arcsin(g(x)): \qquad -1 \leq g(x) \leq 1$
	$f(x) = \arccos(g(x)): \qquad -1 \leq g(x) \leq 1$

- **Kompozicija funkcija ($f \circ x$):** 
 $$
g: \; A \to B \\
f: \; B \to C \\
f \cdot g : \; A \to C \\
g \circ f)(x) = g \Big(f(x) \Big)
$$

- **Identiteta:** 
$\id_A: \; A \to A, \quad \id_A(x) = x \\id_A \circ f = f$
 $\id_A \circ f = f$

	
-  **Uvjet komponiranja**: 
	- Za kompoziciju $f \circ g$, $Im_f \subseteq D_g$ ; 
	- U kompoziciji prvo djeluje *unutarnja* funkcija, a tek onda *vanjska* ($(f\circ g)(x) = f(g(x))$).

- **Što nam govori pravilo funkcije?:** Kako funkcija varijabli $x$ pridružuje pripadajući $y$.

- **Inverzna funkcija:** 

- **Dobivanje inverzne funkcije:** Umjesto $y = (\cdot\cdot\cdot)$ dobiti $x = (\cdot\cdot\cdot)$

- **Definicija inverzne funkcije:** Inverzna funkcija funkcije $f: \; D \to K$ je funkcija $f^{-1}: \; K \to D$ za koju vrijedi $f \circ f^{-1} = \id_K, \quad f^{-1} \circ f = \id_D$

- **Injektivnost:** svojstvo funkcije da ne postoje dva elementa u domeni koji imaju istu sliku u kodomeni $(\forall x_1, \: x_2 \in D, \; f(x_1) = f(x_2) \Rightarrow x_1 = x_2 \equiv \forall x_1 \: x_2 \in D, \; x_1 \neq x_2 \Rightarrow f(x_1) \neq f(x_2))$

- **Surjektivnost:** svojstvo funkcije da domenu preslikava u čitavo područje kodomene (nema "rupa" u kodomeni, svi elementi su "pogođeni"): $\forall y \in K, \; \exists n \in D, \; f(x) = y$

- **Bijektivnost:** i surjektivnost i injektivnost

- **TEOREM O INVERZNOJ FUNKCIJI:** Ako je funkcija $f$ bijekcija, tada ona ima inverz.

- **Grafovi međusobno inverznih funkcija**: simetrični s obzirom na pracac $y = x$.

- **Prirodna domena funkcija:** najveći skup $x$-eva za koje $f(x)$ ima smisla

## Pravila određivanja domena:

### $D_f = \mathbb{R}$
- polinom
- iracionalna funkcija s neparnim korijenom $f(x) ) \sqrt[2k+1]{x}$
- eksponencijalna funkcija $f(x) = a^x$
- $\sin$ i $\cos$

### Racionalna funkcija $f(x) = \frac {P(x)} {Q(x)}$
- $D_f: \;Q(x) \neq 0$

### Parni korijen $f(x) = \frac[2k]{g(x)}$
- $D_f: \; g(x) \geq 0$

### Logaritam $f(x) = \log(x)$
- $D_f: \; x > 0$

### Funkcije $\arcsin(x)$ i $\arccos(x)$
- $D_f: \; x \in [-1, \; 1]$

## Svojstva funkcija

- **Nultočka:** svaki $x$ za koji je $f(x) = 0$. Označava se s $x_0$.

- **Omeđenost odozgo:**  $\exists M \in \mathbb{R}, \; f(x) \leq M, \; \forall x \in D_f \qquad$ (u prijevodu, postoji vrijednost $M$ (iz skupa $\mathbb{R}$, ali to je manje bitno), pri čemu je $f(x)$ manji ili jednak tom $M$ za svaki x u domeni. $M$ se naziva gornjom međom funkcije.

- **Najmanja gornja međa:** Najmanja vrijednost za koju vrijedi da je gornja međa $(\forall M \in \mathbb{R}, \; f(x) \leq M, \; \forall x \in D_f, )$ ` dalje ne znam

- **Omeđenost odozgo:** $\exists m \in \mathbb{R}, \; f(x) \geq m, \; \forall x \in D_f$

- Najveća donja međa: najveća vrijednost za koju vrijedi da je donja međa funkcije $(dodati)$

- **Omeđena funkcija:** Funkcija koje je omeđena i odozdo i odozgo $\exists M \in \mathbb{R},  \; f(x) \leq M, \; \forall x \in D_f \wedge \exists m, \; f(x) \geq m, \; \forall x \in D_f$
- **Rastuća funkcija:** Funkcija raste na intervalu $I (\subseteq D_f)$  ako: $( \forall x_1, \: x_2 \in I ) \big(x_1 \leq x_2 \Rightarrow f(x_1) > f(x_2)\big)$

- **Strogo rastuća funkcija:** Funkcija strogo raste na intervalu $I (\subseteq D_f)$ ako: $(\forall x_1, \: x_2 \in I)\big(x1 < x_2 \Rightarrow f(x_1) < f(x_2)\big)$

- **Padajuća funkcija:** Funkcija pada na intervalu $I(\subseteq D_f)$ ako: $(\forall x_1, x_2 \in I)\big( x_1 < x_2 \Rightarrow f(x_2) < f(x_1) \big)$

- **Strogo padajuća funkcija:** Funkcija strogo pada na intervalu $I(\subseteq D_f)$ ako: $(\forall x_1, \: x_2) \big( x_1 < x_2 \Rightarrow f(x_2) < f(x_1)\big)$

- **Monotona funkcija:** Funkcija koja raste ili pada na cijelom području svoje domene

- **$\varepsilon$-okolina:** interval $\langle x_0 - \varepsilon, \; x_o - \varepsilon \rangle$ (je li krivo ako kažem samo $\langle x-\varepsilon, \, x+\varepsilon \rangle$?)

- **Lokalni maksimum:** Točka $x_M$ unutar okoline $O$ unutar koje vrijdi da je $x_M$ najveća vrijdnost koju funkcija unutar te okoline poprima $\big( f(x) \leq f(x_m), \forall x \in O \big)$

- **Strogi lokalni maksimum:** Točka $x_M$ za koju vrijdi da je jedina vrijednost unutar okoline $O$ u kojoj funkcija poprima maksimalnu vrijednost $\big( f(x) < f(x_M), \; \forall x \in O \setminus \{x_m\} \big)$

- **Lokalni minimum:** Točka $x_m$ unutar okoline $O$ za koju vrijdi da je $x_m$ najmanja vrijednost koju funkcija proprima unutar okoline $O$. $f(x) \geq f(x_m), \; \forall x \in O$

- **Strogi lokalni minimum:** Točka $točka $x_m$ unutar okoline $O$ za koju vrijedi da je $x_m$ najmanja vrijdnost koju funkcija poprima unutar okoline $O$. $\big( f(x) > x_m, \; \forall x \in O \setminus x_m \big)$

- **Lokalni ekstremi:** i minimumi i maksimumi

- **Periodičnost:** svojstvo funkcije da ponavlja svoje preslikavanje na predvidiv način unutar svoje domene nakon perioda $T$. Najmanji period funkcije je osnovni period, $T_0$ (period je i svaki višekratnik temeljnog $T_0$). 
$$\exists T \in \mathbb{R} \setminus \{ 0\}, \; f(x+T) = f(x), \; \forall x \in D_f$$

- **Parnost:** svojstvo funkcije da "briše" minus. Graf parne funkcije osnosimetričan s obzirom na os $y$. 
$$x \in D_f \Rightarrow -x \in D_f, \; f(-x) = f(x), \; \forall x \in D_f$$

- **Neparnost:** svojstvo funkcije da "izlučuje" minus. Graf neparne funkcije je centralnosimetričan s obzirom na ishodište. Formalno: $x \in D_f \Rightarrow -x \in D_f, \; f(-x) = -f(x), \; \forall x \in D_f$

- **Parne i neparne elementarne funkcije:
	- **Parne:** $x^{2k}, \; \cos(x),\; |x|$
	- **Neparne:** $x^{2k-1}, \; \sin(x), \; \tan(x), \; \cot(x)$
### Eksponencijalna funkcija
- **Oblik:** $f \to \langle 0, \, \infty \rangle, \; f(x) = a^x, \;\; a > 0, \; a \neq 1$
- **Svojstva:**
	- $a^0 = 1$
	- $a^x > 0$
	- HA: $x = 0$

	- za $a > 1$ funkcija strogo raste na čitavoj domeni - formalno $x < y \Leftrightarrow a^x < a^y$
	- za $a \in [0, \, 1]$ funkcija strogo pada na čitavoj domeni - formalno $x < y \Leftrightarrow a^x < a^y$
- Svojstva računanja s potencijama (podsjetnik): 
	- $a^x \cdot a^y = a^{x+y}$
	- $\frac {a^x} {a^y} = a^{x-y}$
	- ${(a^x)}^y = a^{xy}$
#### Posebni oblici eksponencijalne funkcije
- Funkcija prirodnog eksponencijalnog rasta: $y(x) = y_0\cdot e^{kx}$

- Funkcija prirodnog eksponencijalnog rasta: $y(x) = y_0\cdot e^{-kx}$

- Krivulja učenja: $a(t) = B - A\cdot e^{-kt}$ - modelira učenje

- Logistička krivulja: $q(t) = \frac {B} {1 + A \cdot e^{-Bkt}}$ - modelira epidemije i tračeve

### Logaritamska funkcija
- $f: \langle 0, \, \infty \rangle \to \mathbb{R}, \; f(x) = \log_a{x}$
- inverz eksponencijalne funckije $g(x): \: \mathbb{R} \to \langle 0, \, \infty,  \rangle \;\; f(x) = a^x$
- Svojstva logaritamske funkcije:
	- za $a > 1$ funkcija strogo raste na čitavoj domeni
	- za $a \in [0, \,1]$ funkcija strogo pada na čitavoj domeni
	
#### Svojstva logaritama: 
	$$
	\begin{gather}

	\log_a(b) = c\Leftrightarrow a^c = b \\\\
	a^{\log_a(x)} = x \\\\
	\log_a(a^x) = x  \\\\
	\log_a(a^x) = x \\\\
	\log_a(0) = N.R. \\\\
	\log_a(a) = 1 \\\\
	a^{log_a(x)} = x \\\\
	\log_a(xy) = log_a(x) + log_a(y) \\\\
	log_a(\frac {x} {y}) = log_a(x) - log_a(y) \\\\
	 \log_a(x^p) = p \cdot \log_a(x) \\\\
	 log_a(b) = \frac {1} {\log_b(a)} \\
	\end{gather}$$
	
	
### Trigonometrijske funkcije:
#### TRIGONOMETRIJSKI INDENTITETI
$$
\begin{gather}
\sin^2(x) + \cos^2(x) = 1 \\\\
\tan(x) \cdot \cot(x) = 1 \\\\
\sin(2x) = 2\sin(x)\cos(x) \\\\
\cos(2x) = \cos^2(x) - \sin^2(x) \\\\
sin(x \pm y) = \sin(x) \cos(y) \pm \cos(x) \sin(y) \\\\
\cos(x \pm y) = \cos(x) \cos(y) \mp \sin(x) \sin(y) \\\\
\cos(x \pm y) = \cos(x) \cos(y) \mp \sin(x) \sin(y) \\
\end{gather}
$$
	
#### Sinus
- oblik $f: \: \mathbb{R} \to [-1, \, 1], \quad f(x) = \sin(x)$
- omeđen: $\sin(x) \in [-1, \, 1]$
- neparan: $\sin (-x) = -\sin(x)$
- periodičan: $TP = 2 \pi$

#### Kosinus
- oblik: $f: \: \mathbb{R} \to [-1, \, 1], \quad f(x) = \cos(x)$
- omeđen: $\cos(x) \in [-1, \, 1]$
- paran: $\cos(-x) = cos(x)$
- periodičan: $TP = 2 \pi$

# TBA - str. 147-203

# NASTAVAK

## Transformacije grafa
- $f(x) +c$ - pomak gore/dolje
- $f(x+c)$ - pomak lijevo/desno (ne desno/lijevo!)
- $f(-x)$ - nemam pojma
- $-f(x)$ - nemam pojma

# 2. Nizovi

- **Definicija niza:** specijalna vrsta funkcije, čija je domena skup $\mathbb{N}$ (službeno "Niz u skupu $S$ je funkcija $a: \: \mathbb{N} \to S$")
- **Definicija niza realnih brojeva:** funkcija $a: \: \mathbb{N} \to \mathbb {R}$

- **Fibbonacijev niz:** Niz zadan rekurzivno kao zbroj prethodna dva člana niza. Prva dva člana niza trebaju se zadati kao sidreni uvjeti

- **Aritmetički niz:** niz kod kojeg je razlika ($d$) među članovima konstantna 
 $$\forall n \in \mathbb {N}, \,a_{n+1} - a = d$$


- **Opći član aritmetičkog niza:** 
$$
\begin{align}
a_n & = a_{n-1} + d \\\\
a_n & = a_1 + d (n-1) 
\end{align}$$


- **Suma prvih n članova aritmetičkog niza:** 
$$
\begin{align}
S_n & = \frac {n \cdot (a_1 + a_n)} {2} \\\\
S_n & = \frac {n \cdot (2 a_1 + (n-1) \cdot d)} {2}
\end{align}
$$

- **Geometrijski niz:** niz kod kojeg je kvocijent ($q$) među članovima jednak 
$$\forall n \in \mathbb{N}, \frac {a_{n+1}} {a_n} = q$$

- **Opći član geometrijskog niza**
$$a_n = a_{n-1} \cdot q = a_1 \cdot q^{n-1}$$

- **Suma prvih n članova geometrijskog niza**
$$S_n = \frac {a_1 \cdot q^n -1} {q-1}$$

## Svojstva nizeva
- **Rast:** $a_n \leq a_{n+1} , \quad \forall n \in \mathbb{N}$
- **Strogi rast:** $a_n < a_{n+1},  \quad \forall n \in \mathbb{N}$
- **Pad:** $a_n \geq a_{n+1}, \quad \forall n \in \mathbb{N}$
- **Strogi pad:** $a_n > a_{n+1}, \quad \forall n \in \mathbb{N}$

- **Aritmetički niz:**
	- $d>0 \Rightarrow$ strog rast
	- $d < 0 \Rightarrow$ strog pad
- **Geometrijski niz:**
	- $a_1 > 0, \, q > 1 \Rightarrow$ strog rast
	- $a_1 > 0, \, q \in [-1, \, 1] \Rightarrow$ strog pad
	- $a_1 < 0, \, q > 1 \Rightarrow$ strog pad
	- - $a_1 < 0, \, q \in [-1, \, 1] \Rightarrow$ strog pad
	- $q < 0 \Rightarrow$ niz nije monoton

## Gomilište i limes niza
- **Tri vrste nizovi s obzirom na gomilište**
	- nizovi koji teže nekoj vrijednosti
	- nizovi koji teže u $\pm \infty$
	- nizovi koji nisu monotoni niti ne teže u neku vrijednost

- **==!==** **Niz teži u $+\infty$ ako:** 
$$\forall M \in \mathbb{R}, \, \exists n_0 \in \mathbb{N}, \, a_n > M, \, \forall n > n_0 \Rightarrow \lim_{n \to \infty} (a_n) = \infty$$
- **==!==** **Niz teži u $- \infty$ ako:** 
$$\forall m \in \mathbb{R}, \, \exists n_0 \in \mathbb{N}, \, a_n < m, \forall n > n_0 \rightarrow \lim_{n \to \infty} (a_n) = -\infty$$

- **Divergentni nizovi:** nizovi koji teže u $\pm \infty$ 

- **$\varepsilon$-okolina** (broja) $x_0$: $$\textsf{interval } \langle x_0 - \varepsilon, x_0 + \varepsilon \rangle, \; O(x_0, \; \varepsilon = \langle x_0 - \varepsilon, \, x_0 + \varepsilon \rangle) = \{ x \in \mathbb{R}: \: |x_0 - x| < \varepsilon\}$$

- **Definicija gomilišta niza:**  $a$ je gomilište niza ako se u svakoj $\varepsilon$-okolini  broja $a$ nalazi beskonačno mnogo članova niza

- **Intuitivna definicija limesa:** $L$ je limes niza ako se u svakoj okolini broja $L$ nalazi beskonačno mnogo članova niza, a izvan okolina $L$ samo konačno mnogo. Oznaka: $\lim_n \to \infty (a_n) = L$
$$\textsf{u okolini } \infty \textsf{ članova, izvan } \cancel{\infty} \Rightarrow \textsf{limes}$$


- **Konvergentni niz:** niz koji teži nekoj vrijednosti (dakle ima i limes)

- **STROGA MATEMATIČKA DEFNICIJA LIMESA NIZA:** 
$$ 
\begin{align*}
L \in \mathbb{R} \textsf{ je granična vrijdnost (limes) niza } a_n \textsf{ ako } \\\\
\forall \varepsilon > 0, \, \exists n_0 \in \mathbb{N}, \, \forall n \: \big(n > n_0 \: \Rightarrow \: |a_n - L| < \varepsilon \big)
\end{align*}
$$  

- **Divergentni nizovi u širem smislu:** 
$$
\begin{align*}
\textsf{koji:} & \textsf{ a) ne konvergiraju} \\
& \textsf{ b) imaju više gomilišta}
\end{align*}$$

- **TEOREM 1 (BOLZANO-WEIERSTRASS):** Svaki omeđen niz realnih brojeva ima barem jedno gomilište
$$\textsf{omeđen niz} \Rightarrow \textsf{barem jedno gomilište}$$

- **TEOREM 2:** Svaki monoton i omeđen niz realnih brojeva ima limes
$$\textsf{niz monoton i momeđen} \Rightarrow \textsf{limes}$$

- **Izvorna definicija broja $e$:** $e = \lim_{n \to \infty} \Big( 1 + \frac {1} {n}\Big)^n$

- **Limes eksponencijalne funkcije (slučajevi):** $f(x)=\begin{cases}\infty,& q>1\\[5pt] 1,& q = 1\\[5pt] 0,& q \in \langle -1, \, 1\rangle\\[5pt]\text{ne postoji},& q \leq -1\end{cases}$

- **TEOREM 3:** Pravila računanja limesa
$$
\begin{gather}
\lim_{n \to \infty} (k) = k \\\\
\lim_{n \to \infty} (a_n \pm b_n) = \lim_{n \to \infty}(a) \pm \lim_{n \to \infty}(b) \\\\
\lim_{n \to \infty} (k\cdot a_n) = k\cdot \lim_{n \to \infty}(a) \\\\
\lim_{n \to \infty} (a_n \cdot b_n) = \lim_{n \to \infty}(a) \cdot \lim_{n \to \infty}(b) \\\\
\lim_{n \to \infty} \Big(\frac {a_n}{b_n}\Big) = \frac{\lim_{n \to \infty}(a)}{\lim_{n \to \infty}(b)} \\\\
\lim_{n \to \infty} (a_n^m) = \lim_{n \to \infty}(a)^m \\
\end{gather}
$$

- **Monotonost limesa:** $$a_n \leq b_n, \, \forall n \in \mathbb{N} \Rightarrow \lim_{n \to \infty}(a_n) \leq lim_{n \to \infty} (b_n)$$
- **Redovi veličine(?): ==! provjeriti==** 
 $$ \log_n(a) << a^n << n^a << n! $$
	$$
	\begin{gather}
	\lim_{n \to \infty} \frac {n^p} {a^n} = 0 \\\\
	\lim_{n \to \infty} \frac {\log_a(n)} {n^p} = 0
	\end{gather}$$


- **Važniji limesi niza 1:**
	$$
	\begin{gather}
	\lim_{n \to \infty} \big( \frac {1} {n} \big) = 0 \\\\
	\lim_{n \to \infty} \sqrt[n]{n} = 1 \\\\
	\lim_{n \to \infty} q^n = 0 \\\\
	\lim_{n \to \infty} (1+ \frac 1 n)^n = e \\
\end{gather}$$

- **Konvergencija podniza:** svaki podniz konvergentnog niza također konvergira u istu vrijednost

### Geometrijski red 
- **Defincija reda:** Red je uređeni par $\big((a_n), \, (b_n)\big)$ niza $a_n$ i njemu pripadnog niza parcijalnih suma ($b_n$)

- **Suma reda:** limes niza parcijalnih suma
$$\sum_{n-1}^{\infty}a_n = \lim_{n \to \infty} (s_n)$$
==!  definiciji je red $b_n$, a u sumi je postao $s_n$   ==

- **Propozicija 9 - Nužan uvjet konvergencije reda:** Ako red $\big((a_n), \, (b_n) \big)$ konvergira, onda je $\lim_{n \to \infty} (a_n) = 0$

- **Korolar 2:** Ako $\lim_{n \to \infty} (a_n) \neq 0$, tada red $\sum_{n = 1}^{\infty} (a_n)$ divergira

- **Geometrijski red:** Red $\big((a_n), \, (s_n)\big)$ je geometrijski red ako je $a_n$ geometrijski niz

# Limes funkcije
- limes = osnova za derivacije i integrale

- **INTUITIVNA DEFINICIJA LIMESA FUNKCIJE:** Ako $f(x)$ teži u $L$ kada $x$ teži u $c$ na bilo koji način možemo reći ca le $L$ limes $f(x)$ kada $x$ teži u $c$, odn. formalno $\lim_{x \to c} f(x) = L$ `|| ovo je sve nekako napisano u krug, kako to pojednostaviti ?`
$$f(x) \to L \textsf{ kada } x \to c \textsf{ "na bilo koji način" } \Rightarrow
L = \lim_{x \to c} f(x)$$

- **HEINEOVA DEFINICIJA LIMESA FUNKCIJE:** $L \in \mathbb{R}$ je limes funkcije $f$ u točki $f(x) = c$ ako za svaki niz $a_n$ takav da je $\lim_{n \to \infty} (a_n) = c$, tada $\lim_{n \to \infty} \big( f(a_n) \big) = L$
$$\forall a_n, \,\lim_{n \to \infty} (a_n) = c \Rightarrow  $$

- **HEINEOVA DEFINICIJA LIMESA FUNKCIJE SLIJEVA:** $L \in \mathbb{R}$ je limes funkcije $f$ u točki $x = c$ ako za svaki niz (a_n) za koji je $a_n < c, \, \forall n \wedge \lim_{n \to \infty} (a_n) = c$, tada $lim_{n \to \infty} f(a_n) = L$ `|| pitanje: ako je ovdje riječ o limesu slijeva, zažto nije lim_{n \to \infty^+} ? Mislim, nema smisla izraz \infty^+, ali mi niti nema smisla da limes slijeva/zdesna postoji ako nema onog plusića/minusića u eksponentu, pogotovo jer se kod limesa zdesna ne javlja -\infty, npr.`

- **HEINEOVA DEFINICIJA LIMESA FUNKCIJE ZDESNA:** $L \in \mathbb{R}$ je limes zdesna funkcije $f$ u točki $x = c$ ako za svaki niz $(a_n)$ za koji vrijedi $a_n > c, \, \forall n \, \wedge \, \lim_{n \to \infty} (a_n) = c$, tada $\lim_{n \to \infty} f(a_n) = L$

- **CAUCHYJEVA DEFINICIJA LIMESA FUNKCIJE:** $L \in \mathbb{R}$ je limes funkcije $f$ u točki $x = c$ ako $\forall \varepsilon > 0 \exists \delta > 0$ *"tako da vrijedi"* $0 < |x-c| < \delta \Rightarrow |f(x) - L| < \varepsilon$

- **NUŽAN I DOVOLJAN UVJET ZA POSTOJANJE LIMESA FUNKCIJE:** $\lim_{x \to c} f(x) = L \Leftrightarrow \lim_{x \to c^-} (f(x)) = \lim_{x \to c^+} (f(x)) = L$

- **TEOREM O SENDVIČU:** Ako postoji pozitivni broj $p$ za koji vrijedi $f(x) \leq g(x) \leq h(x), \;$  $\forall x \in \mathbb{R}, \; 0 < |x-c| < p$ i ako je $\lim_{x \to c} (f(x)) = \lim_{x \to c} (h(x)) = L$, tada je i $\lim_{x \to c} (g(x) = L$

- **Važniji limesi 2:** 
	-  $\lim_{x \to \infty} \big( \frac {1} {x}\big) = 0$
	- $\lim_{x \to \infty} (q^x) = 0$
	- $\lim_{x \to \infty} (1 + \frac {1}{x})^x = e$
	- $\lim_{x \to 0} (1+x)^{\frac {1} {x}} = e$
	- $\lim_{x \to 0} \Big(\frac {\ln(x+1)} {x}\Big) = 1$
	- $\lim_{x \to 0} \Big( \frac {a^x -1} {x} \Big) = \ln (a)$
	- $\lim_{x \to 0} \Big( \frac {sin(x)} {x} \Big) = 1$

- **Neodređeni izrazi (7):** $\frac {0}{0}, \; \frac {\infty} {\infty}, \; 0 \cdot \infty, \; \infty - \infty, \; 1^{\infty}, \; \infty^0, \; 0^0$

### Neprekidnost

- **Definicija neprekidne funkcije u točki:** Funkcija $f$ je neprekinna u točki $c \in D_f$ ako $\lim_{x \to c} (f(x)) = f(c)$

- **Limes funkcije u točki:** $L$ je limes funkcije $f$ u točki $x = c$ ako $\forall \varepsilon > 0, \, \exists \delta > o, \, 0 < |x-c| < \delta < \Rightarrow |f(x) -L| < \varepsilon$

- **Neprekidnost funkcije u točki:** Funkcija $f$ je neprekidna u točki $x = c$ ako $\forall \varepsilon > 0, \, \exists \delta > 0, \, |x-c| < \delta \Rightarrow |f(x) - f(c)| < \varepsilon$

- **Neprekidnost funkcije u točki 2:** Funkcija $f$ je neprekidna u točki $x = c$ akko vrijedi $\lim_{\Delta x \ to 0} \big( \Delta f(c) \big) = 0$

- **Neprekidnost funkcije na intervalu:** Funkcija je neprekidna na intercalu ako je neprekidna u svakoj točki tog intervala

- **Prekid u točki:** Funkcija $f$ ima prekid prve vrste u točki $x = c$ ako u noj postoje konačni limesi $L_1 = \lim_{x \to c^-} \big( f(x) \big), \quad L_2 = \lim_{x \to c^+} \big( f(x) \big)$. Ako su $L_1 = L_2 = f(x)$, funkcija nema prekid u točki $x = c$. Ako su $L_1 = L_2 \neq f(x)$, funkcija ima uklonjiv prekid u točki $x = c$. Ako su $L_1 \neq L_2$, funkcija ima neuklonjiv prekid orve vrste u točki $x = c$.

- **Prekid druge vrste:** Ako $c$ nije izolirana funkcija iz domene funkcije $f$, funkcija $f$ ima prekid druge vrste u točki $x = c$ ako barem jedan od limesa $\lim_{x \to c^-} \big( f(x) \big), \quad \lim_{x \to c^+} \big( f(x) \big)$ ne postoji.

### Asimptote

- Asimptota je pravac $y = kx+l$ ako točka $T$ funkcije po jednoj koordinati teži u $\pm \infty$, a po drugoj teži k pravcu $y = kx+l$

- **VA:** $x = c$ je vertikalna asimptota funkcije $f$ ako $\lim_{x \to c^-} \big( f(x) \big) = \pm \infty$ ili $\lim_{x \to c^+} \big( f(x) \big) = \pm \infty$

- **HA:** $y= l$ je desna HA funkcije $f$ ako je $l = \lim_{x \to \infty} \big( f(x) \big)$. Alternativno, ako je $l = \lim_{x \to -\infty} \big( f(x) \big)$, tada je $y = l$ lijeva HA funkcije $f$.

- **KA:** $y = kx + l$ je desna KA funkcije $f$ ako $\lim_{x \to \infty} \big( f(x) -kx - l\big) = 0$. Ako $l =\lim_{x \to -\infty} \big( f(x) -kx\big) = 0$, onda je $y = kx +l$ lijeva KA funkcije.


## Derivacija funkcije

- **GEOMETRIJSKA INTERPRETACIJA DERIVACIJE:** Derivacija funkcije $f$ u točki $x_0$ predstavlja koeficijent smjera tangente na graf funkcije $f$ u toj točki $\big( x_0, f(x_0) \big)$.

- **DEFINICIJA DERIVACIJE U TOČKI:** Derivacija funkcije $f$ u točki $x_0$ je $f'(x_0) = \lim_{\Delta x \to 0} \Big( \frac {f(x_0 + \Delta x)- f(x_0)} {\Delta x} \Big)$, pod uvjetom da dani limes postoji.

- **Derivabilna funkcija:** Funkcija $f$ je derivabilna/diferencijabilna na intervalu $\langle a, \, b \rangle$ ako ima derivaciju u svakoj točki tog intervala, a $f'$ definiana na tom intervalu je derivacija funkcije $f$.

- **DEFINICIJA DERIVACIJE FINKCIJE:** Derivacija funkcije $f$ je funkcija $f'$ definirana kao $f'(x) = \lim_{\Delta x \to 0} \Big( \frac {f(x + \Delta x) - f(x)} {\Delta x}\Big)$, pod uvjetom da dani limes postoji.

- **DERIVACIJA PRAVILA DERIVACIJE** - vjerojatno će biti barem jedno pitanje - probati svaku jednom

- **Pravilo o derivaciji kompozicije/ulančanom deriviranju (chain rule):** $\Big(f\big(g(x)\big)\Big)' = f'\big(g(x)\big)g'(x)$

- **Derivacija inverza:** $\big( f^{-1}\big)'(y) = \frac {1} {f'(x)}$

- **Derivacije višeg reda:** Derivacije višeg reda određuju se induktivno, tj. $y^{(n)} = \Big( y^{(n-1)} \Big)'$

- **Diferencijal funkcije:** izraz $f'(x)\Delta x$, oznaka $df$ `dodati`

- **L'Hospitalovo pravilo:** Ako limes funkcije $f = \frac g h$ poprimi oblik $\frac 0 0$ i $\frac \infty \infty$, on će biti istovjetan limesu $\frac {g'} {h'}$. 

## Primjena derivacija

- **Tangenta:** pravac koji dodiruje krivulju ($f$) u samo jednoj točki ($x_0$), jednadžbe $y - y_0 = f'(x_0)(x-x_0)$

- **Normala:** pravac koji siječe tangentu funkcije $f$ u točki $x_0$ pod pravim kutem, jednadžbe $y - y_0 = - \frac{1}{f'(x_0)}(x - x_0)$

- **Kut između krivulja:** kut pod kojim se sijeku tangente krivulja u točki sjecišta krivulja, formula: $\tan (\phi) = \Big|\frac {f'(x_0) - g'(x_0)} {1 + f'(x_0) g'(x_0)}\Big|$

- **Monotonost funkcije (teoremi 8 i 9):** Ako je $f: \: \langle a, \, b \rangle \to \mathbb{R}$ diferencijabilna funkcija i:
	- $f'(x) < 0 \quad \forall x \in \langle a, \, b \rangle$, $f$ strogo raste na int. $\langle a, \, b \rangle$
	- $f'(x) > 0 \quad \forall x \in \langle a, \, b \rangle$, $f$ strogo pada na int. $\langle a, \, b \rangle$

- **FERMATOV TEOREM (teorem 9):** Ako je funkcija $f: \: \langle a, \, b \rangle \to \mathbb{R}$ u točki $c$ diferencijabilna i u njoj ima lokalni ekstrem, tada je vrijednost $f'(c) = 0$.

- **Definicija stacionarne točke:** Stacionarna točka funkcije $f$ je točka u kojoj derivacija funkcije $f$ ($f'$) poprima vrijednost 0. Stacionarne točke su točke infleksije i ekstremi.

- **Određivanje ekstrema preko prve derivacije:** Stacionarna točka $T$ derivabilne funkcije je lokalni ekstrem akko postoji okolina točke takva da se u toj okolini predznak prve derivacije ljevo od $T$ razlikuje od predznaka desno od točke $T$.

- **Određivanje ekstrema preko druge derivacije:**
	- Ako je $f'(c) = 0$ i $f''(c) > 0$, funkcija $f$ u točki $c$ ima lokalni minimum
	- Ako je $f'(c) = 0$ i $f''(c) < 0, funkcija $f$ u točki $c$ ima lokalni maksimum
	- Kao je $f'(c) = 0$ i $f''(c) = 0$, tada ne možemo odrediti ekstrem putem druge derivacije

- **Definicija konveksnosti:** Neprekidna funkcija $f: \: I \to \mathbb{R}$ je konveksna na intervalu $I \subseteq \mathbb{R}$ ako za svaki $a, \, b \in I$ vrijedi $f(\frac {a+b} {2}) \leq \frac {f(a) + f(b)} {2}$. Ako je u pitanju stroga nejednakost, tada je i funkcija strogo konveksna (oblik U)

- **Definicija konavnosti:** Neprekidna funkcija $f: \: I \to \mathbb{R}$ je konkavna na intervalu $I \subseteq \mathbb{R}$ ako za svaki $a, \, b \in I$ vrijedi $f(\frac {a+b} {2}) \geq \frac {f(a)+f(b)} {2}$. Ako je u pitanju stroga nejednakost, funkcija je strogo konkavna (oblik naopako U)

- **Teoremi 10 i 11:** Dva puta derivabilna funkcija $f: I \:  \to \mathbb{R}$ na intervalu $I$ je:
	- konveksna na $I$ akko je $f''(x) \geq 0 \;\; \forall x \in I$
	- konkavna na $I$ akko je $f''(x) \leq 0 \;\; \forall x \in I$

- **Točka infleksije:** točka u kojoj funkcija prelazi iz konveksnosti u konkavnost ili obratno.

- **Nužan uvjet točke infleksije (teorem 12):** Ako je $f: \: I \to \mathbb{R}$ funkcija koja ima neprekidnu drugu derivaciju u točki $c \in I$ i ako je $c$ točka infleksije funkcije $f$, tada je $f''(c) = 0$.

- **Dovoljan uvjet točke infleksije (teorem 13):** Ako je $f: \: I \to \mathbb{R}$ dva puta derivabilna funkcija i ako je $f''(c) = 0$, $c$ je točka infleksije funkcije $f$ ako druga derivacija pri prijelazu kroz točku $c$ mijenja predznak.

- **Teorem 14 (razrješenje slučaja $f'(c) = f''(c) = 0$):** Ako funkcija $f$ u točki $c$ ima derivacije do reda $n \in \mathbb{N}$, ako je takva $n-$ta derivacija u točki $c$ neprekidna i ako su sve prethodne derivacije funkcije $f$ u točki $c$ poprimile vrijednost $0$, a $n$-ta derivacija je poprimila vrijednost različitu od 0, tada je točka $c$:
	-  lokalni ekstrem funkcije $f$ ako je $n$ paran broj (minimum ako je $f^{(n)}(c) > 0$ odnosno maksimum ako je $f^{(n)}(c) < 0$)
	-  točka infleksije funkcije $f$ ako je $n$ neparan broj.

- **Definicija asimptote:** Neka se točka $T$ neprekinuto giba po grafu funkcije $f$ tako da barem jedna od njezinih koordinata teži u $\pm \infty$. Ako pritom udaljenost točke $T$ od pravca $y = kx+l$ teži k nuli tada je taj pracac asimptota te funkcije.

- **Tok funkcije:**
	1. Domena (vertikalne asimptote!) 
	2. Nultočke 
	3. Svojstva: parnost/neparnost, periodičnost, ... 
	4. $f'$ (stac. točke i intervali rasta/pada)
	5. $f''$ (konv./konk., točke infleksije)
	6. Asimptote (HA, VA, KA)
	7. Skica grafa
	- NAPOMENA: posebnu pašnju posvetiti **kritičnim točkama** (mogu biti stac. točke - tangenta paralelna s osi $x$ ili točke u kojima funkcija nije definirana - tangenta je vertikalna ili ne postoji )

#### 4 teorema o srednjoj vrijednosti

- **FERMATOV TEOREM:** Ako je funkcija $f$ definirana na otvorenom intervalu i ima ekstrem u točki $x_0$ unutar tog intervala i ako postoji $f'(x_0)$, tada je $f'(x_0) = 0$

- **LAGRANGEOV TEOREM:** Ako je funkcija $f$ diferencijabilna na  intervalu $\langle a, \, b \rangle$ i neprekdina na intervalu $[a, \, b]$, tada postoji jedna vrijednost $c \in \langle a, \, b \rangle$ za koji vrijedi $f'(c) = \frac {f(b) - f(a) }  {b-a}  \equiv f(b) - f(a) = (b-a) \cdot f'(c)$

- **ROLLEOV TEOREM:** Ako je funkcija $f$ derivabilna na $\langle a, \, b \rangle$ i neprekidna na $[a, \, b]$ i ako je $f(a) = f(b)$, tada postoji jedna vrijednost $c \in \langle a, \, b \rangle$ takva da $f'(c) = 0$.

- **CAUCHYJEV TEOREM SREDNJE VRIJEDNOSTI:** Ako su $f$ i $g$ derivabilne funkcije na $\langle a, \, b \rangle$ i neprekidne na $[a, \, b]$ i ako je $g'(x) \neq 0$ na $\langle a, \, b \rangle$, tada postoji $c$ $\in \langle a, \, b \rangle$ za koji vrijedi $\frac {f'(c)} {g'(c)} = \frac {f(b) - f(a)} {g(b) - g(a)}$.

# Integrali

- **Definicija primitivne funkcije:** $F$ je primitivna funkcija (antiderivacija) funkcije $f$ na intervalu $\langle a, \, b \rangle$ ako vrijedi $F'(x) = f(x), \; \forall x \in \langle a, \, b \rangle$.

- **Definicija neodređenog integrala:** Skup svih primitivnih funkcija funkcije $F$ dane funkcije $f$ je neodređeni integral funkcije $f$ i označava se sa $\int f(x) dx = \{ F+c: \: c \in \mathbb{R}\}$ ili kraće $\int f(x) dx = F + c$

- **Metode integriranja:** neposredno, supstitucija, parcijalna integracija, integriranje racionalnih funkcija i integriranje trigonometrijskih funkcija.

- **3 svojstva integrala:** 
	- **Aditivnost** - rastavimo li integral na dva intervala možemo ih opet zbrojiti 
		- $\int_a^b f(x) dx = \int_a^c f(x) dx + \int_c^b f(x) dx$ 
	- **Integral negativne funkcije** - iako je površina izričito pozitivna veličina, zbog prirode računanja integrala površina ispod osi $x$ ispadne "negativna"
	- **Linearnost** - isto ko aditivnost samo za množenje: 
		- $\int c \cdot f(x) dx = c \int f(x) dx$ 
		- $\int f(x) + g(x) = \int f(x) dx + \int g(x) dx$

- **Integralne sume:** 
	- donja: $s_n = \sum_{i = 1}^n \big( m_i \Delta x_i \big)$
	- gornja: $S_n = \sum_{i = 1}^n \big(M_i \Delta x_i)$

- **Definicija određenog integrala:** Zajednički limes gornje i donje integralne sume funkcije $f: \: [a, \, b] \to \mathbb{R}$ je određen integral funkcije $f$, a označava se s $I = \int_a^b f(x) dx$ i on je jednak površini ispod grafa funkcije $f$ na intervalu $[a, \, b]$.

- **Newton-Leibnizova formula:** daje vezu određenog integrala i primitivne funkcije podintegralne funkcije. Formula: $\int_a^b f(x) dx = F(b) -F(a) = F(x)\Big|_a^b$  






