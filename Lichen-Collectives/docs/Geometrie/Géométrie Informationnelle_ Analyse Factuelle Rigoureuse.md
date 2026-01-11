# **Cadres Géométriques Unifiés : La Géométrie Informationnelle de la Micro-Statistique à l'Espace-Temps Macroscopique**

## **1\. Introduction : La Nature Géométrique de l'Information et l'Unification des Échelles**

L'histoire de la physique théorique est marquée par une quête incessante d'unification, cherchant à décrire des phénomènes disparates par un langage mathématique commun. Au cours des dernières décennies, la convergence entre la géométrie différentielle et les statistiques a donné naissance à une discipline puissante et transversale : la géométrie informationnelle. Ce domaine ne traite plus les distributions de probabilité comme de simples fonctions analytiques, mais comme des points sur une variété riemannienne structurée, offrant ainsi un cadre rigoureux pour appréhender la complexité physique à travers des échelles radicalement différentes.1

Traditionnellement, la géométrie était l'apanage de l'espace physique — un cadre rigide, déterministe et tangible décrit par la relativité générale. À l'opposé, les statistiques traitaient de l'incertitude, de la fluctuation et de l'estimation dans des systèmes désordonnés. La géométrie informationnelle comble ce fossé en définissant une "variété statistique" où la distance entre les points n'est pas spatiale, mais est déterminée par la distinguabilité des distributions de probabilité. Cette distance est quantifiée par la métrique d'information de Fisher (FIM) en régime classique, et par la métrique de Fubini-Study ou de Bures en régime quantique.1

Ce rapport de recherche présente une analyse exhaustive et factuelle de la littérature établie concernant l'application de la géométrie informationnelle à travers les échelles physiques. Il explore comment ce langage géométrique décrit non seulement les fluctuations microscopiques des états quantiques, mais s'étend aux propriétés macroscopiques des systèmes thermodynamiques via la géométrie de Ruppeiner, pour finalement atteindre l'échelle cosmologique où l'espace-temps lui-même émerge de l'intrication quantique et des structures holographiques.5 L'analyse détaille rigoureusement les mécanismes par lesquels les lois dynamiques fondamentales — de l'équation de Schrödinger aux équations de champ d'Einstein — peuvent être dérivées de principes informationnels variationnels, suggérant que la "réalité" physique pourrait être une manifestation de la structure de l'information.8

## ---

**2\. Fondements Mathématiques : La Variété Statistique**

Le postulat central de la géométrie informationnelle est qu'une famille paramétrique de distributions de probabilité $S \= \\{p(x; \\xi) | \\xi \\in \\mathbb{R}^n\\}$ constitue une variété différentiable lisse. Sur cette variété, les propriétés géométriques — telles que la métrique, la connexion affine et la courbure — ne sont pas des abstractions mathématiques arbitraires, mais encodent profondément le comportement statistique et physique du système modélisé.1

### **2.1 La Métrique d'Information de Fisher (FIM)**

La pierre angulaire de cette architecture est la métrique d'information de Fisher. Contrairement à la métrique euclidienne qui mesure la distance physique linéaire, la FIM mesure une "distance statistique" ou, plus précisément, le degré de distinguabilité entre deux distributions de probabilité $p(x; \\xi)$ et $p(x; \\xi \+ d\\xi)$ qui diffèrent par une variation infinitésimale de leurs paramètres.1

Pour une variété statistique $S$ dotée de coordonnées $\\xi \= \[\\xi^1, \\dots, \\xi^n\]$, les composantes du tenseur métrique de Fisher $g\_{ij}(\\xi)$ sont définies par l'espérance du produit des fonctions de score (les dérivées partielles du logarithme de la vraisemblance). Mathématiquement, cela s'exprime par l'intégrale suivante sur l'espace des événements $X$ 1 :

$$g\_{ij}(\\xi) \= E\_{\\xi} \\left\[ \\frac{\\partial \\log p(x; \\xi)}{\\partial \\xi^i} \\frac{\\partial \\log p(x; \\xi)}{\\partial \\xi^j} \\right\] \= \\int\_X \\frac{\\partial \\log p(x; \\xi)}{\\partial \\xi^i} \\frac{\\partial \\log p(x; \\xi)}{\\partial \\xi^j} p(x; \\xi) dx$$  
Cette définition confère à la métrique des propriétés d'invariance remarquables. Le théorème de Chentsov établit que la métrique d'information de Fisher est l'unique métrique riemannienne (à un facteur d'échelle près) sur le simplexe de probabilité qui reste invariante sous des transformations statistiques suffisantes.1 Cette invariance est cruciale car elle signifie que la géométrie est intrinsèque à la distribution de probabilité elle-même, et non dépendante de la paramétrisation arbitraire choisie pour la décrire, qu'il s'agisse de paramètres naturels, d'espérance ou d'autres coordonnées curvilignes.1

Une interprétation géométrique alternative relie la FIM à la divergence de Kullback-Leibler (KL), qui mesure l'entropie relative entre deux distributions. Si $D\_{KL}\[p(\\xi) |

| p(\\xi \+ d\\xi)\]$ représente cette divergence, la métrique de Fisher apparaît comme le terme du second ordre dans son expansion de Taylor 3 :

$$ D\_{KL}\[p(\\xi) |

| p(\\xi \+ d\\xi)\] \\approx \\frac{1}{2} \\sum\_{i,j} g\_{ij}(\\xi) d\\xi^i d\\xi^j $$

Cette relation établit fermement la métrique comme une mesure infinitésimale de la "perte d'information" ou de la surprise générée par une petite fluctuation des paramètres.

### **2.2 Connexions Affines Duales et la Géométrie $\\alpha$ d'Amari**

Si la métrique permet de définir des distances, la définition de "lignes droites" (géodésiques) et le transport parallèle de vecteurs tangents nécessitent une structure supplémentaire : une connexion affine. Dans la géométrie riemannienne standard, la connexion de Levi-Civita est uniquement déterminée par la métrique (elle préserve la métrique et est sans torsion). Cependant, la géométrie informationnelle introduit une structure plus riche : une paire duale de connexions affines.1

Le professeur Shun-ichi Amari, fondateur de la géométrie informationnelle moderne, a introduit le concept des $\\alpha$-connexions ($\\nabla^{(\\alpha)}$), une famille de connexions affines paramétrées par un scalaire $\\alpha$. Ces connexions sont définies via les $\\alpha$-divergences, dont la divergence KL est un cas particulier. Spécifiquement, $\\alpha \= \-1$ correspond à la 1-connexion (aussi appelée connexion exponentielle), tandis que $\\alpha \= 1$ correspond à la connexion de mélange.1

La caractéristique fondamentale de ce cadre est la condition de dualité. Deux connexions $\\nabla$ et $\\nabla^\*$ sont dites duales par rapport à la métrique $g$ si elles satisfont la règle de Leibniz généralisée pour tous champs de vecteurs $X, Y, Z$ 1 :

$$X \\langle Y, Z \\rangle\_g \= \\langle \\nabla\_X Y, Z \\rangle\_g \+ \\langle Y, \\nabla^\*\_X Z \\rangle\_g$$  
Amari a démontré que la $\\alpha$-connexion et la $-\\alpha$-connexion sont duales l'une de l'autre par rapport à la métrique de Fisher. Le cas particulier $\\alpha \= 0$ correspond à la connexion de Levi-Civita de la métrique de Fisher, qui est sa propre duale (auto-duale).1

Cette dualité éclaire la structure géométrique de l'estimation statistique. Pour la famille exponentielle de distributions (qui inclut les distributions gaussiennes, de Poisson et de Boltzmann), la variété est "plate" par rapport aux connexions $\\pm 1$. Cette platitude dually (dualement plate) permet des solutions exactes en théorie de l'estimation, car les géodésiques duales correspondent à des contraintes linéaires dans les paramètres naturels et les paramètres d'espérance, respectivement. La divergence canonique associée à cette structure dually plate est la divergence de Bregman, qui généralise la distance euclidienne.2

### **2.3 La Borne de Cramér-Rao et l'Incertitude Intrinsèque**

La signification physique et statistique de la métrique de Fisher est cristallisée dans la borne de Cramér-Rao. Ce théorème fondamental stipule que la variance de tout estimateur non biaisé $\\hat{\\xi}$ d'un paramètre $\\xi$ est bornée inférieurement par l'inverse de l'information de Fisher 8 :

$$\\text{Var}(\\hat{\\xi}) \\ge \\frac{1}{I(\\xi)}$$  
Ou, en notation matricielle pour plusieurs paramètres :

$$\\text{Cov}(\\hat{\\xi}) \\ge I(\\xi)^{-1}$$  
Géométriquement, cela implique que la courbure et le volume de la variété statistique imposent des limites fondamentales à la précision de toute mesure physique. Dans les régions de la variété où le "volume d'information" est élevé (grand déterminant de $g\_{ij}$), les états sont facilement distinguables, la distance statistique est grande, et l'incertitude de mesure est faible. Inversement, dans les régions où la métrique dégénère, les paramètres deviennent indistinguables et les fluctuations dominent. Ce principe de distinguabilité constitue la base pour dériver des lois physiques à partir de l'information, notamment via le principe d'Information Physique Extrême (EPI) discuté ultérieurement.8 L'inégalité de Cramér-Rao devient ainsi une loi géométrique de l'incertitude, analogue aux relations d'incertitude de Heisenberg en mécanique quantique.15

## ---

**3\. Géométrie de l'Information Quantique : L'Échelle Microscopique**

Le cadre géométrique établi pour les probabilités classiques s'étend naturellement à la mécanique quantique, où les distributions de probabilité sont remplacées par des amplitudes complexes et des matrices de densité. À cette échelle microscopique, la variété devient l'espace de Hilbert projectif complexe, et la métrique acquiert des propriétés liées à la phase et à l'intrication.

### **3.1 La Métrique de Fubini-Study et les États Purs**

En mécanique quantique, un état pur est représenté par un vecteur $|\\psi\\rangle$ dans un espace de Hilbert $\\mathcal{H}$. Cependant, les états physiques sont définis à une phase globale près ($|\\psi\\rangle \\sim e^{i\\theta}|\\psi\\rangle$) et à une normalisation près. L'espace des états physiques réels est donc l'espace projectif complexe $\\mathbb{C}P^n$.16

La métrique naturelle et unique sur cet espace est la métrique de Fubini-Study. Pour un état quantique $|\\psi(\\xi)\\rangle$ paramétré par des coordonnées réelles $\\xi$, la métrique infinitésimale $ds^2$ est dérivée du recouvrement (overlap) entre états voisins 3 :

$$ds^2 \= 1 \- |\\langle \\psi(\\xi) | \\psi(\\xi \+ d\\xi) \\rangle|^2$$  
Sous forme différentielle, en utilisant l'opérateur de projection, elle s'exprime comme 2 :

$$g\_{ij}^{FS} \= \\text{Re} \\left\[ \\frac{\\langle \\partial\_i \\psi | \\partial\_j \\psi \\rangle}{\\langle \\psi | \\psi \\rangle} \- \\frac{\\langle \\partial\_i \\psi | \\psi \\rangle \\langle \\psi | \\partial\_j \\psi \\rangle}{\\langle \\psi | \\psi \\rangle^2} \\right\]$$  
Un résultat fondamental relie cette métrique quantique à la métrique statistique classique : la métrique de Fubini-Study correspond exactement à un quart de la métrique d'information de Fisher classique lorsque l'on considère la variation des paramètres. Plus précisément, la partie réelle du tenseur géométrique quantique est proportionnelle à l'information de Fisher (mesurant la distinguabilité), tandis que sa partie imaginaire correspond à la courbure de Berry (mesurant la phase géométrique et la topologie).4

$$g\_{ij}^{Quantum} \= \\frac{1}{4} g\_{ij}^{Fisher} \+ i \\frac{1}{2} \\Omega\_{ij}$$  
Cette unification ($g\_{ij}^{FS} \= \\frac{1}{4} g\_{ij}^{Fisher}$) démontre que la géométrie de l'information quantique fusionne les propriétés métriques (distance/distinguabilité) et les propriétés symplectiques (phase/interférence) de l'espace des états. La métrique de Fubini-Study apparaît ainsi comme une extension naturelle de la métrique euclidienne induite sur la sphère des états, après les changements de variables appropriés.3

### **3.2 La Métrique de Bures et les États Mixtes**

Pour les systèmes ouverts ou intriqués décrits par des états mixtes (matrices de densité $\\rho$), la géométrie se complexifie. La métrique riemannienne appropriée est la métrique de Bures (ou métrique de Helstrom), définie via la fidélité quantique $F(\\rho, \\sigma) \= \\text{Tr}\\sqrt{\\sqrt{\\rho}\\sigma\\sqrt{\\rho}}$.4

La distance infinitésimale de Bures entre deux matrices de densité $\\rho$ et $\\rho \+ d\\rho$ est donnée par :

$$ds^2\_{Bures} \= 2(1 \- F(\\rho, \\rho \+ d\\rho)) \= \\frac{1}{2} \\text{Tr}(\\rho L^2)$$  
où $L$ est la Dérivée Logarithmique Symétrique (SLD) définie implicitement par l'équation $d\\rho \= \\frac{1}{2}(\\rho L \+ L \\rho)$.4 La métrique de Bures est la métrique monotone minimale sous l'action des applications stochastiques (canaux quantiques), ce qui en fait la mesure fondamentale de la distinguabilité pour les états quantiques mixtes.3

Cette métrique est directement liée à l'Information de Fisher Quantique (QFI), qui généralise la borne de Cramér-Rao au régime quantique. La QFI borne la précision ultime de l'estimation d'un paramètre $\\theta$ encodé dans un état quantique $\\rho(\\theta)$ :

$$\\text{Var}(\\hat{\\theta}) \\ge \\frac{1}{\\mathcal{F}\_Q(\\theta)}$$  
Cela démontre que la géométrie de l'espace des états dicte directement les limites de la résolution expérimentale, connue sous le nom de limite de Heisenberg ($1/N$ au lieu de $1/\\sqrt{N}$ classique) dans les protocoles de métrologie quantique utilisant l'intrication.15

### **3.3 Tenseur Géométrique Quantique et Courbure de Berry**

L'analyse de la géométrie quantique révèle que le tenseur métrique n'est qu'une partie d'une structure plus vaste : le Tenseur Géométrique Quantique. Comme mentionné précédemment, sa partie imaginaire est la courbure de Berry, un objet antisymétrique qui joue un rôle analogue au champ magnétique dans l'espace des paramètres.19

Cette courbure est responsable des phases géométriques accumulées lors de l'évolution cyclique adiabatique (phase de Berry) et est liée aux propriétés topologiques de la matière, telles que l'effet Hall quantique. Dans le contexte de la géométrie informationnelle, la coexistence de la métrique (distance) et de la courbure (phase) au sein d'un même tenseur complexe souligne l'interconnexion profonde entre la statistique des mesures (Fisher) et la dynamique de phase (Berry).19

## ---

**4\. Géométrie Thermodynamique : L'Échelle Mésoscopique**

En passant de l'échelle microscopique des états quantiques à l'échelle mésoscopique de la mécanique statistique, la géométrie informationnelle se manifeste sous la forme de la Géométrie Thermodynamique. Développée par Weinhold et Ruppeiner, cette approche interprète les fluctuations thermodynamiques comme induisant une métrique sur l'espace des états d'équilibre.

### **4.1 Géométrie de Ruppeiner : L'Entropie comme Potentiel Métrique**

La géométrie de Ruppeiner définit une métrique riemannienne sur la variété des états d'équilibre thermodynamique en utilisant l'entropie $S$ comme potentiel thermodynamique. L'élément de longueur est défini par la Hessienne de l'entropie par rapport aux variables extensives (telles que l'énergie interne $U$, le volume $V$, et le nombre de particules $N$) 5 :

$$g\_{ij}^R \= \-\\frac{\\partial^2 S}{\\partial X^i \\partial X^j}$$  
où $X^i$ représente les paramètres extensifs. Cette définition est intrinsèquement liée à la théorie des fluctuations d'Einstein. La probabilité de trouver le système dans un état fluctuant éloigné de l'équilibre est proportionnelle à l'exponentielle de la distance de Ruppeiner :

$$P \\propto e^{-\\frac{1}{2} \\Delta l^2}$$  
Cela lie directement la distance riemannienne à la probabilité de Boltzmann des fluctuations spontanées.5 Une métrique alternative, la métrique de Weinhold, utilise l'énergie interne $U$ comme potentiel, reliée à celle de Ruppeiner par une transformation conforme impliquant la température ($g^R \= \\frac{1}{T} g^W$).24

### **4.2 Interprétation Physique de la Courbure Thermodynamique**

L'apport le plus profond de la géométrie de Ruppeiner réside dans l'interprétation physique de la courbure scalaire riemannienne $R$. Contrairement à la géométrie plate d'un gaz idéal classique, les systèmes en interaction possèdent une courbure thermodynamique non nulle. Le scalaire de courbure $R$ sert de mesure directe de la longueur de corrélation $\\xi$ du système.20

Le signe et la magnitude de la courbure de Ruppeiner $R$ révèlent la nature des interactions microscopiques 5 :

* **$R \> 0$ (Courbure Positive) :** Indique la présence d'interactions répulsives dominantes (par exemple, un gaz de Fermi idéal, modèle de sphères dures).  
* **$R \< 0$ (Courbure Négative) :** Indique des interactions attractives (par exemple, un gaz de Bose, la région attractive d'un fluide de Van der Waals).  
* **$R \= 0$ (Plat) :** Indique l'absence d'interaction (Gaz Idéal Classique).

Cet outil de diagnostic géométrique a été largement appliqué pour étudier les transitions de phase. À l'approche d'un point critique, la longueur de corrélation diverge ($\\xi \\to \\infty$), et par conséquent, la courbure thermodynamique $R$ diverge également. L'exposant critique de la divergence de la courbure est lié à l'exposant de la chaleur spécifique, satisfaisant la relation d'hyperscaling $R \\sim \\xi^d$, où $d$ est la dimension spatiale du système.20

### **4.3 Géométrie des Trous Noirs et Structures de Phase**

La géométrie de Ruppeiner a trouvé une application spectaculaire dans la thermodynamique des trous noirs, en traitant ces objets gravitationnels comme des systèmes thermiques macroscopiques. Pour les trous noirs chargés en espace Anti-de Sitter (AdS), l'espace de phase thermodynamique présente une structure riche analogue à un fluide de Van der Waals, incluant une criticalité $P-V$ (où la constante cosmologique $\\Lambda$ joue le rôle de la pression thermodynamique).5

Les recherches indiquent que pour les "petits" trous noirs, la courbure de Ruppeiner est finie et positive, suggérant des interactions répulsives parmi les constituants microscopiques du trou noir. À mesure que la taille du trou noir augmente, la corrélation change. Spécifiquement 23 :

* Le scalaire de courbure $R$ pour les trous noirs chargés AdS est généralement négatif dans les régimes de grands trous noirs, indiquant que des interactions attractives dominent la microstructure.  
* Au point critique de la transition de phase petit trou noir / grand trou noir, la courbure diverge vers l'infini négatif, signalant une transition de phase du second ordre parfaitement analogue à la criticalité liquide-gaz des fluides classiques.27  
* Dans certains régimes (petits trous noirs chargés), la courbure peut devenir positive, impliquant une dominance des interactions répulsives de type fermionique.28

Cette application de la géométrie informationnelle jette un pont conceptuel entre la thermodynamique classique et les degrés de liberté microscopiques inconnus de la gravité quantique, suggérant que l'entropie des trous noirs émerge de micro-états en interaction obéissant aux lois statistiques géométriques standards.

## ---

**5\. L'Émergence des Lois Physiques : Dynamique et Information**

Au-delà de la description des états statiques, plusieurs lignes de recherche suggèrent que la géométrie informationnelle pourrait être génératrice des lois dynamiques de la physique. Le principe d'Information Physique Extrême (EPI) de Roy Frieden postule que les lois physiques fondamentales découlent d'une variation de l'information de Fisher.

### **5.1 Le Principe EPI (Extreme Physical Information)**

Le principe central de l'EPI est que l'observation d'un phénomène physique implique un transfert d'information de la "source" (le système physique) vers les "données" (la mesure). Ce processus est imparfait et régi par un principe variationnel.8

Frieden définit l'information physique $K$ comme la différence entre l'information de Fisher $I$ (intrinsèque aux données acquises) et l'information liée $J$ (intrinsèque à la source ou au phénomène) :

$$K \= I \- J$$  
Le principe EPI stipule que les lois physiques sont les solutions qui extrémisent cette quantité, c'est-à-dire $\\delta(I \- J) \= 0$. Ici, $I$ mesure la précision ou la qualité de la connaissance obtenue, tandis que $J$ représente le coût informationnel ou la contrainte imposée par le système.8

### **5.2 Dérivation des Équations Fondamentales**

En appliquant le principe EPI à différents scénarios de mesure, la littérature rapporte la dérivation de plusieurs équations majeures de la physique théorique 8 :

* **Équation de Schrödinger :** En considérant l'estimation des coordonnées de position avec des fluctuations aléatoires, la minimisation de l'information de Fisher mène à une équation différentielle identique à l'équation de Schrödinger indépendante du temps. Le terme d'énergie cinétique émerge directement de l'intégrale de l'information de Fisher ($\\int (\\nabla \\psi)^2 dx$), interprétée comme une mesure de la "vitesse" de changement de la densité de probabilité.32  
* **Équations de Champ d'Einstein :** L'EPI a été appliqué à l'estimation des coordonnées de 4-position dans un espace-temps courbe. En définissant une densité de probabilité sur la variété et en extrémisant l'information associée, on retrouve l'action d'Einstein-Hilbert et les équations du champ gravitationnel. Cela suggère que la courbure de l'espace-temps optimise le flux d'information lors de la mesure des positions spatio-temporelles.9

Bien que cette approche soit sujette à des critiques concernant l'arbitraire possible dans la définition de l'information liée $J$ et la validité universelle du principe 32, le cadre EPI représente une tentative significative d'ancrer la physique dans la géométrie de l'acquisition d'information. Il s'aligne avec la philosophie "It from Bit", suggérant que la distinguabilité des états (Information de Fisher) est la ressource primaire d'où émerge la dynamique.

### **5.3 Dérivation Thermodynamique de la Gravité (Jacobson)**

En parallèle à l'EPI, une connexion profonde entre thermodynamique et gravité a été établie par Ted Jacobson en 1995\. Il a démontré que les équations de champ d'Einstein ne sont pas nécessairement des postulats fondamentaux, mais peuvent être dérivées comme une équation d'état thermodynamique locale. La dérivation repose sur la relation de Clausius $\\delta Q \= T dS$ appliquée à un horizon de Rindler local.35

Les hypothèses clés de Jacobson sont :

1. **L'Effet Unruh :** Un observateur accéléré perçoit un bain thermique avec une température proportionnelle à son accélération, $T \= \\hbar a / 2\\pi k\_B$.  
2. **Entropie de Bekenstein-Hawking :** L'entropie de l'horizon est proportionnelle à son aire ($S \= \\eta A$).  
3. **Flux d'Énergie :** La chaleur $\\delta Q$ traversant l'horizon est identifiée au flux d'énergie de la matière, décrit par le tenseur énergie-impulsion $T\_{ab} \\chi^a \\chi^b$.

En égalant le flux de chaleur $\\delta Q$ à $T dS$ (où $dS$ correspond au changement d'aire de l'horizon dû à la focalisation des géodésiques par la courbure), Jacobson a dérivé l'équation d'Einstein 25 :

$$R\_{ab} \- \\frac{1}{2}R g\_{ab} \+ \\Lambda g\_{ab} \= 8\\pi G T\_{ab}$$  
Cette dérivation interprète la courbure de l'espace-temps comme la manifestation macroscopique des relations entropie-aire microscopiques.

### **5.4 Gravité Entropique (Verlinde)**

S'appuyant sur les travaux de Jacobson, Erik Verlinde a proposé en 2011 que la gravité est une "force entropique" résultant de la tendance naturelle d'un système à maximiser son entropie. Dans le modèle de Verlinde, le mouvement d'une particule modifie le contenu informationnel sur un écran holographique (une surface entourant la masse), entraînant une force thermodynamique $F \= T \\nabla S$.38

La dérivation de Verlinde permet de retrouver la loi de gravitation de Newton et, dans ses généralisations relativistes, les équations d'Einstein. La théorie postule que l'information spatio-temporelle (bits) est la quantité fondamentale, et que la gravité est un artefact statistique du mélange (scrambling) de cette information. La connexion avec la géométrie de Ruppeiner est évidente : la force gravitationnelle est pilotée par les gradients de densité d'information (entropie), tout comme les processus thermodynamiques sont pilotés par la maximisation de l'entropie.38

Des travaux récents étendent ces concepts en utilisant explicitement la métrique d'information de Fisher. Parvan et d'autres ont montré que le tenseur d'Einstein peut être dérivé de la métrique de Fisher des valeurs propres de la matrice de densité partielle d'états quantiques intriqués.9 Dans ce cadre, la constante cosmologique $\\Lambda$ émerge naturellement dans la variété informationnelle comme résultat de l'utilisation d'extensions complexes de l'espace-temps ou de familles exponentielles gaussiennes spécifiques.40

## ---

**6\. Holographie et Reconstruction de l'Espace-Temps : L'Échelle Cosmologique**

La réalisation la plus rigoureuse de l'idée "l'espace-temps émerge de l'information" se trouve dans la correspondance AdS/CFT (Holographie). Ici, une théorie quantique des champs (CFT) résidant sur le bord d'un espace est duale à une théorie gravitationnelle dans le volume (bulk) de l'espace Anti-de Sitter (AdS). La géométrie informationnelle fournit le dictionnaire de traduction entre ces deux univers.

### **6.1 La Formule de Ryu-Takayanagi**

Le pont fondamental entre l'information de bord et la géométrie du volume est la formule de Ryu-Takayanagi (RT). Elle stipule que l'entropie d'intrication $S\_A$ d'un sous-système $A$ dans la CFT de bord est proportionnelle à l'aire de la surface minimale $\\gamma\_A$ dans l'espace-temps AdS qui est homologue à $A$ (c'est-à-dire qui partage le même bord que $A$) 7 :

$$S\_A \= \\frac{\\text{Area}(\\gamma\_A)}{4G\_N}$$  
Cette formule est la réalisation géométrique précise de l'entropie de Bekenstein-Hawking. Elle implique une relation causale profonde : la connectivité de l'espace-temps (le bulk) est maintenue par l'intrication des états de bord. Si l'intrication tombe à zéro, la géométrie du volume se "pince" et se déconnecte ; l'espace-temps se désintègre littéralement.44 Cette relation est connue sous le slogan "It from Qubit".

### **6.2 Information de Fisher Holographique**

Alors que la formule RT relie l'aire à l'entropie (une mesure statique), la métrique d'information de Fisher est reliée à la *fidélité* ou à la réponse de l'état aux perturbations. La métrique d'Information de Fisher Holographique mesure la distance entre l'état fondamental (vide) de la CFT et un état perturbé par un opérateur.46

La recherche identifie le dual holographique de la métrique de Fisher avec le volume d'une tranche de codimension un dans le bulk, ou avec la "susceptibilité de fidélité canonique". Spécifiquement, pour une sous-région sphérique, la métrique de Fisher pour des états mixtes de bord est reliée au volume enfermé par la surface de Ryu-Takayanagi.47

$$G\_{\\lambda\\lambda} \\sim \\text{Volume}(\\Sigma)$$  
Cela établit une hiérarchie géométrique fascinante :

1. **Entropie d'Intrication $\\leftrightarrow$ Aire Minimale (Surface de codimension 2).**  
2. **Information de Fisher / Fidélité $\\leftrightarrow$ Volume Maximal (Région de codimension 1).**

Cette correspondance volume/information explique comment la géométrie du volume encode la distinguabilité des états du bord.

### **6.3 Espace Cinématique et Géométrie Intégrale**

Un outil géométrique puissant dans ce contexte est l'"Espace Cinématique", l'espace de toutes les géodésiques possibles dans le bulk. La longueur d'une géodésique dans AdS (qui donne l'entropie d'intrication dans la CFT) peut être calculée en intégrant une densité locale sur l'espace cinématique.49

Le volume de l'espace cinématique est défini par une forme symplectique dérivée de l'information mutuelle conditionnelle des intervalles de bord. Cela implique que la géométrie du bulk est littéralement construite à partir des densités d'information (structures d'intrication) du bord.49 L'espace cinématique agit comme une structure intermédiaire, une géométrie auxiliaire qui organise l'information d'intrication pour générer la métrique spatiale.

## ---

**7\. Réseaux de Tenseurs et Géométrie Discrète**

L'abstrait continuum de la correspondance AdS/CFT trouve une réalisation concrète et discrète dans les Réseaux de Tenseurs, en particulier l'Ansatz de Renormalisation d'Intrication Multi-échelle (MERA). Ces réseaux fournissent une géométrie discrète de l'information qui reproduit la structure hyperbolique de l'espace-temps AdS.

### **7.1 MERA et Géométrie Hyperbolique**

Le réseau MERA (Multi-scale Entanglement Renormalization Ansatz) est conçu pour représenter efficacement les états fondamentaux des systèmes quantiques critiques (CFT). Il utilise des couches de "désintriqueurs" (tenseurs unitaires) et d'"isométries" pour grossir l'état quantique échelle par échelle, éliminant l'intrication à courte portée à chaque étape.51

La connectivité d'un réseau MERA forme naturellement une géométrie hyperbolique discrète (AdS). La "direction" de la renormalisation (du réseau microscopique UV vers les blocs macroscopiques IR) correspond exactement à la coordonnée radiale $z$ dans l'espace AdS, qui représente l'échelle d'énergie.51

### **7.2 Renormalisation d'Intrication comme Géodésiques**

La formule de Ryu-Takayanagi émerge naturellement dans le cadre MERA. L'entropie d'intrication d'une région dans l'état MERA est calculée en comptant le nombre de liens (bonds) coupés par le chemin minimal à travers le réseau qui sépare la région du reste du système. Cette coupe minimale est l'équivalent discret de la surface minimale $\\gamma\_A$ dans la formule RT.51

* **MERA vs MPS :** Les états de produit matriciel (MPS) représentent des systèmes 1D avec une loi d'aire (entropie constante), générant une géométrie triviale (un "tube"). MERA, en incluant la dimension d'échelle, supporte une loi d'échelle logarithmique pour l'entropie ($S \\sim \\log L$), ce qui correspond exactement à la longueur d'une géodésique dans un espace hyperbolique.51

Cela confirme que le réseau MERA est un squelette discret de l'espace-temps gravitationnel dual. La dimension de lien (bond dimension) $\\chi$ des tenseurs correspond à la capacité de l'espace-temps à porter l'intrication (liée à l'inverse de la constante de Newton $G\_N$).

### **7.3 Information de Fisher et Complexité dans MERA**

La complexité et la géométrie du réseau MERA sont également liées à la métrique d'information de Fisher. L'optimisation des tenseurs MERA peut être vue comme une minimisation de l'énergie, équivalente à un mouvement le long de la plus grande pente dans la variété informationnelle définie par la métrique de Fubini-Study des états variationnels.50

Des propositions récentes suggèrent que la complexité du réseau de tenseurs (le nombre de portes/tenseurs nécessaires pour construire l'état) agit comme une mesure de l'Information de Fisher de l'univers de de Sitter (dS) dans certains modèles cosmologiques. Cela lie directement la complexité du réseau (un concept informatique) au volume thermodynamique de l'espace-temps.50 La géométrie MERA permet ainsi une interprétation "informatique" de la cosmologie, où l'expansion de l'univers correspond à la croissance de la complexité de l'état quantique sous-jacent.

## ---

**8\. Conclusion : Une Synthèse des Échelles**

La littérature examinée dans ce rapport établit que la géométrie informationnelle fournit un langage unifié décrivant des phénomènes allant de l'échelle quantique à l'échelle cosmologique. Ce n'est pas une simple analogie, mais une identité structurelle profonde.

1. **Micro-Échelle (Quantique) :** Les métriques de Fubini-Study et de Bures quantifient la distinguabilité et la fidélité des états quantiques. Cette géométrie impose des limites fondamentales à la mesure (Cramér-Rao) et définit la phase géométrique (courbure de Berry).  
2. **Méso-Échelle (Thermodynamique) :** La géométrie de Ruppeiner révèle que la "distance statistique" entre les états d'équilibre encode la nature des interactions microscopiques. La courbure $R$ de la variété informationnelle prédit les transitions de phase et identifie les forces attractives/répulsives, s'appliquant même à la thermodynamique exotique des trous noirs.  
3. **Macro-Échelle (Gravité & Espace-Temps) :** La Relativité Générale émerge comme une description hydrodynamique de la variété informationnelle sous-jacente. Les dérivations de Jacobson ($dQ=TdS \\to G\_{\\mu\\nu} \\propto T\_{\\mu\\nu}$) et la Gravité Entropique de Verlinde refondent la gravité comme une conséquence de la maximisation de l'entropie.  
4. **Échelle Holographique (AdS/CFT & MERA) :** La géométrie de l'espace-temps est littéralement la géométrie de l'intrication. La formule de Ryu-Takayanagi et les réseaux MERA démontrent que la métrique gravitationnelle du "bulk" est construite à partir des corrélations d'information (entropie d'intrication et information de Fisher) de la surface de bord.

En résumé, les recherches documentées soutiennent la conclusion que la géométrie n'est pas simplement une scène sur laquelle la physique se déroule, mais une propriété émergente du traitement de l'information des micro-états constituants. Que ce soit défini par la métrique de Fisher des distributions de probabilité ou l'aire des surfaces holographiques, la structure de la réalité physique apparaît fondamentalement informationnelle.

### **Tableau : Comparaison des Métriques Géométriques à Travers les Échelles**

| Échelle / Domaine | Nom de la Métrique | Base de Définition | Interprétation Physique | Application Clé | Source |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Statistique Classique** | Métrique d'Information de Fisher (FIM), $g\_{ij}$ | Dérivées du Log-vraisemblance (Hessienne de KL) | Distinguabilité des distributions de probabilité | Borne de Cramér-Rao (limites d'estimation) | 1 |
| **Mécanique Quantique** | Métrique de Fubini-Study | Recouvrement des états purs $ | \\langle \\psi | \\phi \\rangle | ^2$ |
| **États Mixtes** | Métrique de Bures (Helstrom) | Fidélité Quantique $F(\\rho, \\sigma)$ | Distinguabilité des matrices de densité | Métrologie Quantique (Systèmes bruités) | 4 |
| **Thermodynamique** | Métrique de Ruppeiner | Hessienne de l'Entropie $-\\partial^2 S$ | Fluctuations des paramètres extensifs | Transitions de phase, Type d'interaction (signe de $R$) | 5 |
| **Relativité Générale** | Métrique Spatio-temporelle $g\_{\\mu\\nu}$ | Temps propre / Longueur | Courbure de l'espace-temps physique | Gravité (Éq. d'Einstein dérivée de la thermodynamique) | 9 |
| **Holographie (AdS/CFT)** | Information de Fisher Holographique | Volume du bulk / Susceptibilité de Fidélité | Géométrie du bulk duale à l'information de bord | Reconstruction de la métrique bulk à partir de la CFT | 46 |

#### **Sources des citations**

1. F-Geometry and Amari's α-Geometry on a Statistical Manifold \- MDPI, consulté le janvier 7, 2026, [https://www.mdpi.com/1099-4300/16/5/2472](https://www.mdpi.com/1099-4300/16/5/2472)  
2. An Elementary Introduction to Information Geometry \- PMC \- NIH, consulté le janvier 7, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC7650632/](https://pmc.ncbi.nlm.nih.gov/articles/PMC7650632/)  
3. Fisher information metric \- Wikipedia, consulté le janvier 7, 2026, [https://en.wikipedia.org/wiki/Fisher\_information\_metric](https://en.wikipedia.org/wiki/Fisher_information_metric)  
4. Bures metric \- Wikipedia, consulté le janvier 7, 2026, [https://en.wikipedia.org/wiki/Bures\_metric](https://en.wikipedia.org/wiki/Bures_metric)  
5. Thermodynamic geometry and phase transition of spinning ... \- CERN, consulté le janvier 7, 2026, [https://scoap3-prod-backend.s3.cern.ch/media/files/66302/10.1103/PhysRevD.104.104066.pdf](https://scoap3-prod-backend.s3.cern.ch/media/files/66302/10.1103/PhysRevD.104.104066.pdf)  
6. The Holographic Principle Comes from Finiteness of the Universe's Geometry \- PMC \- NIH, consulté le janvier 7, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC11276587/](https://pmc.ncbi.nlm.nih.gov/articles/PMC11276587/)  
7. Ryu–Takayanagi conjecture \- Wikipedia, consulté le janvier 7, 2026, [https://en.wikipedia.org/wiki/Ryu%E2%80%93Takayanagi\_conjecture](https://en.wikipedia.org/wiki/Ryu%E2%80%93Takayanagi_conjecture)  
8. Principle of Maximum Fisher Information from Hardy's Axioms Applied to Statistical Systems, consulté le janvier 7, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC4010149/](https://pmc.ncbi.nlm.nih.gov/articles/PMC4010149/)  
9. Emergent General Relativity from Fisher Information Metric \- ResearchGate, consulté le janvier 7, 2026, [https://www.researchgate.net/publication/257410160\_Emergent\_General\_Relativity\_from\_Fisher\_Information\_Metric](https://www.researchgate.net/publication/257410160_Emergent_General_Relativity_from_Fisher_Information_Metric)  
10. Information geometry of divergence functions, consulté le janvier 7, 2026, [https://journals.pan.pl/Content/83037/PDF/19\_paper.pdf](https://journals.pan.pl/Content/83037/PDF/19_paper.pdf)  
11. 10\. Physics from Fisher Information. \- Research, consulté le janvier 7, 2026, [https://research.engineering.nyu.edu/\~jbain/physinfocomp/lectures/11.PhysicsfromFI.pdf](https://research.engineering.nyu.edu/~jbain/physinfocomp/lectures/11.PhysicsfromFI.pdf)  
12. Fisher information theory for parameter estimation in single molecule microscopy: tutorial, consulté le janvier 7, 2026, [https://opg.optica.org/josaa/fulltext.cfm?uri=josaa-33-7-B36](https://opg.optica.org/josaa/fulltext.cfm?uri=josaa-33-7-B36)  
13. Fisher information \- Wikipedia, consulté le janvier 7, 2026, [https://en.wikipedia.org/wiki/Fisher\_information](https://en.wikipedia.org/wiki/Fisher_information)  
14. \[1406.3615\] Derivation of Principle of Extreme Physical Information \- arXiv, consulté le janvier 7, 2026, [https://arxiv.org/abs/1406.3615](https://arxiv.org/abs/1406.3615)  
15. Computing the quantum Fisher information via the Fubini-Study metric for photonic states \- Online Technical Discussion Groups—Wolfram Community, consulté le janvier 7, 2026, [https://community.wolfram.com/groups/-/m/t/3561108](https://community.wolfram.com/groups/-/m/t/3561108)  
16. Fubini–Study metric \- Wikipedia, consulté le janvier 7, 2026, [https://en.wikipedia.org/wiki/Fubini%E2%80%93Study\_metric](https://en.wikipedia.org/wiki/Fubini%E2%80%93Study_metric)  
17. Fubini-Study Metric | PDF | Manifold | Geometry \- Scribd, consulté le janvier 7, 2026, [https://www.scribd.com/document/702114733/Fubini-Study-metric](https://www.scribd.com/document/702114733/Fubini-Study-metric)  
18. UNIVERSITہ DEGLI STUDI DI NAPOLI “FEDERICO II” Information Geometry and Quantum Mechanics, consulté le janvier 7, 2026, [https://www.fisica.unina.it/documents/12375590/13725484/2900\_DiNoceraF\_16-10-2019.pdf/a1691efc-3887-4776-9506-9a6c37047a70](https://www.fisica.unina.it/documents/12375590/13725484/2900_DiNoceraF_16-10-2019.pdf/a1691efc-3887-4776-9506-9a6c37047a70)  
19. \[1012.1337\] Quantum Geometric Tensor (Fubini-Study Metric) in Simple Quantum System: A pedagogical Introduction \- arXiv, consulté le janvier 7, 2026, [https://arxiv.org/abs/1012.1337](https://arxiv.org/abs/1012.1337)  
20. (PDF) Information Geometry and the Renormalization Group \- ResearchGate, consulté le janvier 7, 2026, [https://www.researchgate.net/publication/273680153\_Information\_Geometry\_and\_the\_Renormalization\_Group](https://www.researchgate.net/publication/273680153_Information_Geometry_and_the_Renormalization_Group)  
21. The Dual Role of Fisher Information Geometry in Unifying Physics : r/LLMPhysics \- Reddit, consulté le janvier 7, 2026, [https://www.reddit.com/r/LLMPhysics/comments/1nweo08/the\_dual\_role\_of\_fisher\_information\_geometry\_in/](https://www.reddit.com/r/LLMPhysics/comments/1nweo08/the_dual_role_of_fisher_information_geometry_in/)  
22. Thermodynamics, phase transitions and Ruppeiner geometry for Einstein–dilaton–Lifshitz black holes in the presence of Maxwel \- SciSpace, consulté le janvier 7, 2026, [https://scispace.com/pdf/thermodynamics-phase-transitions-and-ruppeiner-geometry-for-2e8wtgzh4f.pdf](https://scispace.com/pdf/thermodynamics-phase-transitions-and-ruppeiner-geometry-for-2e8wtgzh4f.pdf)  
23. Thermodynamic Information Geometry and Complexity Growth of Warped AdS Black Hole and the WAdS3/CFT2 Correspondence \- arXiv, consulté le janvier 7, 2026, [https://arxiv.org/pdf/1902.02433](https://arxiv.org/pdf/1902.02433)  
24. How to understand the relationship between Weinhold geometry and Ruppeiner geometry in thermodynamic geometry? \[closed\] \- Physics Stack Exchange, consulté le janvier 7, 2026, [https://physics.stackexchange.com/questions/808409/how-to-understand-the-relationship-between-weinhold-geometry-and-ruppeiner-geome](https://physics.stackexchange.com/questions/808409/how-to-understand-the-relationship-between-weinhold-geometry-and-ruppeiner-geome)  
25. Gravitation and thermodynamics: The einstein equation of state revisited \- LSU Scholarly Repository, consulté le janvier 7, 2026, [https://repository.lsu.edu/cgi/viewcontent.cgi?article=5434\&context=physics\_astronomy\_pubs](https://repository.lsu.edu/cgi/viewcontent.cgi?article=5434&context=physics_astronomy_pubs)  
26. Information geometry and Bose–Einstein condensation \- AIP Publishing, consulté le janvier 7, 2026, [https://pubs.aip.org/aip/cha/article-pdf/doi/10.1063/5.0136244/16786477/033101\_1\_online.pdf](https://pubs.aip.org/aip/cha/article-pdf/doi/10.1063/5.0136244/16786477/033101_1_online.pdf)  
27. \[PDF\] Ruppeiner geometry, phase transitions, and the microstructure ..., consulté le janvier 7, 2026, [https://www.semanticscholar.org/paper/Ruppeiner-geometry%2C-phase-transitions%2C-and-the-of-Wei-Liu/2c51f8405d19cd80bb7b2fa3d7c94e42e1ec8dd3](https://www.semanticscholar.org/paper/Ruppeiner-geometry%2C-phase-transitions%2C-and-the-of-Wei-Liu/2c51f8405d19cd80bb7b2fa3d7c94e42e1ec8dd3)  
28. \[1909.03887\] Ruppeiner Geometry, Phase Transitions, and the Microstructure of Charged AdS Black Holes \- arXiv, consulté le janvier 7, 2026, [https://arxiv.org/abs/1909.03887](https://arxiv.org/abs/1909.03887)  
29. Thermodynamic curvature in phase transitions for Hayward AdS black hole \- arXiv, consulté le janvier 7, 2026, [https://arxiv.org/html/2510.11319v2](https://arxiv.org/html/2510.11319v2)  
30. PHYSICS FROM FISHER INFORMATION, consulté le janvier 7, 2026, [https://catdir.loc.gov/catdir/samples/cam032/98020461.pdf](https://catdir.loc.gov/catdir/samples/cam032/98020461.pdf)  
31. (PDF) Derivation of Principle of Extreme Physical Information \- ResearchGate, consulté le janvier 7, 2026, [https://www.researchgate.net/publication/263126690\_Derivation\_of\_Principle\_of\_Extreme\_Physical\_Information](https://www.researchgate.net/publication/263126690_Derivation_of_Principle_of_Extreme_Physical_Information)  
32. Physics from Fisher information | Request PDF \- ResearchGate, consulté le janvier 7, 2026, [https://www.researchgate.net/publication/235410178\_Physics\_from\_Fisher\_information](https://www.researchgate.net/publication/235410178_Physics_from_Fisher_information)  
33. Variational Information Principles to Unveil Physical Laws \- MDPI, consulté le janvier 7, 2026, [https://www.mdpi.com/2227-7390/12/24/3941](https://www.mdpi.com/2227-7390/12/24/3941)  
34. Physics from Fisher Information \- by B. Roy Frieden \- Cosma Shalizi, consulté le janvier 7, 2026, [http://bactra.org/reviews/physics-from-fisher-info/](http://bactra.org/reviews/physics-from-fisher-info/)  
35. Gravity, Entropy, and Spacetime Jacobson vs. Multifaceted Coherence (MC) \- Zenodo, consulté le janvier 7, 2026, [https://zenodo.org/records/15478868/files/MC\_Entropy\_Link.pdf?download=1](https://zenodo.org/records/15478868/files/MC_Entropy_Link.pdf?download=1)  
36. Thermodynamics of Spacetime: The Einstein Equation of State \- arXiv, consulté le janvier 7, 2026, [https://arxiv.org/pdf/gr-qc/9504004](https://arxiv.org/pdf/gr-qc/9504004)  
37. Spacetime thermodynamics and entanglement entropy: the Einstein field equations, consulté le janvier 7, 2026, [https://diposit.ub.edu/bitstreams/3a349666-d2a4-4667-a191-efffc065905c/download](https://diposit.ub.edu/bitstreams/3a349666-d2a4-4667-a191-efffc065905c/download)  
38. Entropic gravity \- Wikipedia, consulté le janvier 7, 2026, [https://en.wikipedia.org/wiki/Entropic\_gravity](https://en.wikipedia.org/wiki/Entropic_gravity)  
39. Derivation of Einstein Field Equations from Information Theory \- ResearchGate, consulté le janvier 7, 2026, [https://www.researchgate.net/publication/392519451\_Derivation\_of\_Einstein\_Field\_Equations\_from\_Information\_Theory](https://www.researchgate.net/publication/392519451_Derivation_of_Einstein_Field_Equations_from_Information_Theory)  
40. \[2301.13017\] Einstein's equations and the pseudo-entropy of pseudo-Riemannian information manifolds \- arXiv, consulté le janvier 7, 2026, [https://arxiv.org/abs/2301.13017](https://arxiv.org/abs/2301.13017)  
41. Einstein's Equations and the pseudo–Entropy of pseudo–Riemannian Information Manifolds \- arXiv, consulté le janvier 7, 2026, [https://arxiv.org/pdf/2301.13017](https://arxiv.org/pdf/2301.13017)  
42. Introduction to the Ryu-Takayanagi Formula, consulté le janvier 7, 2026, [https://theory.uchicago.edu/\~sethi/Teaching/P483-W2018/Intro%20to%20the%20RT.pdf](https://theory.uchicago.edu/~sethi/Teaching/P483-W2018/Intro%20to%20the%20RT.pdf)  
43. The Emergence of Time from Quantum Information Dynamics \- Scirp.org., consulté le janvier 7, 2026, [https://www.scirp.org/journal/paperinformation?paperid=137035](https://www.scirp.org/journal/paperinformation?paperid=137035)  
44. Essay: Emergent Holographic Spacetime from Quantum Information \- arXiv, consulté le janvier 7, 2026, [https://arxiv.org/html/2506.06595v2](https://arxiv.org/html/2506.06595v2)  
45. Space Emerging from Quantum Mechanics \- Sean Carroll, consulté le janvier 7, 2026, [https://www.preposterousuniverse.com/blog/2016/07/18/space-emerging-from-quantum-mechanics/](https://www.preposterousuniverse.com/blog/2016/07/18/space-emerging-from-quantum-mechanics/)  
46. Holographic Fisher information metric in Schrödinger spacetime ..., consulté le janvier 7, 2026, [https://www.researchgate.net/publication/356089036\_Holographic\_Fisher\_information\_metric\_in\_Schrodinger\_spacetime](https://www.researchgate.net/publication/356089036_Holographic_Fisher_information_metric_in_Schrodinger_spacetime)  
47. \[1701.02319\] Connecting Fisher information to bulk entanglement in holography \- arXiv, consulté le janvier 7, 2026, [https://arxiv.org/abs/1701.02319](https://arxiv.org/abs/1701.02319)  
48. Connecting Fisher information to bulk entanglement in holography \- arXiv, consulté le janvier 7, 2026, [https://arxiv.org/pdf/1701.02319](https://arxiv.org/pdf/1701.02319)  
49. Integral Geometry and Holography \- SLAC National Accelerator Laboratory, consulté le janvier 7, 2026, [https://www.slac.stanford.edu/pubs/slacpubs/16250/slac-pub-16293.pdf](https://www.slac.stanford.edu/pubs/slacpubs/16250/slac-pub-16293.pdf)  
50. Towards a Fisher-Information Description of Complexity in de Sitter Universe \- MDPI, consulté le janvier 7, 2026, [https://www.mdpi.com/2218-1997/5/12/221](https://www.mdpi.com/2218-1997/5/12/221)  
51. Tensor Network States and Geometry \- ResearchGate, consulté le janvier 7, 2026, [https://www.researchgate.net/publication/51910203\_Tensor\_Network\_States\_and\_Geometry](https://www.researchgate.net/publication/51910203_Tensor_Network_States_and_Geometry)  
52. Consistency Conditions for an AdS/MERA Correspondence \- arXiv, consulté le janvier 7, 2026, [https://arxiv.org/pdf/1504.06632](https://arxiv.org/pdf/1504.06632)  
53. arXiv:1502.05385v2 \[cond-mat.str-el\] 12 Sep 2015, consulté le janvier 7, 2026, [https://arxiv.org/pdf/1502.05385](https://arxiv.org/pdf/1502.05385)  
54. Geometric Structure of MERA networks: Relation to AdS/CFT Correspondence \- JICFuS, consulté le janvier 7, 2026, [https://www.jicfus.jp/field5/jp/wp-content/uploads/2015/05/SlideTN\_Matsueda\_20150514UT\_Kashiwa.pdf](https://www.jicfus.jp/field5/jp/wp-content/uploads/2015/05/SlideTN_Matsueda_20150514UT_Kashiwa.pdf)  
55. Fisher Information Metric from Holography and its Application to Scrambling, consulté le janvier 7, 2026, [https://www-gauge.scphys.kyoto-u.ac.jp/seminar/presen/Miyaji161026.pdf](https://www-gauge.scphys.kyoto-u.ac.jp/seminar/presen/Miyaji161026.pdf)  
56. The schematic structure of MERA. | Download Scientific Diagram \- ResearchGate, consulté le janvier 7, 2026, [https://www.researchgate.net/figure/The-schematic-structure-of-MERA\_fig1\_258849346](https://www.researchgate.net/figure/The-schematic-structure-of-MERA_fig1_258849346)  
57. Entanglement Renormalization and Holography | Request PDF \- ResearchGate, consulté le janvier 7, 2026, [https://www.researchgate.net/publication/45850494\_Entanglement\_Renormalization\_and\_Holography](https://www.researchgate.net/publication/45850494_Entanglement_Renormalization_and_Holography)  
58. Space from entanglement: An information-geometric perspective \- World Scientific Publishing, consulté le janvier 7, 2026, [https://www.worldscientific.com/doi/abs/10.1142/S0219887822500098](https://www.worldscientific.com/doi/abs/10.1142/S0219887822500098)  
59. (PDF) Generalized Fubini-Study Metric and Fisher Information Metric \- ResearchGate, consulté le janvier 7, 2026, [https://www.researchgate.net/publication/273640012\_Generalized\_Fubini-Study\_Metric\_and\_Fisher\_Information\_Metric](https://www.researchgate.net/publication/273640012_Generalized_Fubini-Study_Metric_and_Fisher_Information_Metric)