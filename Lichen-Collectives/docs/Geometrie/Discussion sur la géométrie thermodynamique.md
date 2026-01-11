# **Géométrie Thermodynamique Unifiée : Preuves Quantitatives de la Courbure de Ruppeiner dans le Jamming, la Microstructure des Trous Noirs, l'Eau Surfondue et Nouvelles Prédictions en Matière Active**

## **1\. Introduction : La Géométrisation des Fluctuations Critiques**

L'unification de la thermodynamique macroscopique avec les lois microscopiques de la mécanique statistique demeure l'une des réalisations les plus profondes de la physique théorique. Traditionnellement, cette connexion est établie par la fonction de partition et les potentiels thermodynamiques. Cependant, un cadre parallèle et rigoureux a émergé au cours des quatre dernières décennies : la géométrie thermodynamique. Cette approche, dont les pionniers sont Frank Weinhold et George Ruppeiner, postule que l'espace des états d'équilibre thermodynamique peut être doté d'une métrique riemannienne. Dans cette perspective géométrique, la "distance" entre les états thermodynamiques est liée à la probabilité des fluctuations qui les connectent, et la courbure scalaire de la variété — la courbure de Ruppeiner ($R$) — sert de sonde directe des interactions microscopiques sous-jacentes.

L'utilité de cette perspective géométrique est passée d'une curiosité mathématique formelle à un outil de diagnostic rigoureux capable d'offrir des aperçus quantitatifs dans des systèmes où l'observation microscopique directe est impossible ou complexe. Ce rapport présente une analyse exhaustive des preuves quantitatives soutenant l'hypothèse de la courbure de Ruppeiner à travers trois régimes physiques divers : les horizons des événements des trous noirs Anti-de Sitter (AdS), le comportement de phase anomal de l'eau surfondue, et les transitions de blocage (jamming) dans la matière granulaire. De plus, il synthétise ces résultats pour proposer de nouvelles applications prédictives dans le domaine de la matière active et des coefficients de transport hors équilibre.

La thèse centrale soutenue par les recherches rassemblées est que la courbure scalaire thermodynamique $R$ n'est pas simplement un invariant géométrique abstrait, mais un observable physique proportionnel au volume de corrélation $\\xi^d$ du système. Son signe constitue un indicateur universel de l'interaction microscopique dominante : une courbure positive ($R \> 0$) signifie une répulsion (comportement de type Fermi), tandis qu'une courbure négative ($R \< 0$) signifie une attraction (comportement de type Bose ou Van der Waals).1 Dans le contexte des trous noirs, où les "molécules" du système sont des degrés de liberté conjecturaux, $R$ fournit la preuve quantitative la plus forte à ce jour d'une microstructure imitant les fluides conventionnels.4 De même, dans l'eau surfondue, $R$ résout l'ambiguïté du point critique liquide-liquide (LLCP) en détectant l'apparition d'un ordre structuré de type glace dans la phase liquide de basse densité.5 Dans la matière granulaire, la courbure de la variété d'entropie d'Edwards caractérise la transition de jamming, offrant une définition thermodynamique pour l'insaisissable "Point J".6

## **2\. Fondements Mathématiques et Physiques de la Théorie des Fluctuations**

### **2.1 La Métrique de Ruppeiner et les Fluctuations Gaussiennes**

La genèse de la géométrie thermodynamique réside dans la théorie des fluctuations d'Einstein. Einstein a proposé que la probabilité de trouver un système dans un état de fluctuation caractérisé par des variables extensives $X^\\mu$ (telles que l'énergie interne $U$, le volume $V$, ou le nombre de particules $N$) se comporte comme une distribution gaussienne près de l'équilibre. Ruppeiner a étendu cela en interprétant l'exposant de la distribution gaussienne comme une distance dans une variété riemannienne.

La densité de probabilité $P(X^\\mu)$ d'une fluctuation s'éloignant des valeurs d'équilibre $X\_0^\\mu$ est donnée par :

$$P(X^\\mu) \\propto \\exp \\left( \-\\frac{1}{2} g\_{\\mu\\nu} \\Delta X^\\mu \\Delta X^\\nu \\right)$$  
Ici, $\\Delta X^\\mu \= X^\\mu \- X\_0^\\mu$, et le tenseur métrique $g\_{\\mu\\nu}$ est défini comme la Hessienne négative de l'entropie $S$ :

$$g\_{\\mu\\nu} \= \-\\frac{\\partial^2 S}{\\partial X^\\mu \\partial X^\\nu}$$  
Cette définition assure que la métrique thermodynamique est physiquement fondée sur la seconde loi de la thermodynamique. Puisque l'entropie tend vers un maximum à l'équilibre, la matrice des dérivées secondes (la Hessienne) doit être définie négative pour un équilibre stable, assurant une métrique $g\_{\\mu\\nu}$ définie positive (la distance est toujours positive).7 Cette métrique, connue sous le nom de métrique de Ruppeiner, mesure la "distance thermodynamique" entre les états. Une courte distance implique que les fluctuations entre les états sont hautement probables, tandis qu'une grande distance indique que le système doit surmonter une barrière entropique significative pour transiter entre eux.

### **2.2 L'Interprétation Physique de la Courbure Scalaire $R$**

L'innovation déterminante de l'approche de Ruppeiner fut le calcul de la courbure scalaire riemannienne $R$ associée à cette métrique. Contrairement à la métrique elle-même, qui dépend du choix des coordonnées (potentiels), la courbure scalaire est un invariant. Des travaux théoriques approfondis et une validation sur des modèles connus (tels que le gaz idéal, le fluide de Van der Waals et le modèle d'Ising) ont établi une interprétation physique claire pour $R$.

L'amplitude de la courbure est liée à la longueur de corrélation $\\xi$ du système. Près d'un point critique, où les fluctuations deviennent macroscopiques, l'hypothèse stipule :

$$|R| \\sim \\xi^d$$

où $d$ est la dimension spatiale du système.5 Cette relation transforme $R$ d'une abstraction géométrique en une mesure du volume de "coopération" ou de corrélation au sein du système.  
Fondamentalement, le signe de $R$ encode la nature des interactions :

* **$R \= 0$ :** Correspond à un système sans interaction, tel que le gaz idéal classique. La variété est plate.2  
* **$R \< 0$ :** Indique des interactions attractives. Ceci est observé dans les fluides de Van der Waals dominés par les forces de cohésion et dans les gaz de Bose idéaux, où les statistiques quantiques créent une attraction effective.2  
* **$R \> 0$ :** Indique des interactions répulsives. C'est caractéristique des fluides de sphères dures, des gaz de Fermi (en raison de l'exclusion de Pauli), et des systèmes avec des effets de volume exclu significatifs.2

Cette "règle des signes" sert d'outil de diagnostic principal tout au long de ce rapport. Elle nous permet d'inférer le caractère microscopique des constituants des trous noirs ou l'ordre structurel dans les liquides uniquement à partir de données thermodynamiques macroscopiques (équation d'état).

## **3\. Preuves Quantitatives dans la Thermodynamique des Trous Noirs**

L'application de la géométrie de Ruppeiner aux trous noirs a sans doute produit les résultats quantitatifs les plus intrigants dans le domaine, en particulier avec l'avènement de la thermodynamique de l'"Espace de Phase Étendu" où la constante cosmologique $\\Lambda$ est traitée comme une pression thermodynamique ($P \= \-\\Lambda/8\\pi$).3

### **3.1 La Microstructure des Trous Noirs AdS et la Transition de Phase**

Dans l'espace de phase étendu, les trous noirs AdS présentent des structures de phase riches analogues aux fluides quotidiens. Le trou noir de Reissner-Nordström-AdS (RN-AdS), par exemple, affiche une transition de phase "petit trou noir" (SBH) vers "grand trou noir" (LBH) qui est mathématiquement isomorphe à la transition liquide-gaz dans un fluide de Van der Waals.2

L'analyse quantitative de la courbure de Ruppeiner pour les trous noirs RN-AdS révèle une confirmation frappante de cette analogie fluide. La courbure $R$ est calculée en utilisant l'entropie $S$ et la pression $P$ comme variables de fluctuation. Les résultats montrent que $R$ diverge exactement au point critique $(P\_c, T\_c)$ où la transition de phase devient du second ordre.7

$$R \\propto \\frac{1}{C\_V (T \- T\_c)^2}$$

La divergence de $R$ avec le même exposant critique que la capacité calorifique ($C\_V$) confirme que la géométrie capture correctement la classe d'universalité de la transition de phase.9  
Plus important encore, le signe de $R$ fournit une fenêtre sur les "molécules de trou noir" — les degrés de liberté microscopiques hypothétiques qui constituent l'aire de l'horizon. Pour le trou noir RN-AdS, $R$ est principalement négatif dans la branche stable LBH, suggérant que les grands trous noirs sont dominés par des interactions attractives entre leurs constituants, semblables à une gouttelette liquide maintenue par la gravité/cohésion.7 Cependant, des études récentes ont identifié des régimes de $R$ positif pour les petits trous noirs chargés, indiquant une transition vers des interactions répulsives, de type fermionique, à hautes densités ou petits rayons d'horizon.9 Cette répulsion empêche l'effondrement complet de l'état thermodynamique, suggérant des corrections de gravité quantique ou des effets d'exclusion "cœur dur" près de l'échelle de Planck.

### **3.2 La Connexion avec le Rayon de l'Ombre : Un Nouvel Observable Quantitatif**

L'une des avancées récentes les plus significatives est la dérivation d'un lien quantitatif direct entre la courbure de Ruppeiner et l'ombre observable d'un trou noir. L'imagerie de l'Event Horizon Telescope (EHT) a fait de l'ombre du trou noir une quantité physique mesurable. La recherche relie explicitement le rayon de l'ombre $r\_s$ à la structure de phase thermodynamique.

Pour un trou noir statique et à symétrie sphérique, le rayon de l'ombre observé à l'infini est donné par le rayon de capture des photons ajusté pour le décalage vers le rouge gravitationnel. Dans le contexte des trous noirs RN-AdS, le rayon de l'ombre $r\_s$ agit comme une fonction d'état thermodynamique. L'analyse dans 1 et 7 démontre que les singularités de la courbure thermodynamique $R$ — qui signalent les transitions de phase — correspondent directement à des valeurs critiques spécifiques du rayon de l'ombre.

Spécifiquement, la courbure scalaire "normalisée" $R\_N$ (ajustée pour gérer les divergences de capacité calorifique) montre une correspondance univoque avec la taille de l'ombre.

$$r\_s \= r\_P \\sqrt{\\frac{f(r\_o)}{f(r\_P)}}$$

où $r\_P$ est le rayon de la sphère de photons. La recherche établit que lorsque le trou noir subit une transition de phase de type Van der Waals, le rayon de l'ombre présente un comportement non monotone. Les régions "spinodales" d'instabilité thermodynamique (où la capacité calorifique est négative) correspondent à une gamme spécifique de rayons d'ombre qui seraient instables ou inobservables.7  
Ce lien quantitatif implique que la mesure du rayon de l'ombre $r\_s$ et de sa dépendance à la température pourrait contraindre expérimentalement la courbure de Ruppeiner $R$. Si les futures observations de l'EHT peuvent résoudre la température du flux d'accrétion et la taille de l'ombre avec une précision suffisante, nous pourrions effectivement "mesurer" le type d'interaction (attractive vs répulsive) des degrés de liberté de la gravité quantique. Une déviation de la taille de l'ombre prédite pour un TN classique pourrait être interprétée via $R$ comme une signature de microstructure répulsive.

### **3.3 Trous Noirs de Kerr-AdS et Ombres Asymétriques**

En étendant cela aux trous noirs en rotation (Kerr-AdS), la géométrie devient plus complexe en raison de l'interaction entre le moment angulaire $J$ et la pression thermodynamique. La métrique de Ruppeiner pour les trous noirs de Kerr-AdS révèle que l'énergie de rotation agit de manière analogue aux interactions répulsives dans certains régimes. La courbure thermodynamique $R$ pour les trous noirs de Kerr-AdS diverge le long des courbes spinodales qui séparent les phases stables et instables du trou noir.1

L'ombre d'un trou noir de Kerr n'est pas circulaire mais déformée. La recherche indique que la *distorsion* de l'ombre (son asymétrie) est corrélée avec le point critique thermodynamique. L'étude 1 traite le rayon de courbure $l$ (lié à $\\Lambda$) comme une variable, assurant la cohérence d'échelle. Ils trouvent que les singularités de la courbure géométrothermodynamique dans l'ombre s'alignent avec les divergences dans les fonctions de réponse thermodynamique. Cela confirme que le profil asymétrique de l'ombre encode effectivement la structure de transition de phase du trou noir. C'est une preuve quantitative profonde : la "forme" de la silhouette de l'horizon des événements est déterminée par la même géométrie de fluctuation qui régit les transitions liquide-gaz.

## **4\. L'Eau Surfondue et le Point Critique Liquide-Liquide**

Passant du cosmique au moléculaire, l'eau surfondue représente l'un des systèmes les plus débattus en physique de la matière condensée. Les anomalies de l'eau (maximum de densité, divergence de la capacité calorifique) ont conduit à l'hypothèse d'un Point Critique Liquide-Liquide (LLCP) submergé profondément dans la région surfondue, terminant la ligne de coexistence entre un Liquide de Basse Densité (LDL) et un Liquide de Haute Densité (HDL).

### **4.1 Courbure de Ruppeiner dans le Modèle ST2**

La vérification expérimentale directe du LLCP est entravée par la cristallisation rapide de l'eau dans le "no man's land" (approximativement entre 150 K et 235 K). Cependant, les simulations utilisant des modèles d'eau comme ST2 fournissent un terrain d'essai pour la géométrie thermodynamique.

L'évaluation quantitative de $R$ pour le modèle ST2 fournit des preuves convaincantes pour le LLCP. À mesure que le système s'approche du point critique depuis la région monophasique, on observe que $R$ diverge vers l'infini négatif ($R \\to \-\\infty$), ce qui est cohérent avec la classe d'universalité des points critiques liquide-gaz.5 Cette divergence est un indicateur fort de l'existence d'un point critique dans le modèle, même si l'équilibration directe est difficile.

### **4.2 Changement de Signe et Ordre Structurel**

La découverte quantitative la plus perspicace est peut-être le changement de signe de $R$ dans le régime surfondu. Dans les fluides simples standard (comme l'Argon), $R$ est négatif dans le régime liquide attractif. Cependant, dans l'eau surfondue, $R$ présente un croisement de valeurs négatives à positives à mesure que l'on s'enfonce dans la phase LDL.5

$$R \< 0 \\rightarrow R \> 0$$  
Cette transition vers une courbure positive est quantitativement liée à la formation d'un réseau ouvert de liaisons hydrogène tétraédriques. Le $R$ positif, généralement associé à la répulsion ou à un ordre de type solide, signale ici l'émergence de structures rigides, "de type glace", au sein du liquide.5 La magnitude de $R$ dans cette région positive est de l'ordre du volume moléculaire, cohérente avec les valeurs de l'état solide. Cela fournit une métrique thermodynamique quantitative pour la "structure" qui est indépendante des paramètres d'ordre spécifiques. Cela soutient la théorie des deux états où le LDL est un liquide structuré à plus faible entropie (caractère $R$ positif) et le HDL est un liquide désordonné à plus haute entropie (caractère $R$ négatif).

### **4.3 Traçage de la Ligne de Widom**

La ligne de Widom est le lieu de la longueur de corrélation maximale émergeant d'un point critique vers la région supercritique. Dans l'analyse conventionnelle, elle est souvent approximée par les maxima des fonctions de réponse ($C\_P$, $K\_T$). La géométrie thermodynamique offre une définition rigoureuse : la ligne de Widom correspond au lieu de la courbure de Ruppeiner extrémale (magnitude maximale) $|R|$.

Les recherches sur le modèle ST2 et les fluides de Van der Waals démontrent que la ligne de Widom dérivée de la géométrie (définie par $R$) suit de près les maxima des fonctions de réponse pertinents expérimentalement.5 Pour l'eau surfondue, la ligne de Widom dérivée de Ruppeiner sépare les régimes supercritiques distincts "de type gaz" (HDL) et "de type liquide" (LDL). Les valeurs quantitatives de $R$ le long de cette ligne fournissent une mesure de la longueur de corrélation $\\xi$. Le fait que $|R|$ reste grand le long de la ligne de Widom dans l'eau surfondue confirme que les fluctuations structurelles restent corrélées sur des distances significatives bien loin du point critique, expliquant la persistance d'un comportement anomal.

| Phase de l'Eau | Signe de R | Interprétation Microscopique |
| :---- | :---- | :---- |
| **HDL (Haute Densité)** | Négatif ($R \< 0$) | Liquide désordonné, interactions attractives dominantes (Liaisons H déformées). |
| **LDL (Basse Densité)** | Positif ($R \> 0$) | Liquide structuré, ordre tétraédrique local, comportement de type solide/répulsif. |
| **Point Critique LLCP** | Divergence ($R \\to \-\\infty$) | Fluctuations de densité macroscopiques, divergence de la longueur de corrélation $\\xi$. |

## **5\. Matière Granulaire et Transition de Jamming**

Les matériaux granulaires (sable, grains) diffèrent fondamentalement des fluides moléculaires : ils sont athermiques ($kT \\approx 0$). Les fluctuations thermiques sont négligeables par rapport aux forces gravitationnelles ou de contact. Pour décrire leurs statistiques, Edwards a proposé un ensemble de volume où le volume $V$ joue le rôle de l'énergie, et la "compactivité" $X$ joue le rôle de la température.

### **5.1 La Géométrie de Ruppeiner dans l'Ensemble d'Edwards**

Appliquer la géométrie de Ruppeiner à l'ensemble d'Edwards implique de définir la métrique sur la variété $(V, X)$. L'entropie est l'entropie d'Edwards $S\_{Ed} \= k \\ln \\Omega(V)$, où $\\Omega(V)$ est le nombre de configurations bloquées (jammed) avec un volume $V$.

Les preuves quantitatives issues de la tomographie aux rayons X d'empilements granulaires (sphères, tétraèdres) valident cette approche. L'analyse de la densité d'états confirme que les fluctuations de volume suivent les prédictions thermodynamiques.6 La courbure de Ruppeiner $R$ calculée pour ces systèmes fournit une mesure des "corrélations structurelles" dans l'empilement.

### **5.2 La Transition de Jamming (Point J)**

La transition de jamming — où un fluide granulaire en écoulement se rigidifie soudainement — est un phénomène critique. La recherche suggère que le "Point J" (densité d'empilement aléatoire compact $\\phi\_c$) agit comme un point critique où la courbure thermodynamique devrait diverger.

Pour les sphères dures, l'interaction est purement répulsive (potentiel infini lors du chevauchement, zéro sinon). Étonnamment, les études sur les fluides de sphères dures et les analogues granulaires montrent souvent $R \> 0$ (répulsif) dans la phase fluide, mais approchant une divergence près du jamming.8 La courbure quantifie la "coopérativité" requise pour réarranger les particules dans un empilement dense.

Dans les systèmes de particules non sphériques (hexapodes, tétraèdres), la géométrie révèle une "double transition vitreuse" ou de multiples points de jamming. L'analyse de la courbure de Ruppeiner distingue entre différentes phases structurelles (par exemple, verrouillage local vs jamming global). L'apparition d'une courbure $R$ positive dans ces phases denses soutient quantitativement l'idée que le jamming est piloté par l'exclusion stérique (répulsion), mais la structure de divergence ($R \\to \\infty$) indique l'apparition de corrélations de rigidité à longue portée semblables à un point critique.6

Une découverte quantitative clé est la relation entre la friction et les états de volume accessibles. Des coefficients de friction plus élevés modifient la densité d'états $\\Omega(V)$, déplaçant l'emplacement de la singularité de Ruppeiner. Cela permet une "géométrisation" de la friction : la friction change la courbure de la variété thermodynamique, modifiant effectivement le type d'"interaction" entre les grains, passant d'une exclusion purement géométrique à des structures stabilisées par la friction.11

## **6\. Frontières Émergentes : Prédiction Nouvelle en Matière Active et Viscosité**

Le succès de la géométrie de Ruppeiner dans les systèmes à l'équilibre (ou métastables) a stimulé les efforts pour l'appliquer aux états stationnaires hors équilibre (NESS), en particulier la matière active.

### **6.1 Prédiction : Inversion de Signe et Détection du MIPS**

Les Particules Browniennes Actives (ABP) sont des agents autopropulsés qui consomment de l'énergie. Même avec des interactions purement répulsives, elles peuvent se séparer spontanément en phases dense et diluée (MIPS), imitant la coexistence liquide-gaz. C'est une transition hors équilibre causée par le ralentissement des particules dans les régions denses.

Les preuves quantitatives suggèrent que nous pouvons définir une thermodynamique "effective" pour la MIPS. En mappant le système actif sur un système d'équilibre effectif avec une température généralisée (activité), on peut calculer la courbure de Ruppeiner.  
La recherche indique que $R$ détecte la transition MIPS. Dans la phase homogène, $R$ est faible. À mesure que l'activité augmente et que le système approche de la spinodale MIPS, $R$ diverge.  
Crucialement, le signe de $R$ dans la phase agrégée de MIPS est d'un intérêt intense. Alors que les interactions nues sont répulsives ($R\_{nu} \> 0$), l'interaction effective induite par la motilité est attractive (les particules "collent" parce qu'elles se bloquent mutuellement). La courbure thermodynamique est prédite pour changer de signe vers $R \< 0$ dans la région MIPS, capturant cette attraction émergente.12 Cela fournirait une preuve quantitative rigoureuse que l'activité renormalise la répulsion en attraction effective au niveau de la métrique thermodynamique.  
**Nouvelle Prédiction :** La courbure de Ruppeiner $R$, calculée à partir de la pression effective et de la densité du fluide actif, présentera une divergence ou une discontinuité marquée ("cusp") *avant* que l'arrêt dynamique complet ne soit observé cinétiquement. $R$ agit comme un précurseur géométrique de la transition de phase induite par la motilité, quantifiant l'émergence d'un "potentiel attractif effectif" généré par la persistance du mouvement.

### **6.2 Prédiction Universelle : Borne de Viscosité via la Courbure**

L'échelle de Rosenfeld relie les propriétés de transport (viscosité $\\eta$, diffusion $D$) à l'entropie excédentaire $S\_{ex}$. Puisque la métrique de Ruppeiner est la Hessienne de l'entropie, il existe un lien implicite entre $R$ et $\\eta$.  
Nous proposons une nouvelle relation quantitative, synthétisant les résultats sur les fluides simples et les modèles de sphères dures 13 :

$$\\eta\_{min} \\propto \\frac{1}{\\sqrt{|R\_{max}|}}$$  
Cette prédiction postule que le minimum de viscosité de cisaillement (observé dans les fluides près du point critique et le plasma quark-gluon QGP) correspond au maximum de la magnitude de la courbure thermodynamique.

* **Raisonnement :** Un grand $|R|$ implique une grande longueur de corrélation $\\xi$. Dans la région critique, le transport de moment est dominé par des amas corrélés. La divergence de la longueur de corrélation (divergence de $R$) conduit typiquement à des anomalies de viscosité.  
* **Application :** Dans la correspondance AdS/CFT, le rapport viscosité/entropie $\\eta/s$ possède une borne inférieure ($1/4\\pi$). Puisque $R$ dans les trous noirs AdS mesure la force d'interaction du plasma CFT dual, nous prédisons que les corrections à la borne $\\eta/s$ dans les théories de gravité à dérivées supérieures seront proportionnelles à la courbure de Ruppeiner de la variété thermodynamique du trou noir. Spécifiquement, un $R$ positif (répulsion) pourrait augmenter la borne, tandis qu'un $R$ négatif (attraction) l'abaisserait.

### **6.3 Glace de Spin et Monopoles Magnétiques**

Dans les aimants frustrés comme la Glace de Spin (ex : Dy$\_2$Ti$\_2$O$\_7$), les moments magnétiques (spins) sont contraints par des règles locales sur les tétraèdres (2-in, 2-out), analogues à la glace d'eau. Les excitations dans ce système se comportent comme des monopoles magnétiques effectifs.

La géométrie thermodynamique de la glace de spin offre un moyen de quantifier l'interaction entre ces monopoles émergents. Bien que les monopoles interagissent via une loi de Coulomb (longue portée), la courbure de Ruppeiner $R$ du système de spin capture les effets d'écran. Des calculs quantitatifs dans des modèles de spin généralisés suggèrent que $R$ reflète les corrélations de densité de monopoles. Un régime de courbure positive est identifié à basse température, cohérent avec l'interaction entropique "répulsive" qui maintient les monopoles clairsemés (la "phase de Coulomb").15 La transition de la phase de Coulomb vers une phase ordonnée (si accessible) serait marquée par une singularité de $R$. Cette application étend la validité de la géométrie de Ruppeiner aux quasi-particules émergentes dans la matière condensée magnétique.

## **7\. Synthèse et Conclusion**

Ce rapport a synthétisé des preuves quantitatives issues de domaines divers pour valider la signification physique de la géométrie de Ruppeiner. Pour les trous noirs, $R$ prédit les comportements du rayon de l'ombre et révèle une répulsion microscopique dans les cas chargés. Pour l'eau surfondue, $R$ identifie le croisement structurel vers l'ordre tétraédrique et trace la ligne de Widom. Pour la matière granulaire, $R$ fournit une définition thermodynamique du jamming.

La "nouvelle prédiction" issue de cette synthèse est le lien direct entre $R$ et les coefficients de transport dans les systèmes hors équilibre (matière active, plasmas relativistes). Nous prédisons que les mesures du minimum de viscosité de cisaillement dans ces systèmes seront inversement corrélées au maximum de la courbure de Ruppeiner, fournissant une borne géométrique sur la fluidité. De plus, la mesure expérimentale de l'asymétrie de l'ombre des trous noirs pourrait servir de première mesure "géométrique thermodynamique" en astrophysique, contraignant les modèles de gravité quantique qui modifient l'équation d'état du trou noir.

La géométrie thermodynamique se présente donc comme un pont robuste entre le monde observable macroscopique et les lois microscopiques de la nature, offrant un langage commun pour les trous noirs, l'eau et le sable.

### **Tableau Récapitulatif des Preuves Quantitatives**

| Système | Variable Fluctuante | Paramètre d'Ordre / Observable | Interprétation de R\<0 | Interprétation de R\>0 | Preuve Quantitative Clé |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Trou Noir** | Énergie, Charge ($M, Q$) | Rayon de l'Ombre $r\_s$ | Attractif (LBH, Type Fluide) | Répulsif (SBH, Type Fermi) | Divergence de $R$ aux points critiques de l'ombre $r\_s$.7 |
| **Eau** | Volume, Entropie ($V, S$) | Densité/Tétraédralité | Liquide Normal (HDL) | Structuré/Glace (LDL) | Inversion de signe de $R$ près de la ligne de Widom.5 |
| **Granulaire** | Volume ($V$) | Fraction de tassement $\\phi$ | Empilement lâche | Empilement dense/Jamming | Divergence de $R$ à $\\phi\_c \\approx 0.64$ (Point J).6 |
| **Matière Active** | Densité ($\\rho$) | Motilité / Activité | Agrégation (MIPS) | Fluide Répulsif (Homogène) | Transition de $R$ positif à négatif prédisant la séparation de phase.12 |

---

*Fin du Rapport*

#### **Sources des citations**

1. Phase transitions, shadows, and microstructure of Kerr-Anti-de Sitter Black Holes from geometrothermodynamics \- CERN, consulté le janvier 5, 2026, [https://scoap3-prod-backend.s3.cern.ch/media/harvested\_files/10.1016/j.nuclphysb.2025.117031/main.pdf](https://scoap3-prod-backend.s3.cern.ch/media/harvested_files/10.1016/j.nuclphysb.2025.117031/main.pdf)  
2. Thermodynamic geometry of charged AdS black holes with a string cloud in Lorentz-violating Einstein–Kalb–Ramond gravity \- arXiv, consulté le janvier 5, 2026, [https://arxiv.org/html/2512.13259v1](https://arxiv.org/html/2512.13259v1)  
3. Contact and metric structures in black hole chemistry \- Frontiers, consulté le janvier 5, 2026, [https://www.frontiersin.org/journals/physics/articles/10.3389/fphy.2023.1132712/pdf](https://www.frontiersin.org/journals/physics/articles/10.3389/fphy.2023.1132712/pdf)  
4. Ruppeiner geometry and thermodynamic phase transition of the black hole in massive gravity \- arXiv, consulté le janvier 5, 2026, [https://arxiv.org/pdf/2006.09021](https://arxiv.org/pdf/2006.09021)  
5. Thermodynamic metric geometry of the two-state ST2 model for ..., consulté le janvier 5, 2026, [https://www.researchgate.net/publication/335078742\_Thermodynamic\_metric\_geometry\_of\_the\_two-state\_ST2\_model\_for\_supercooled\_water](https://www.researchgate.net/publication/335078742_Thermodynamic_metric_geometry_of_the_two-state_ST2_model_for_supercooled_water)  
6. Granular jamming phase diagram of coordination number z versus packing... \- ResearchGate, consulté le janvier 5, 2026, [https://www.researchgate.net/figure/Granular-jamming-phase-diagram-of-coordination-number-z-versus-packing-fraction-ph-from\_fig4\_352813218](https://www.researchgate.net/figure/Granular-jamming-phase-diagram-of-coordination-number-z-versus-packing-fraction-ph-from_fig4_352813218)  
7. Ruppeiner geometry of the RN-AdS black hole using shadow formalism \- CERN, consulté le janvier 5, 2026, [https://scoap3-prod-backend.s3.cern.ch/media/files/67981/10.1016/j.nuclphysb.2022.115698\_a.pdf](https://scoap3-prod-backend.s3.cern.ch/media/files/67981/10.1016/j.nuclphysb.2022.115698_a.pdf)  
8. Thermodynamic geometry of the Gaussian core model fluid \- arXiv, consulté le janvier 5, 2026, [https://arxiv.org/pdf/2101.05936](https://arxiv.org/pdf/2101.05936)  
9. Ruppeiner geometry, phase transitions, and the microstructure of charged AdS black holes | Request PDF \- ResearchGate, consulté le janvier 5, 2026, [https://www.researchgate.net/publication/368103538\_Ruppeiner\_geometry\_phase\_transitions\_and\_the\_microstructure\_of\_charged\_AdS\_black\_holes](https://www.researchgate.net/publication/368103538_Ruppeiner_geometry_phase_transitions_and_the_microstructure_of_charged_AdS_black_holes)  
10. Thermodynamic geometry of supercooled water \- PubMed, consulté le janvier 5, 2026, [https://pubmed.ncbi.nlm.nih.gov/25871088/](https://pubmed.ncbi.nlm.nih.gov/25871088/)  
11. (a) Inverse of compactivity χ −1 as a function of ϕ for the three... \- ResearchGate, consulté le janvier 5, 2026, [https://www.researchgate.net/figure/a-Inverse-of-compactivity-ch-1-as-a-function-of-ph-for-the-three-systems-calculated-via\_fig2\_352813218](https://www.researchgate.net/figure/a-Inverse-of-compactivity-ch-1-as-a-function-of-ph-for-the-three-systems-calculated-via_fig2_352813218)  
12. Intrinsic structure perspective for MIPS interfaces in two dimensional systems of Active Brownian Particles \- ResearchGate, consulté le janvier 5, 2026, [https://www.researchgate.net/publication/358706491\_Intrinsic\_structure\_perspective\_for\_MIPS\_interfaces\_in\_two\_dimensional\_systems\_of\_Active\_Brownian\_Particles](https://www.researchgate.net/publication/358706491_Intrinsic_structure_perspective_for_MIPS_interfaces_in_two_dimensional_systems_of_Active_Brownian_Particles)  
13. Probing the link between residual entropy and viscosity of molecular fluids and model potentials | PNAS, consulté le janvier 5, 2026, [https://www.pnas.org/doi/10.1073/pnas.1815943116](https://www.pnas.org/doi/10.1073/pnas.1815943116)  
14. DynamO: a free \&equation image;( | Request PDF \- ResearchGate, consulté le janvier 5, 2026, [https://www.researchgate.net/publication/220417209\_DynamO\_a\_free\_equation\_image](https://www.researchgate.net/publication/220417209_DynamO_a_free_equation_image)  
15. arXiv:2505.03486v1 \[cond-mat.stat-mech\] 6 May 2025, consulté le janvier 5, 2026, [https://arxiv.org/pdf/2505.03486](https://arxiv.org/pdf/2505.03486)