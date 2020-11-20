Vecteurs {#vecteurs .unnumbered}
========

Translations - Vecteurs associés
--------------------------------

Une télécabine se déplace le long d’un câble de A vers B :\

\(A) at (3,5); (B) at (9,7); [(A) node\[above\] [$A$]{}; (A) node
[$\times$]{};]{}; [(B) node\[above\] [$B$]{}; (B) node [$\times$]{};]{};
(0,0) grid (12,8); (0,4) – (12,8); (3,5) – (3,4) – (4,4) – (4,1) – (2,1)
– (2,4) – (3,4);

\
Dessiner ci-dessus la télécabine lorsqu’elle sera arrivée au terminus
B.\
On appelle ce déplacement une $\dots\dots\dots\dots\dots$ de A vers B.\

\(A) at (3,5); (B) at (9,7); [(A) node\[above\] [$A$]{}; (A) node
[$\times$]{};]{}; [(B) node\[above\] [$B$]{}; (B) node [$\times$]{};]{};
(0,0) grid (12,8); (0,4) – (12,8); (3,5) – (3,4) – (4,4) – (4,1) – (2,1)
– (2,4) – (3,4); (9,7) – (9,6) – (10,6) – (10,3) – (8,3) – (8,6) –
(9,6); (A)–(B); (2,4)–(8,6); (4,4)–(10,6); (4,1)–(10,3); (2,1)–(8,3);

\
Déplacer une figure par [****]{}, c’est faire glisser cette figure sans
la faire tourner. Pour décrire ce déplacement, il faut donc donner la
[****]{}, le [****]{} et la [****]{} de ce parcours. Pour cela, on va
utiliser un nouvel outil mathématique : [****]{}. Sur la figure,

Soit $A$ et $B$ deux points du plan.\
On appelle [****]{} la transformation qui, à tout point $M$ du plan,
associe l’unique point $M'$ tel que $[ AM' ]$ et $[ BM ]$ ont même
milieu.

(0,0) grid (11,8); (A) at (1,1); (B) at (3,5); (M) at (7,2); (N) at
(9,6); (F) at (10.6, 7); (A)–(N); (B)–(M); (A)–(B); (M)–(N); [(A)
node\[below left\] [$A$]{};]{} [(B) node\[above left\] [$B$]{};]{} [(M)
node\[below right\] [$M$]{};]{} [(N) node\[above\] [$M'$]{};]{} (3,2.25)
node\[rotate=122, color=F1\] [[$\approx$]{}]{}; (7,4.75)
node\[rotate=122, color=F1\] [[$\approx$]{}]{}; (4,4.25)
node\[rotate=53, color=C1\] [[$\infty$]{}]{}; (6,2.75) node\[rotate=53,
color=C1\] [[$\infty$]{}]{};

-   Le point $M'$ est appelé [****]{} du point $M$.

-   On dit également que $M$ est le [****]{} de $M'$.

Une **transformation** sert à **modéliser** mathématiquement un
mouvement.

-   La **symétrie centrale** est la transformation qui modélise le
    demi-tour.

-   La **translation** est la transformation qui modélise le glissement
    rectiligne. Pour la définir, on indique la direction, le sens et la
    longueur du mouvement.

On considère quatre points $A$, $B$, $C$ et $D$.\
La translation qui transforme $A$ en $B$ transforme $C$ en $D$, si et
seulement si $ABDC$ est un [****]{} (éventuellement aplati).

(0,0) grid (11,8); (A) at (1,1); (B) at (3,5); (M) at (7,2); (N) at
(9,6); (F) at (10.6, 7); (A)–(N); (B)–(M); (A)–(B); (M)–(N); (B)–(N);
(A)–(M); [(A) node\[below left\] [$A$]{};]{} [(B) node\[above left\]
[$B$]{};]{} [(M) node\[below right\] [$C$]{};]{} [(N) node\[above\]
[$D$]{};]{} (3,2.25) node\[rotate=122, color=F1\] [[$\approx$]{}]{};
(7,4.75) node\[rotate=122, color=F1\] [[$\approx$]{}]{}; (4,4.25)
node\[rotate=53, color=C1\] [[$\infty$]{}]{}; (6,2.75) node\[rotate=53,
color=C1\] [[$\infty$]{}]{};

C’est la conséquence de la propriété: *un quadrilatère est un
parallélogramme si et seulement si ses diagonales se coupent en leur
milieu*.

À chaque translation est associé un [****]{}.\
Pour $A$ et $B$ deux points, le [****]{} ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$ est associé à la translation qui transforme $A$
en $B$.\
Le vecteur ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$ est défini par :

1.  la [****]{} (celle de la droite $(AB)$),

2.  le [****]{} (de $A$ vers $B$)

3.  la [****]{} $AB$.

$A$ est l’[****]{} du vecteur et $B$ son [****]{}.

Deux vecteurs qui définissent la même translation sont dits [****]{}.\

${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CD\mskip2mu$\cr}}}$ si et seulement si $ABDC$ est un parallélogramme
(éventuellement aplati).

(-3,0.5) grid (4,3); (-2,2) –node\[above\] [${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$]{} (1,1); (-0,2.5) –node\[above\]
[${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CD\mskip2mu$\cr}}}$]{} (3,1.5); (-2,2) – (-0,2.5); (3,1.5) – (1,1);
(-2,2) node\[above left\] [$A$]{}; (1,1) node\[below right\] [$B$]{};
(-0,2.5) node\[above left\] [$C$]{}; (3,1.5) node\[below right\]
[$D$]{};

\[Construire un vecteur\] Soit $A$, $B$ et $C$ trois points non
alignés.\
Pour [****]{} le point $D$ tel que ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CD\mskip2mu$\cr}}}={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$, on construit le parallélogramme $ABDC$.

(-4,-2) grid (5,5); (-3,-1)– (2,0); (-3,-1)– (-1,3); (-1,3)– (4,4);
(2,0)– (4,4); (-3,-1) node\[below\] [$A$]{}; (-1,3) node\[above\]
[$B$]{}; (2,0) node\[below\] [$C$]{}; (4,4) node\[right\] [$D$]{};

Une translation peut être définie par un point quelconque et son
translaté.\
Il existe donc une **infinité** de vecteurs associés à une translation.
Ils sont tous égaux.\
Le vecteur choisi pour définir la translation est un **représentant** de
tous ces vecteurs.\
La translation **ne dépend pas** du représentant choisi pour la définir.
On le note souvent $\Vec u$.

Le vecteur associé à la translation qui transforme un point quelconque
en lui-même\
est le [****]{}, noté ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $0\mskip2mu$\cr}}}$.\
Ainsi, ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AA\mskip2mu$\cr}}} = {\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $BB\mskip2mu$\cr}}}  = {\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CC\mskip2mu$\cr}}}= \ldots ={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $0\mskip2mu$\cr}}} $

Le vecteur ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $BA\mskip2mu$\cr}}}$ de la translation qui transforme $B$ en $A$ est
appelé [****]{} à ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$.

-   Le vecteur opposé à ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AB\mskip2mu$\cr}}}$ se note $-{\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AB\mskip2mu$\cr}}}$ et on a l’égalité ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $BA\mskip2mu$\cr}}}=-{\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AB\mskip2mu$\cr}}}$.

-   La notation $\overleftarrow{AB}$ n’existe pas.

Deux vecteurs **opposés** ont même direction, même longueur mais sont de
sens contraires.

Opérations sur les vecteurs
---------------------------

### Additions

L’enchaînement de deux translations est également une translation.

Soit $A$, $B$, $C$ trois points.\
L’enchaînement de la translation de vecteur ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$ puis de la translation de vecteur
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $BC\mskip2mu$\cr}}}$ est la translation de vecteur
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AC\mskip2mu$\cr}}}$ et on a : $${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}+{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $BC\mskip2mu$\cr}}}={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AC\mskip2mu$\cr}}}.$$ Le vecteur ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AC\mskip2mu$\cr}}}$ est le vecteur [****]{}.

(-4,-2) grid (5,5); (-3,-1)–node\[below\][${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$]{} (2,0);
(2,0)–node\[right\][${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $BC\mskip2mu$\cr}}}$]{} (4,4);
(-3,-1)–node\[above,left\][${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}+{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $BC\mskip2mu$\cr}}}={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AC\mskip2mu$\cr}}}$]{} (4,4); (-3,-1) node\[below\] [$A$]{}; (2,0)
node\[below\] [$B$]{}; (4,4) node\[right\] [$C$]{};

$$\begin{aligned}
{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AD\mskip2mu$\cr}}}=&{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}+{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AC\mskip2mu$\cr}}}&\\
\Leftrightarrow {\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AC\mskip2mu$\cr}}}+{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CD\mskip2mu$\cr}}}=&{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}+{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AC\mskip2mu$\cr}}}&\text{d'après la relation de Chasles}\\
\Leftrightarrow {\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CD\mskip2mu$\cr}}}=&{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}\\
 \Leftrightarrow ABDC \text{est un parall\'elogramme} \end{aligned}$$

\[2G3\_M\_construire\_somme\] On remplace l’un des deux vecteurs par un
représentant:

-   soit de même origine afin d’utiliser la règle du parallélogramme;

-   soit d’origine l’extrémité de l’autre afin d’utiliser la relation de
    Chasles.

${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}+{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AC\mskip2mu$\cr}}}=\Vec 0$ si et seulement si $A$ est le milieu du
segment $[BC]$.

### Soustraction

[****]{}, c’est additionner son opposé.

Soit trois points $A$, $B$ et $C$ non alignés.\
Donner un représentant du vecteur ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}} ={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}-{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AC\mskip2mu$\cr}}}$.\
On a :\
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}}={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}-{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AC\mskip2mu$\cr}}}$\
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}}={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}+{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CA\mskip2mu$\cr}}}$\
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}}={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CA\mskip2mu$\cr}}}+{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$\
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}} ={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CB\mskip2mu$\cr}}}$ en utilisant la relation de Chasles.

Coordonnées d’un vecteur
------------------------

Deux vecteurs sont égaux si et seulement si ces vecteurs ont les mêmes
coordonnées.

Dans un repère $(O; I,J)$, les coordonnées du vecteur
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$ sont
$\left( \begin{array}{c} x_B-x_A\\y_B-y_A\end{array}\right)$.

Soit $A$, $B$ et $M$ de coordonnées respectives $(x_A; y_A)$,
$(x_B; y_B)$ et $(x_M; y_M)$ dans un repère $(O; I, J)$ tels que
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $OM\mskip2mu$\cr}}}={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$ et $OMBA$ est un parallélogramme.\
Donc $[AM]$ et $[OB]$ ont même milieu.
$\renewcommand{\arraystretch}{2}\left \lbrace \begin{array}{c}
                      \dfrac{x_A+x_M}{2}=\dfrac{x_B+x_O}{2}\\
                      \dfrac{y_A+y_M}{2}=\dfrac{y_B+y_O}{2}
                     \end{array} \right.\renewcommand{\arraystretch}{1}
$ soit $\left \lbrace \begin{array}{c}
                     x_A+x_M=x_B\\
                    y_A+y_M=y_B
                     \end{array} \right.
$ soit $\left \lbrace \begin{array}{c}
                     x_M=x_B-x_A\\
                    y_M=y_B-y_A
                     \end{array} \right.
$

\[2G3\_M\_lire\_coord\] Lire les coordonnées du vecteur $\Vec u$ sur la
figure ci-dessous.

///in [0/0/5/0, 0/0.87/5/0.87, 0/2.61/5/2.61, 0/3.48/5/3.48,
0/1.74/1/3.48, 1/0/3/3.48, 2/0/4/3.48, 3/0/5/3.48, 4/0/5/1.74]{} [(,)–(,
);]{} (0,0)–(2,3.48); (0,1.74)–(5,1.74); (I) at (2,1.74); (J) at
(1.5,2.61); (I) node\[rotate=-25\] [[$/$]{}]{} node\[below\][$I$]{}; (J)
node [[$-$]{}]{} node\[left\][$J$]{}; (0.5,2.61)–(3,0); (1.25,1.305)
node\[below\] [[${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}}$]{}]{};

Les coordonnées de $\Vec u$ sont $\left(\begin{array}{c}4 \\ -3
\end{array}\right)
$ car

///in [0/0/5/0, 0/0.87/5/0.87, 0/2.61/5/2.61, 0/3.48/5/3.48,
0/1.74/1/3.48, 1/0/3/3.48, 2/0/4/3.48, 3/0/5/3.48, 4/0/5/1.74]{} [(,)–(,
);]{} (0,0)–(2,3.48); (0,1.74)–(5,1.74); (I) at (2,1.74); (J) at
(1.5,2.61); (I) node\[rotate=-25\] [[$/$]{}]{} node\[below\][$I$]{}; (J)
node [[$-$]{}]{} node\[above left\][$J$]{}; (0.5,2.61)–(3,0);
(1.25,1.305) node\[below, color=F1\] [[${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}}$]{}]{}; (0.5,2.61)–(4.5,2.61); (2.5,2.61)
node\[above, color=A1\] [[$+4$]{}]{}; (4.5,2.61)–(3,0); (3.75,1.305)
node\[right, color=A1\] [[$-3$]{}]{};

Dans un repère orthonormé, construire le représentant d’origine
$A(6; 2)$ du vecteur $\Vec u$ de coordonnées
$\left( \begin{array}{c} -4 \\3\end{array}\right)$.\
On a :

(-2,-2) grid (8,6); [(-2,0)–(8,0); (1,0) node [$+$]{}; (1,0)
node\[below\] [$I$]{};]{} [(0,-2)–(0,6); (0, 1) node [$+$]{}; (0, 1)
node\[left\] [$J$]{};]{} [(0,0) node\[below left\] [$O$]{};]{}(2,5) –
(6,2); (2,2) – (6,2); (2,5) – (2,2); (4,2) node\[below\] [[$-4$]{}]{};
(2,3.5) node\[left\] [[$+3$]{}]{}; (4.5,4) node [[$\Vec u$]{}]{}; [(6,2)
node\[below right\] [$A$]{}; (6,2) node [$+$]{};]{}

Dans un repère orthogonal $(O;I,J)$, on a les points $A(-2;3)$,
$B(4;-1)$ et $C(5;3)$.\
Calculer les coordonnées

1.  du vecteur ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AB\mskip2mu$\cr}}}$;

2.  du point $D$ tel que ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AB\mskip2mu$\cr}}}={\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $CD\mskip2mu$\cr}}}$.

On a:

1.  Les coordonnées du vecteur ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AB\mskip2mu$\cr}}}$ sont $\left( \begin{array}{c}
                        x_B-x_A \\ y_B-y_A
                       \end{array}
    \right)$ soit $\left( \begin{array}{c}
                        4-(-2) \\ -1-3
                       \end{array}
    \right)$. Donc ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AB\mskip2mu$\cr}}}$ a pour coordonnées $\left( \begin{array}{c}
                        6 \\ -4
                       \end{array}
    \right)$.

2.  On cherche $(x_D;y_D)$, les coordonnées du point $D$ tel que
    ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AB\mskip2mu$\cr}}}={\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $CD\mskip2mu$\cr}}}$.\
    Or, *si deux vecteurs sont égaux alors ils ont mêmes coordonnées*.\
    Donc le couple $(x_D;y_D)$ est la solution du système:

    $\left\lbrace \begin{array}{c}
                        x_D-x_C=x_B-x_A \\ y_D-y_C=y_B-y_A
                       \end{array}\right.$ soit
    $\left \lbrace \begin{array}{l}
                                                            x_D-5=6 \\y_D-3=-4
                                                           \end{array}
    \right.$ soit $\left \lbrace \begin{array}{l}
                                                            x_D=6+5=11 \\y_D=-4+3=-1
                                                           \end{array}
    \right.$

    Les coordonnées du point $D$ sont $(11;-1)$.

Si ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}}$ et ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $v\mskip2mu$\cr}}}$ sont deux vecteurs de coordonnées respectives
$\left (\begin{array}{c}
x\\y
\end{array}\right)$ et $\left(\begin{array}{c}
x'\\y'
\end{array}\right)$, alors les coordonnées du [****]{},
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}}+{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $v\mskip2mu$\cr}}}$, sont $\left(\begin{array}{c}
x+x'\\y+y'
\end{array}\right)$.

\[2G3\_M\_repere\_point\_somme\] Dans un repère orthogonal $(O; I, J)$,
on place les points $A(2;3)$, $B(4;-1)$, $C(5;3)$ et $D(-2;-1)$. Quelles
sont les coordonnées du point $E$ tel que ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AE\mskip2mu$\cr}}}={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AD\mskip2mu$\cr}}}+{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CB\mskip2mu$\cr}}}$?

On cherche les coordonnées $(x_E;y_E)$ du point $E$ tel que
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AE\mskip2mu$\cr}}}={\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AD\mskip2mu$\cr}}}+{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CB\mskip2mu$\cr}}}$.\
Donc le couple $(x_E;y_E)$ est solution du système:

$\left\lbrace\begin{array}{l}
x_E-x_A=(x_D-x_A)+(x_B-x_C)\\y_E-y_A=(y_D-y_A)+(y_B-y_C)
\end{array}\right.$ soit $\left \lbrace \begin{array}{l}
x_E-2=(-2-2)+(4-5)\\y_E-3=(-1-3)+(-1-3)
\end{array}
\right.$ soit $\left \lbrace \begin{array}{l}
x_E-2=-5 \\y_E-3=-8
\end{array}
\right.$ soit $\left \lbrace \begin{array}{l}
x_E=-5+2=-3 \\y_E=-8+3=-5
\end{array}
\right.$

Les coordonnées du point $E$ sont $(-3;-5)$.

Multiplication par un réel
--------------------------

Soit ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}}$ un vecteur de coordonnées $(x;y)$ et $\lambda$ un
réel.\
La [****]{} est le vecteur [****]{} de coordonnées [****]{}.

\[2G3\_M\_reperer\_produit\] Dans un repère orthogonal, construire le
représentant d’origine $A(1; 4)$ du vecteur $-0,5 \Vec u$ avec
$\Vec u \left( \begin{array}{c} 2 \\-3\end{array}\right)$.\
On a :\

Soient deux vecteurs ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$ et ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CD\mskip2mu$\cr}}}$ et $\lambda$ un réel tels que
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}=\lambda{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $CD\mskip2mu$\cr}}}$.

-   si $\lambda>0$, ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AB\mskip2mu$\cr}}}$ et ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $CD\mskip2mu$\cr}}}$ sont de même sens.

-   si $\lambda<0$, ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AB\mskip2mu$\cr}}}$ et ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $CD\mskip2mu$\cr}}}$ sont de sens contraires.

$\Vec u$ et $\lambda \Vec u$ ont la même direction. Leurs sens et leurs
longueurs dépendent de $\lambda$.

Colinéarité
-----------

On dit que deux vecteurs non nuls sont [****]{} si leurs coordonnées
dans un même repère sont proportionnelles.

Par convention, le vecteur nul est colinéaire à tout vecteur
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}}$.

Deux vecteurs ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}}$ et ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $v\mskip2mu$\cr}}}$ non nuls sont colinéaires lorsqu’il existe un réel
$\lambda$ tel que ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $v\mskip2mu$\cr}}}=\lambda{\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}}$.

\[2G3\_M\_colinearite\] Pour vérifier que deux vecteurs non nuls
${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $u\mskip2mu$\cr}}}\left (\begin{array}{c}
x\\y
\end{array}\right)$ et ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $v\mskip2mu$\cr}}}\left(\begin{array}{c}
x'\\y'
\end{array}\right)$ sont colinéaires, il suffit de:

possibilité 1

:   trouver un réel $\lambda$ non nul tel que $x'=\lambda x$ et
    $y'=\lambda y$;

possibilité 2

:   vérifier que les produits en croix, $xy'$ et $x'y$, sont égaux.

Soit $(O; I, J)$ un repère orthogonal. Les vecteurs suivants sont-ils
colinéaires?

1.  $\Vec u \left( \begin{array}{c}
    2\\6 
    \end{array}
    \right)$ et $\Vec v \left( \begin{array}{c}
    -6 \\ -18
    \end{array}
    \right)$.

2.  $\Vec w \left( \begin{array}{c}
    -5 \\ 3\end{array}\right)$ et
    $\Vec z \left( \begin{array}{c}12 \\ -7\end{array}\right)$.

On a :

1.  $-6=-3\times 2$ et $-18=-3\times 6$ donc $\Vec v=-3\Vec u$. $\Vec u$
    et $\Vec v$ sont donc colinéaires.

2.  $-5\times(-7)=35$ et $3\times 12=36$. Les produits en croix ne sont
    pas égaux. Donc $\Vec w$ et $\Vec z$ ne sont pas colinéaires.

-   Deux droites $(AB)$ et $(CD)$ sont **parallèles** si et seulement si
    les vecteurs ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AB\mskip2mu$\cr}}}$ et ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $CD\mskip2mu$\cr}}}$ sont colinéaires;

-   Trois points $A$, $B$ et $C$ sont **alignés** si et seulement si les
    vecteurs ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AB\mskip2mu$\cr}}}$ et ${\vbox{\halign{##\cr 
      \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
      $AC\mskip2mu$\cr}}}$ sont colinéaires.

Les points $A(1;2 )$, $B(3;1 )$ et $C(5; 3)$ sont-ils alignés ?\
On calcule les coordonnées des vecteurs ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$ et ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AC\mskip2mu$\cr}}}$ puis les produits en croix :
$$(x_B-x_A)(y_C-y_A)=(3-1)(3-2)=2\times 1=2.$$ et ainsi :\
$$(y_B-y_A)(x_C-x_A)=(1-2)(5-1)=-1\times4=-4.$$ Les coordonnées des
vecteurs ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AB\mskip2mu$\cr}}}$ et ${\vbox{\halign{##\cr 
  \tiny\rightarrowfill\cr\noalign{\nointerlineskip\vskip1pt} 
  $AC\mskip2mu$\cr}}}$ ne sont pas proportionnelles. Donc $A$, $B$, $C$
ne sont pas alignés.
