# Impact de la géométrie sur les phénomènes physiques : fondements, modèles et mesures expérimentales

---

## Introduction

La géométrie joue un rôle fondamental dans la compréhension et la modélisation des phénomènes physiques. Qu’il s’agisse de la structure des réseaux atomiques, de la forme des cavités optiques, de la topologie des bandes électroniques ou de la chiralité des objets, la géométrie impose des contraintes, génère des effets nouveaux et façonne les propriétés observables des systèmes. Ce rapport propose une synthèse rigoureuse et factuelle de l’impact de la géométrie dans divers domaines de la physique contemporaine, en s’appuyant exclusivement sur les résultats établis dans la littérature scientifique. Chaque axe thématique est structuré autour de trois points : (1) la géométrie impliquée, (2) les équations ou modèles associés, (3) les effets physiques mesurés, avec des exemples concrets, des tableaux comparatifs, des formules analytiques et des cas expérimentaux documentés. Des questions ouvertes, issues des tendances observées, concluent chaque section, sans spéculation.

---

## 1. Géométrie des réseaux et frustration magnétique

### 1.1 Géométrie impliquée

Les réseaux géométriquement frustrés sont des structures où la topologie empêche la minimisation simultanée de toutes les interactions locales. Les exemples emblématiques incluent les réseaux triangulaires, kagomé, pyrochlore et honeycomb【0】【43】【47】【40】. Dans le réseau kagomé, chaque site est connecté à ses voisins par des triangles partageant leurs sommets, générant une frustration magnétique intrinsèque. Les composés tels que La₃Cu₂VO₉, Herbertsmithite (ZnCu₃(OH)₆Cl₂), et Zn-barlowite (ZnCu₃(OH)₆FBr) illustrent la diversité des géométries et des effets associés【0】【54】【51】.

### 1.2 Modèles et équations associés

Le modèle de Heisenberg antiferromagnétique est la base de la description des réseaux frustrés :

\[
\mathcal{H} = -J \sum_{\langle i,j \rangle} \vec{S}_i \cdot \vec{S}_j
\]

Pour les agrégats de La₃Cu₂VO₉, la modélisation inclut plusieurs constantes d’échange intra-agrégat (J₁, J₂, J₃, J₄)【0】. Les interactions de Dzyaloshinskii-Moriya (DM) sont également cruciales dans les réseaux kagomé :

\[
H_{DM} = \sum_{\langle i,j \rangle} \mathbf{D}_{ij} \cdot (\mathbf{S}_i \times \mathbf{S}_j)
\]

La frustration se manifeste par la dégénérescence des états de basse énergie et la sélection entropique, comme dans le kagomé【35】【27】.

### 1.3 Effets physiques mesurés

Les mesures expérimentales révèlent des anomalies thermodynamiques, des plateaux d’aimantation, des excitations collectives et l’absence d’ordre magnétique à basse température【0】【54】【51】. Par exemple, dans La₃Cu₂VO₉, une anomalie autour de 2 K est observée en chaleur spécifique et susceptibilité, suggérant des corrélations à courte portée. Les isothermes magnétiques montrent des plateaux d’aimantation et des niveaux d’énergie discrets (ΔE ≈ 7.4 meV). La diffusion inélastique de neutrons révèle des excitations magnétiques à ≈ 8.7 meV. Les simulations numériques (Monte Carlo, DMRG) confirment la robustesse des modèles et la présence de phases exotiques telles que les liquides de spins et les glaces de spins【31】【50】【42】【46】.

#### Tableau comparatif : géométries de réseaux et frustration

| Réseau         | Coordination | Frustration | Ordre magnétique | Exemples expérimentaux         |
|----------------|--------------|-------------|------------------|-------------------------------|
| Triangulaire   | 6            | Forte       | Néel frustré     | Cs₂CuCl₄, Ba₃CoSb₂O₉          |
| Kagomé         | 4            | Très forte  | Absente (QSL)    | Herbertsmithite, Zn-barlowite |
| Pyrochlore     | 6            | Extrême     | Glace de spins   | Dy₂Ti₂O₇, Ho₂Ti₂O₇            |
| Honeycomb      | 3            | Modérée     | Néel, QSL        | Na₂IrO₃, α-RuCl₃              |

Les réseaux kagomé et pyrochlore sont particulièrement étudiés pour leur capacité à héberger des états quantiques fortement corrélés et des excitations fractionnaires【54】【51】【53】.

### 1.4 Questions ouvertes

- Quelle est l’origine microscopique exacte de la coexistence entre moments statiques et dynamiques dans les réseaux kagomé frustrés【32】?
- Comment la distorsion du réseau influence-t-elle la stabilité des plateaux de magnétisation fractionnaires et des phases exotiques【47】?

---

## 2. Bandes plates : définitions, constructions et exemples moiré

### 2.1 Géométrie impliquée

Les bandes plates sont des régions du spectre électronique où l’énergie ne dépend pas du moment, résultant en une densité d’états élevée et des interactions renforcées【1】【14】【18】【28】【38】【49】. Elles apparaissent dans les réseaux kagomé, les bicouches de graphène tordu (TBG), les hétérostructures moirées de TMD (tMoTe₂, tWSe₂), et les modèles de Harper-Hofstadter【14】【49】【52】【45】.

Dans le graphène bilayer tordu, le motif moiré généré par un petit angle de torsion crée une superstructure périodique, élargissant la maille unitaire et modifiant la mini-zone de Brillouin【11】【49】.

### 2.2 Modèles et équations associés

Le modèle de Bistritzer-MacDonald pour TBG :

\[
H = \begin{pmatrix}
0 & D(r) \\
D^\dagger(-r) & 0
\end{pmatrix}
\]
avec
\[
D(r) = \begin{pmatrix}
-i\bar{\partial} & \alpha U(r) \\
\alpha U(-r) & -i\bar{\partial}
\end{pmatrix}
\]

Le Hamiltonien moiré pour tMoTe₂【18】 :

\[
H = \begin{bmatrix}
-\frac{(k - K_t + eA)^2}{2m^*} + \Delta_t(r) + \epsilon & \Delta_T(r) \\
\Delta_T^\dagger(r) & -\frac{(k - K_b - eA)^2}{2m^*} + \Delta_b(r) + \epsilon
\end{bmatrix}
\]

La construction de bandes plates topologiques repose sur la symétrie chirale et la classification des points nodaux【14】【38】.

### 2.3 Effets physiques mesurés

Les bandes plates moirées hébergent des états corrélés : supraconductivité, isolants de Mott, effet Hall quantique anormal (QAH), isolants de Chern fractionnaires (FCI)【18】【28】【45】【52】. Dans tMoTe₂ à 3.15°, des bandes plates topologiques avec nombre de Chern C = +1 sont observées, accompagnées de plateaux quantifiés de Hall et de transitions de phase induites par champ électrique ou magnétique. Dans TBG, la supraconductivité émerge aux angles magiques, avec un diagramme de phase similaire aux cuprates【49】【45】【52】.

#### Tableau comparatif : propriétés des bandes plates moirées

| Système         | Angle de torsion | Largeur de bande | Nombre de Chern | Phases observées           | Température critique |
|-----------------|------------------|------------------|-----------------|----------------------------|---------------------|
| tMoTe₂          | 3.15°            | 8–15 meV         | +1, −1          | QAH, FQAH, FCI, métal      | 4–10 K              |
| TBG             | ~1.1°            | <10 meV          | variable        | Supraconducteur, Mott      | 1–5 K               |
| tWSe₂           | 3.65°–5°         | ~10 meV          | ±1              | Supraconducteur, AFM       | 0.2–0.4 K           |

Les mesures de transport, RMCD, spectroscopie ARPES et calculs DFT/DMRG confirment la présence de bandes plates et d’états topologiques【18】【28】【45】【52】.

### 2.4 Questions ouvertes

- Quels sont les mécanismes microscopiques permettant la stabilisation de bandes plates à dégénérescence élevée dans les systèmes moirés【14】?
- Comment la symétrie chirale influence-t-elle la robustesse des bandes plates face aux perturbations externes【14】?

---

## 3. Cavités photoniques et électrodynamique quantique de cavité (CQED)

### 3.1 Géométrie impliquée

Les cavités photoniques sont des structures confinant les modes électromagnétiques, typiquement des microcavités Fabry–Pérot, des cavités plasmoniques ou des résonateurs supraconducteurs【15】【41】【8】【13】【19】【56】【57】. La géométrie (plan, sphère, cylindre, nanoparticule) détermine le spectre des modes et le régime de couplage.

### 3.2 Modèles et équations associés

Le modèle de Jaynes–Cummings (JCM) décrit l’interaction d’un système à deux niveaux avec un mode de cavité :

\[
\hat{H}_{JC} = \hbar \omega_c a^\dagger a + \hbar \omega_0 \sigma^z + \hbar g (\sigma^\dagger a + \sigma a^\dagger)
\]

Dans le régime ultrastrong (USC), le modèle de Rabi quantique s’impose :

\[
\hat{H}_R = \frac{\omega_a}{2} \sigma_z + \omega_c a^\dagger a + g (a + a^\dagger)(\sigma^+ + \sigma^-)
\]

La séparation de Rabi (splitting) est donnée par :

\[
\Omega_R = \sqrt{\delta_c^2 + 4N g_c^2}
\]

Le modèle de Hopfield généralise à N systèmes couplés collectivement :

\[
\hat{H}_{Hop} = \hbar \omega_c a^\dagger a + \hbar \omega_0 (b^\dagger b - N/2) + \hbar \Omega_R \sqrt{N} (a^\dagger + a)(J^- + J^+) + D(a^\dagger + a)^2
\]

### 3.3 Effets physiques mesurés

Les expériences montrent la formation d’états polaritoniques (hybrides lumière–matière), la modification des taux de transfert électronique, la production de photons virtuels en régime USC, et des effets non linéaires tels que la conversion de fréquence et la génération de photons réels par modulation Floquet【15】【41】【8】【13】【19】【56】【57】.

Dans les microcavités Fabry–Pérot, la réflectivité et la photoluminescence révèlent l’anticroisement caractéristique du couplage fort【48】. Les mesures de spectroscopie infrarouge et Raman confirment la séparation de Rabi et la formation de polaritons vibrationnels【21】【41】.

#### Tableau comparatif : régimes de couplage et effets physiques

| Régime de couplage | Ratio \( g/\omega_c \) | Modèle | Effets observés                        | Plateformes expérimentales         |
|--------------------|-----------------------|--------|----------------------------------------|------------------------------------|
| Faible             | <0.1                  | JCM    | Effet Purcell, polaritons simples      | Atomes, molécules organiques       |
| Fort               | 0.1–1                 | Hopfield| Splitting de Rabi, polaritons collectifs| Microcavités, TMD, supraconducteurs|
| Ultrastrong (USC)  | 0.1–1                 | Rabi   | Photons virtuels, non-linéarités       | Circuits QED, plasmonique, TMD     |
| Deep-strong (DSC)  | ≥1                    | Rabi   | États de Schrödinger chat, transitions | Circuits supraconducteurs          |

### 3.4 Questions ouvertes

- Dans quelle mesure les photons virtuels présents dans l’état fondamental des systèmes en régime USC peuvent-ils être détectés expérimentalement sans perturber le système【8】【56】?
- Comment la géométrie de la cavité influence-t-elle la structure des niveaux et les taux de couplage effectifs dans les processus non-linéaires【13】【41】?

---

## 4. Confinement et chimie en cavité

### 4.1 Géométrie impliquée

La chimie en cavité concerne les réactions chimiques modifiées par le confinement dans une cavité optique, typiquement Fabry–Pérot ou plasmonique【10】【21】【41】. Les molécules sont insérées entre deux miroirs, et la fréquence du mode de cavité est ajustée pour résonner avec une transition vibrationnelle ou électronique.

### 4.2 Modèles et équations associés

Le couplage fort vibrationnel (VSC) est modélisé par la théorie de Marcus–Levich–Jortner pour les taux de transfert :

\[
k = \frac{2\pi}{\hbar} |V|^2 \frac{1}{\sqrt{4\pi \lambda k_B T}} \exp\left[ -\frac{(\Delta G + \lambda)^2}{4 \lambda k_B T} \right]
\]

La séparation de Rabi est :

\[
\Omega = 2\sqrt{N}g
\]

La température critique pour la population majoritaire dans le polariton inférieur :

\[
T_c = \frac{\Omega}{2k_B \ln(N - 1)}
\]

### 4.3 Effets physiques mesurés

Des modifications de taux de réaction, de sélectivité et de mécanisme sont observées sous VSC【10】【21】【41】. Par exemple, la déprotection d’un alkylsilane sous VSC de la vibration Si–C voit son taux diminuer d’un facteur 5.5. La cyclisation de Prins montre une augmentation de l’enthalpie d’activation ΔH‡ sous VSC. La photoisomérisation de la spiropyrane est ralentie par le couplage fort. Des effets coopératifs solvant–réactif accélèrent certaines réactions. Les réactions enzymatiques et l’auto-assemblage de matériaux (ZIF-8) sont également influencés.

#### Tableau comparatif : effets du VSC sur la réactivité

| Réaction                  | VSC ciblé      | Effet observé                 | ΔH‡ (kJ/mol) | ΔS‡ (J/mol·K) |
|---------------------------|----------------|-------------------------------|--------------|---------------|
| Déprotection alkylsilane  | Si–C           | Taux diminué ×5.5             | —            | —             |
| Cyclisation de Prins      | C=O            | ΔH‡ augmenté, taux diminué    | 19.2→30.9    | −251→−222     |
| Solvolyse PNPA            | C=O (solvant)  | Taux accéléré                 | —            | —             |
| Photoisomérisation        | Excité (SP)    | Ralentie                      | —            | —             |
| Synthèse ZIF-8            | OH (eau)       | Sélectivité accrue            | —            | —             |

### 4.4 Questions ouvertes

- Quels sont les mécanismes microscopiques précis permettant à certains systèmes sous couplage fort collectif de modifier la réactivité chimique alors que d’autres ne montrent aucun effet mesurable【41】?
- Comment optimiser la géométrie des cavités pour maximiser les effets de couplage fort tout en minimisant les pertes dissipatives【41】?

---

## 5. Effet Casimir et géométrie des cavités

### 5.1 Géométrie impliquée

L’effet Casimir est observé entre deux plaques conductrices parallèles, mais il existe aussi pour des géométries sphériques, cylindriques ou anisotropes【2】【12】【16】【22】. Les expériences utilisent souvent des miroirs ou des cristaux biréfringents.

### 5.2 Modèles et équations associés

La force de Casimir à température nulle entre deux plaques de surface A séparées par une distance L :

\[
F = -\frac{\pi^2}{240} \frac{\hbar c}{L^4} A
\]

À température finie :

\[
F = -\frac{\pi^2 \hbar c}{240 L^4} - \frac{\pi^2}{45 \hbar^3 c^3 \beta^4} + \frac{1}{\beta L^3} \cdot \text{(terme négligeable)}
\]

Pour des objets anisotropes, un couple de Casimir apparaît, induisant une rotation vers la position d’énergie minimale.

### 5.3 Effets physiques mesurés

Les mesures expérimentales ont confirmé la force attractive de Casimir avec une précision croissante : 100 % (Spaarnay, 1958), 25 % (van Blokland et Overbeeck, 1978), 1 % (Mohideen et al., 1990s)【2】【16】【12】【22】. Un couple de Casimir a été mesuré en 2018 entre un cristal biréfringent et un cristal liquide. La transmission de phonons à travers le vide par effet Casimir a été observée (Berkeley, 2019).

#### Tableau comparatif : configurations et effets Casimir

| Configuration             | Formule de la force                   | Conditions                | Effets mesurés                          |
|---------------------------|---------------------------------------|---------------------------|-----------------------------------------|
| Plaques parallèles        | \(-\frac{\pi^2}{240} \frac{\hbar c}{L^4}\) | T = 0, plaques parfaites  | Force attractive (précision 1 %)        |
| Température finie         | Formule complète ci-dessus            | T ≈ 300 K, L ≈ 1 μm       | Corrections thermiques négligeables      |
| Objets anisotropes        | Couple de Casimir                     | Anisotropie optique       | Rotation induite (mesurée en 2018)      |
| Vide entre objets         | Transmission de phonons               | Fluctuations quantiques   | Transfert thermique observé (2019)      |

### 5.4 Questions ouvertes

- Comment la géométrie des cavités non planes (sphériques, cylindriques) modifie-t-elle quantitativement l’expression de la force de Casimir【2】【16】?
- Dans quelles conditions expérimentales la transmission de phonons par effet Casimir pourrait-elle être exploitée pour des applications technologiques【2】?

---

## 6. Géométrie thermodynamique : formalisme et applications confinées

### 6.1 Géométrie impliquée

La thermodynamique géométrique utilise le formalisme de la géométrie de Riemann pour représenter les états d’équilibre comme des points sur une variété, la distance entre états étant liée aux fluctuations【3】【25】【29】【33】. Les systèmes confinés (cavités, interfaces) modifient les grandeurs molaires partielles et les potentiels chimiques.

### 6.2 Modèles et équations associés

Les relations différentielles fondamentales :

\[
dU = TdS - PdV + \sum \mu_i dN_i
\]
\[
dG = -SdT + VdP + \sum \mu_i dN_i
\]

La relation de Gibbs-Duhem :

\[
\sum_i n_i d\mu_i = -S dT + V dP
\]
À T et P constantes :
\[
\sum_i n_i d\mu_i = 0
\]

La géométrie de Ruppeiner :

\[
g_{ij}^R = -\frac{\partial^2 S}{\partial x^i \partial x^j}
\]

### 6.3 Effets physiques mesurés

Les équilibres de phases (liquide-vapeur, liquide-solide) sont décrits par les potentiels chimiques et les coefficients d’activité/fugacité. Les propriétés thermodynamiques réelles sont obtenues par :

\[
X_{real} = X_{ideal} + X_{residuelle}
\]

Les modèles cubiques (Van der Waals, Peng-Robinson) et à coefficient d’activité (NRTL, UNIQUAC, COSMO-RS) sont utilisés pour simuler les mélanges réels【3】【33】.

#### Tableau comparatif : modèles thermodynamiques

| Type de système           | Modèle recommandé      | Grandeur clé                |
|---------------------------|-----------------------|-----------------------------|
| Hydrocarbures légers      | PR, SRK               | Fugacité, activité          |
| Mélanges polaires         | NRTL, UNIQUAC, PC-SAFT| Coefficient d’activité      |
| Électrolytes              | Pitzer, eNRTL         | Force ionique, γ±           |
| Molécules complexes       | COSMO-SAC, NRTL-SAC   | Profils de charge σ         |

### 6.4 Questions ouvertes

- Dans quelle mesure la géométrie des cavités ou des interfaces influence-t-elle les grandeurs molaires partielles mesurées expérimentalement dans des systèmes confinés【29】【33】?
- Comment la relation de Gibbs-Duhem peut-elle être adaptée ou reformulée pour des systèmes hors équilibre ou dans des régimes de couplage fort avec un champ électromagnétique【29】?

---

## 7. Chiralité en physique : définitions, mesures et applications

### 7.1 Géométrie impliquée

La chiralité est la propriété d’un objet de ne pas être superposable à son image miroir. Elle se manifeste dans les molécules, les cristaux, les ondes polarisées circulairement, les hélices, les trièdres, et les textures magnétiques non coplanaires【4】【30】【36】.

### 7.2 Modèles et équations associés

L’interaction lumière–matière dans les systèmes chiraux est étudiée par le dichroïsme circulaire (CD) et le dichroïsme circulaire de photoélectrons (PECD) :

\[
\text{CD} = A_{L} - A_{R}
\]
où \(A_{L}\) et \(A_{R}\) sont les absorptions pour polarisation gauche et droite.

Le PECD mesure l’asymétrie angulaire des électrons émis :

\[
\text{PECD} = \frac{I_{f} - I_{b}}{I_{f} + I_{b}}
\]
où \(I_{f}\) et \(I_{b}\) sont les intensités avant et arrière.

L’interaction de Dzyaloshinskii–Moriya (DMI) en magnétisme :

\[
E_{DM} = \mathbf{D}_{ij} \cdot (\mathbf{S}_i \times \mathbf{S}_j)
\]

### 7.3 Effets physiques mesurés

Le CD et le PECD permettent de déterminer la configuration absolue et l’excès énantiomérique des molécules chirales, même en phase gazeuse et in situ【4】【30】【36】. En nanophysique, la chiralité des plasmons de surface et des parois de Néel induit des effets directionnels et topologiques (skyrmions). Les expériences de PECD sur des dipeptides cycliques et des acides aminés montrent une forte énantiosélectivité et une dépendance à la microsolvatation【30】【36】.

#### Tableau comparatif : mesures de chiralité

| Technique      | Système étudié         | Grandeur mesurée         | Application                |
|----------------|-----------------------|--------------------------|----------------------------|
| CD             | Molécules organiques  | Différence d’absorption  | Configuration absolue      |
| PECD           | Dipeptides, acides aminés | Asymétrie angulaire      | Excès énantiomérique       |
| DMI            | Parois magnétiques    | Chiralité de paroi       | Contrôle du déplacement    |
| Plasmons       | Nanostructures        | Couplage chiral          | Directionnalité optique    |

### 7.4 Questions ouvertes

- Quelle est la relation quantitative entre la chiralité structurale et la chiralité dynamique dans les systèmes moléculaires et nanostructurés【4】【36】?
- Peut-on exploiter la chiralité des plasmons et des skyrmions pour des applications en information quantique et spintronique【4】?

---

## 8. Topologie et invariants géométriques

### 8.1 Géométrie impliquée

La topologie des bandes électroniques est caractérisée par des invariants tels que le nombre de Chern, Z₂, et la courbure de Berry. Les réseaux kagomé, moirés et Harper-Hofstadter sont des plateformes privilégiées pour l’étude des isolants topologiques et des états fractionnaires【18】【28】【34】【38】.

### 8.2 Modèles et équations associés

Le nombre de Chern est calculé par :

\[
C = \frac{1}{2\pi} \int_{BZ} d^2k\, \mathcal{F}(k)
\]
où
\[
\mathcal{F}(k) = 2\, \text{Im} \langle \partial_{k_y} u(k) | \partial_{k_x} u(k) \rangle
\]

La formule de Streda relie le nombre de Chern à la dérivée de la densité par rapport au champ magnétique :

\[
C = \frac{h}{e} \frac{dn}{dB_\perp}
\]

La construction de fonctions de Wannier optimales dans les bandes de Chern repose sur la minimisation de la variance de la position et la résolution de l’équation de Poisson pour la jauge de Coulomb【34】.

### 8.3 Effets physiques mesurés

Les états topologiques sont identifiés par des plateaux quantifiés de Hall, des modes de bord chiraux, des spectres d’entrelacement conformes à la théorie SU(2)₁ WZW, et des signatures d’entropie d’intrication topologique (TEE)【46】【28】【38】. Les isolants de Chern fractionnaires (FCI) et les états de Laughlin sont observés dans les réseaux kagomé et moirés, avec des spectres d’excitation compatibles avec la fractionnalisation des symétries du groupe d’espace.

#### Tableau comparatif : invariants topologiques et phases

| Système         | Invariant | Phase observée         | Signature expérimentale         |
|-----------------|-----------|------------------------|---------------------------------|
| tMoTe₂          | C = +1    | QAH, FQAH, FCI         | Plateaux Hall, RMCD, gap        |
| Kagomé          | C = 1/2   | CSL, QSL, Laughlin     | Transfert de spin, TEE, DMRG    |
| Harper-Hofstadter| C = n     | Bande sombre topologique| Déplacement centre de masse     |

### 8.4 Questions ouvertes

- Quelle est la limite supérieure du nombre de Chern réalisable par couplage cohérent de bandes de Bloch【38】?
- Comment la présence de désordre ou d’interactions fortes affecte-t-elle la stabilité et la topologie des bandes plates et sombres【38】【34】?

---

## 9. Modèles Hamiltoniens et équations analytiques : catalogue par géométrie

### 9.1 Géométrie impliquée

Les modèles Hamiltoniens sont adaptés à la géométrie du système : réseaux (Heisenberg, Hubbard), cavités (Jaynes–Cummings, Rabi, Hopfield), surfaces (modèles de surface, DMI), et bandes plates (Bistritzer-MacDonald, Harper-Hofstadter)【5】【13】【55】【57】【34】【49】.

### 9.2 Catalogue des modèles

#### Réseaux frustrés

- Heisenberg antiferromagnétique :
  \[
  \mathcal{H} = -J \sum_{\langle i,j \rangle} \vec{S}_i \cdot \vec{S}_j
  \]
- Dzyaloshinskii-Moriya :
  \[
  H_{DM} = \sum_{\langle i,j \rangle} \mathbf{D}_{ij} \cdot (\mathbf{S}_i \times \mathbf{S}_j)
  \]
- Modèle J₁–J₂–J₃ kagomé :
  \[
  H= J_{1}\sum_{\langle ij \rangle} \mathbf{S}_{i} \cdot \mathbf{S}_{j} + J_{2}\sum_{\langle\langle ij \rangle\rangle} \mathbf{S}_{i} \cdot \mathbf{S}_{j} + J_{3}\sum_{\langle\langle\langle ij \rangle\rangle\rangle} \mathbf{S}_{i} \cdot \mathbf{S}_{j}
  \]

#### Cavités et CQED

- Jaynes–Cummings :
  \[
  \hat{H}_{JC} = \hbar \omega_c a^\dagger a + \hbar \omega_0 \sigma^z + \hbar g (\sigma^\dagger a + \sigma a^\dagger)
  \]
- Rabi quantique :
  \[
  \hat{H}_R = \frac{\omega_a}{2} \sigma_z + \omega_c a^\dagger a + g (a + a^\dagger)(\sigma^+ + \sigma^-)
  \]
- Hopfield :
  \[
  \hat{H}_{Hop} = \hbar \omega_c a^\dagger a + \hbar \omega_0 (b^\dagger b - N/2) + \hbar \Omega_R \sqrt{N} (a^\dagger + a)(J^- + J^+) + D(a^\dagger + a)^2
  \]

#### Bandes plates moiré

- Bistritzer-MacDonald :
  \[
  H = \begin{pmatrix}
  0 & D(r) \\
  D^\dagger(-r) & 0
  \end{pmatrix}
  \]
- Harper-Hofstadter :
  \[
  H_{HH} = -t \sum_{m,n} (e^{i 2\pi \phi n} c_{m+1,n}^\dagger c_{m,n} + c_{m,n+1}^\dagger c_{m,n} + h.c.)
  \]

### 9.3 Questions ouvertes

- Comment optimiser les séquences de pulsations pour minimiser les erreurs numériques dans les régimes de couplage ultra-fort【55】【57】?
- Peut-on relier la position optimale du vortex dans les fonctions de Wannier à des invariants topologiques secondaires【34】?

---

## 10. Effets physiques mesurés : techniques expérimentales et données quantitatives

### 10.1 Techniques expérimentales

- Diffusion inélastique de neutrons (INS) : mesure des excitations magnétiques, continuum de spinons, structure dynamique du facteur de spin【39】【53】【51】.
- RMCD (dichroïsme circulaire magnétique réfléchi) : mesure de la magnétisation hors-plan dans les réseaux moirés【18】【28】.
- Transport électrique : résistivité longitudinale et Hall, plateaux quantifiés, transitions de phase【18】【28】【45】【52】.
- Spectroscopie infrarouge et Raman : polaritons vibrationnels, séparation de Rabi【21】【41】.
- Photoluminescence et réflectivité : anticroisement dans les cavités photoniques【48】.

### 10.2 Données quantitatives

- Températures critiques : 0.2–10 K (supraconductivité moiré), 4–10 K (ferromagnétisme moiré), 50 mK (QSL kagomé)【18】【45】【54】【51】.
- Largeurs de bande plate : 8–15 meV (tMoTe₂), <10 meV (TBG, tWSe₂)【18】【45】【52】.
- Gaps de transport : 1–2.5 meV (IQSH, isolant trivial)【18】.
- Rabi splitting : 100–350 meV (cavités collectives)【15】【41】.
- Hall quantifié : \( \rho_{xy} = h/e^2 \), \( 3h/2e^2 \) (QAH, FQAH, FCI)【18】【28】.

#### Tableau comparatif : techniques et grandeurs mesurées

| Technique         | Grandeur mesurée         | Systèmes étudiés           | Précision/Plage           |
|-------------------|-------------------------|----------------------------|---------------------------|
| INS               | Excitations magnétiques | Kagomé, moiré, QSL         | 0.1–10 meV                |
| RMCD              | Magnétisation hors-plan | tMoTe₂, tWSe₂              | 1–10 K                    |
| Transport         | Résistivité, Hall       | Moiré, TBG, kagomé         | 0.1–100 kΩ, quantifié     |
| Spectroscopie IR  | Polariton, Rabi         | Cavités, molécules         | 10–350 meV                |
| Photoluminescence | Anticroisement          | Cavités, semi-conducteurs  | 1–100 meV                 |

### 10.3 Questions ouvertes

- Quelles sont les limites de température et de désordre pour l’observation de phases topologiques quantifiées【18】【28】?
- Comment affiner les techniques de mesure pour détecter des signatures plus nettes d’états non-Abéliens ou de fractionnalisation【46】【51】?

---

## 11. Simulations et méthodes numériques

### 11.1 Méthodes utilisées

- DMRG (Density Matrix Renormalization Group) : étude des phases QSL, CSL, FCI, spectres d’excitation, entropie d’intrication【31】【50】【42】【46】【51】.
- Diagonalisation exacte (ED) : spectres de Laughlin, bandes plates, interactions projetées【34】.
- Monte Carlo : corrélations de spin, transitions de phase, modèles de frustration【0】【35】.
- Ab initio, DFT, Hartree–Fock : structure de bande, courbure de Berry, interactions électroniques【18】【28】【45】.

### 11.2 Données et validation

Les simulations reproduisent les corrélations spin-spin, les spectres d’excitation, les gaps de spin, et les signatures topologiques observées expérimentalement. Les calculs DMRG sur kagomé et moiré confirment la présence de QSL, CSL, FCI et la robustesse des corrélations AFM de premier voisinage jusqu’à haute température【51】【54】.

#### Tableau comparatif : méthodes numériques et applications

| Méthode           | Système            | Propriété calculée           | Validation expérimentale    |
|-------------------|--------------------|------------------------------|----------------------------|
| DMRG              | Kagomé, moiré      | QSL, CSL, FCI, spectre       | INS, RMCD, transport       |
| ED                | Kagomé, moiré      | Laughlin, gap, spectre       | Plateaux Hall, RMCD        |
| Monte Carlo       | Kagomé, frustration| Corrélations, transitions    | Chaleur spécifique, INS    |
| DFT/HF            | Moiré, TMD         | Structure de bande, Berry    | ARPES, transport           |

### 11.3 Questions ouvertes

- Quelle est la robustesse des résultats DMRG vis-à-vis des fluctuations quantiques au-delà du champ moyen【34】【46】?
- Peut-on améliorer la précision des phases identifiées par des méthodes numériques plus coûteuses ou hybrides【31】【50】?

---

## 12. Comparaison des géométries : réseaux, surfaces, cavités, confinement

### 12.1 Tableau comparatif des géométries et effets physiques

| Géométrie      | Modèle associé         | Effet physique mesuré         | Systèmes expérimentaux      |
|----------------|-----------------------|-------------------------------|-----------------------------|
| Réseau kagomé  | Heisenberg, DM        | QSL, CSL, bandes plates       | Herbertsmithite, Mn₃Sn     |
| Moiré (TBG, TMD)| Bistritzer-MacDonald | Supraconductivité, QAH, FCI   | tMoTe₂, tWSe₂, TBG          |
| Cavité Fabry–Pérot| Jaynes–Cummings, Rabi| Polaritons, VSC, chimie modifiée| Cavités optiques, plasmoniques|
| Surface chirale| DMI, CD, PECD         | Chiralité, dichroïsme         | Dipeptides, nanostructures  |
| Confinement    | Modèles thermodynamiques| Modification de réactivité, transitions| Cavités chimiques, interfaces|

### 12.2 Questions ouvertes

- Comment la connectivité ou la non-connectivité d’un réseau influence-t-elle la nature des phases magnétiques observées dans les modèles de spins【43】?
- Peut-on classifier les géométries favorisant un SCQSL robuste ou des bandes plates topologiques stables【54】【34】?

---

## Conclusion

L’impact de la géométrie sur les phénomènes physiques est un domaine d’une richesse exceptionnelle, où la structure spatiale des systèmes impose des contraintes, génère des effets nouveaux et façonne la diversité des états observés. Des réseaux frustrés aux cavités photoniques, des bandes plates moirées aux textures chirales, chaque géométrie ouvre des perspectives uniques pour la compréhension et la manipulation des propriétés physiques. Les modèles analytiques et numériques, validés par des mesures expérimentales précises, permettent de relier la géométrie aux invariants topologiques, aux excitations collectives et aux transitions de phase. Les questions ouvertes identifiées dans chaque axe témoignent de la vitalité du champ et de la nécessité de poursuivre l’exploration rigoureuse des liens entre géométrie, modèles et phénomènes physiques.

---

**Questions ouvertes transversales :**

- Peut-on établir une classification universelle des géométries favorisant la stabilisation de phases topologiques et exotiques ?
- Comment la géométrie des cavités et des interfaces peut-elle être exploitée pour contrôler finement les réactions chimiques et les transitions quantiques ?
- Quelles sont les signatures expérimentales directes des effets géométriques dans les spectres d’excitation, les mesures de transport et les propriétés thermodynamiques ?

Ce rapport, ancré dans les faits établis et les résultats expérimentaux, offre une base solide pour la construction d’une théorie rigoureuse de l’impact de la géométrie dans les phénomènes physiques, et ouvre la voie à de nouvelles investigations interdisciplinaires.
