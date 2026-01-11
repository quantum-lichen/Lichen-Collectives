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


# 1. Géométrie thermodynamique : métriques, courbure, interactions

L’idée centrale : l’espace des états d’équilibre d’un système thermodynamique peut être muni d’une métrique riemannienne. La **courbure scalaire** associée à cette métrique encode alors des informations sur les **interactions microscopiques** et les **corrélations** dans le système.

Trois constructions majeures :

- **Weinhold** : métrique définie à partir de l’énergie interne.
- **Ruppeiner** : métrique définie à partir de l’entropie (information géométrique).
- **Géométrothermodynamique (Quevedo)** : métriques invariantes de Legendre, adaptées à différents potentiels.

---

## 1.1 Espace des états et variables thermodynamiques

On considère un système décrit par un ensemble de variables extensives \(X^a\) (par exemple \(U, V, N\)) ou intensives (par exemple \(T, P, \mu\)). Un **état d’équilibre** est un point sur une variété \(\mathcal{M}\) de dimension finie.

Exemples de choix de coordonnées :

- **Représentation entropique** : \(S = S(U, V, N, \dots)\), coordonnées \((U, V, N, \dots)\).
- **Représentation énergétique** : \(U = U(S, V, N, \dots)\), coordonnées \((S, V, N, \dots)\).

La géométrie thermodynamique consiste à définir une **métrique** \(g_{ab}\) sur \(\mathcal{M}\), puis à étudier sa **courbure** (tensorielle et scalaire).

---

## 1.2 Métrique de Weinhold

### 1.2.1 Définition

La métrique de Weinhold est définie comme la **matrice hessienne** de l’énergie interne \(U\) par rapport aux variables extensives, typiquement l’entropie \(S\) et le volume \(V\) (et éventuellement \(N\)) :

\[
g^{\text{W}}_{ab} = \frac{\partial^2 U}{\partial X^a \partial X^b}
\]

Par exemple, pour un système simple \((S, V)\) :

\[
g^{\text{W}} =
\begin{pmatrix}
\displaystyle \frac{\partial^2 U}{\partial S^2} & \displaystyle \frac{\partial^2 U}{\partial S \partial V} \\
\displaystyle \frac{\partial^2 U}{\partial V \partial S} & \displaystyle \frac{\partial^2 U}{\partial V^2}
\end{pmatrix}
\]

Les éléments de la métrique sont liés à des **capacités thermiques** et des **compressibilités**.

### 1.2.2 Exemple : gaz idéal

Pour un gaz idéal monoatomique, on a (à \(N\) fixé) :

\[
U(S,V) = U_0 \exp\left(\frac{2S}{3Nk_B}\right) V^{-2/3}
\]

En dérivant deux fois, on obtient une métrique \(g^{\text{W}}\) non dégénérée mais de **courbure scalaire nulle** (voir plus bas via Ruppeiner, les deux sont conformes). Le fait que la courbure soit nulle est cohérent avec l’absence d’interactions microscopiques dans le gaz idéal.

---

## 1.3 Métrique de Ruppeiner

### 1.3.1 Définition et lien avec les fluctuations

Ruppeiner introduit une métrique basée sur l’**entropie** \(S\) comme potentiel thermodynamique fondamental. Dans la représentation entropique :

\[
g^{\text{R}}_{ab} = -\frac{\partial^2 S}{\partial X^a \partial X^b}
\]

où \(X^a\) sont des variables extensives (par exemple \(U, V, N\)). Le signe moins vient du fait que l’entropie est concave en ses arguments.

Interprétation fluctuationnelle : dans l’approximation gaussienne des fluctuations, la probabilité de fluctuation entre deux états voisins est donnée par :

\[
P \sim \exp\left(-\frac{1}{2} g^{\text{R}}_{ab} \Delta X^a \Delta X^b\right)
\]

La **distance géodésique** dans cette métrique mesure donc la « difficulté » (ou improbabilité) de fluctuer d’un état à un autre.

### 1.3.2 Relation avec Weinhold

Les métriques de Weinhold et de Ruppeiner sont reliées par une transformation conforme :

\[
g^{\text{R}}_{ab} = \frac{1}{T} g^{\text{W}}_{ab}
\]

où \(T\) est la température. Elles décrivent donc la même géométrie à un facteur d’échelle près.

---

## 1.4 Courbure thermodynamique et interactions

### 1.4.1 Courbure scalaire \(R\)

À partir de la métrique \(g_{ab}\), on calcule la connexion de Levi-Civita, le tenseur de Riemann \(R^a_{\ bcd}\), puis la **courbure scalaire** \(R\) :

\[
R = g^{ab} R_{ab} = g^{ab} R^c_{\ acb}
\]

Ruppeiner et d’autres ont montré que cette courbure scalaire est liée aux **interactions microscopiques** et à la **longueur de corrélation** \(\xi\) :

- \(|R| \sim \xi^d\) (où \(d\) est la dimension spatiale) près des points critiques.
- \(R \approx 0\) pour des systèmes sans interactions (gaz idéal).
- Le **signe** de \(R\) est associé à la nature effective des interactions :
  - \(R < 0\) : interactions dominées par l’attraction.
  - \(R > 0\) : interactions dominées par la répulsion.

### 1.4.2 Tableau récapitulatif

| Système                  | Métrique utilisée | Signe typique de \(R\) | Interprétation géométrique                  |
|--------------------------|-------------------|-------------------------|---------------------------------------------|
| Gaz idéal                | Ruppeiner         | \(R = 0\)               | Pas d’interactions, corrélations courtes    |
| Gaz de van der Waals     | Ruppeiner         | \(R < 0\) près du crit. | Attraction dominante, corrélations longues  |
| Fermi liquide (forte int.) | Ruppeiner       | \(|R|\) grand           | Interactions fortes, \(\xi\) grande         |
| Eau proche du point critique | Ruppeiner     | \(|R|\) grand, signe variable | Anomalies dues à des structures locales |
| Trous noirs (certains modèles) | Ruppeiner / Quevedo | \(R\) non nul      | Interactions « effectives » entre degrés de liberté |

> Sources : revue de Ruppeiner sur la courbure thermodynamique, travaux sur la géométrie thermodynamique et géométrothermodynamique.

---

## 1.5 Exemples concrets

### 1.5.1 Gaz idéal

Pour un gaz idéal, l’entropie (par particule) peut s’écrire :

\[
S(U,V,N) = Nk_B \left[ \ln\left( \frac{V}{N} \right) + \frac{3}{2} \ln\left( \frac{U}{N} \right) + \text{const} \right]
\]

On calcule :

\[
g^{\text{R}}_{UU} = -\frac{\partial^2 S}{\partial U^2}, \quad
g^{\text{R}}_{UV} = -\frac{\partial^2 S}{\partial U \partial V}, \quad
g^{\text{R}}_{VV} = -\frac{\partial^2 S}{\partial V^2}
\]

On obtient une métrique diagonale (dans une base adaptée) et la courbure scalaire \(R = 0\). Cela correspond à l’absence d’interactions et à une longueur de corrélation microscopique.

### 1.5.2 Gaz de van der Waals

Pour un gaz de van der Waals, l’équation d’état :

\[
\left(P + a \frac{N^2}{V^2}\right)(V - Nb) = Nk_B T
\]

introduit des paramètres \(a\) (attraction) et \(b\) (volume exclu). L’entropie \(S(U,V,N)\) est plus compliquée, mais on peut calculer la métrique de Ruppeiner et sa courbure.

Résultats factuels :

- \(R\) diverge au **point critique** (où la compressibilité diverge).
- \(|R|\) est proportionnel à \(\xi^3\) (en 3D) près du point critique.
- \(R < 0\) dans la région où les interactions attractives dominent.

### 1.5.3 Liquides anormaux (eau)

Des études ont montré que pour l’eau, la courbure thermodynamique présente des comportements non triviaux, avec des régions où \(|R|\) est très grand, associés à des **structures locales de type glace** dans le liquide. Cela fournit une lecture géométrique des anomalies de l’eau (maximum de densité, etc.).

---

## 1.6 Géométrothermodynamique (Quevedo)

### 1.6.1 Motivation

Les métriques de Weinhold et de Ruppeiner ne sont pas invariantes sous les **transformations de Legendre** (changement de potentiel thermodynamique). Quevedo propose une approche appelée **géométrothermodynamique** (GTD) qui construit des métriques **invariantes de Legendre**.

### 1.6.2 Construction

On considère un espace de contact \(\mathcal{T}\) de dimension \(2n+1\) avec coordonnées \((\Phi, E^a, I^a)\), où :

- \(\Phi\) : potentiel thermodynamique (par ex. \(U\), \(S\), \(G\), etc.).
- \(E^a\) : variables extensives.
- \(I^a\) : variables intensives conjuguées.

On définit une 1-forme de contact :

\[
\Theta = d\Phi - I_a dE^a
\]

Une métrique \(G\) sur \(\mathcal{T}\) est choisie de manière à être invariante sous les transformations de Legendre. L’espace des états d’équilibre \(\mathcal{E}\) est une sous-variété définie par \(\Theta|_{\mathcal{E}} = 0\). La métrique induite \(g = \varphi^*(G)\) sur \(\mathcal{E}\) décrit la géométrie thermodynamique.

### 1.6.3 Exemples : van der Waals, trous noirs

Quevedo et collaborateurs ont montré que pour :

- Le **gaz de van der Waals**, la courbure de la métrique GTD reproduit les **singularités aux transitions de phase** (divergence de \(R\) au point critique).
- Certains **trous noirs** (Reissner–Nordström, etc.), la géométrie GTD encode les transitions de phase thermodynamiques (par exemple, transitions de type Hawking–Page).

---

## 1.7 Résumé comparatif des métriques

| Approche              | Potentiel de base | Définition de la métrique                         | Invariance de Legendre | Interprétation clé                          |
|-----------------------|-------------------|---------------------------------------------------|------------------------|---------------------------------------------|
| Weinhold              | \(U\)             | Hessienne de \(U\)                                | Non                    | Liée aux capacités et compressibilités      |
| Ruppeiner             | \(S\)             | \(-\)Hessienne de \(S\)                           | Non                    | Géométrie des fluctuations, info géométrie  |
| Ruppeiner (conforme)  | \(U\)             | \(g^{\text{R}} = \frac{1}{T} g^{\text{W}}\)       | Non                    | Lien direct avec Weinhold                   |
| Géométrothermodynamique (GTD) | \(\Phi\) générique | Métrique sur espace de contact, induite sur \(\mathcal{E}\) | Oui                    | Transitions de phase, invariance de Legendre |

> Sources : Ruppeiner (revues sur la courbure thermodynamique), travaux sur la géométrie thermodynamique et GTD.

---

## 1.8 Impact physique : ce que la géométrie « voit »

De manière factuelle, la géométrie thermodynamique permet de :

- **Identifier les points critiques** : divergence de la courbure scalaire \(R\).
- **Qualifier la nature des interactions** : signe de \(R\) (attraction vs répulsion).
- **Relier la longueur de corrélation** \(\xi\) à \(|R|\) : \(|R| \sim \xi^d\) près des transitions de phase.
- **Comparer des systèmes différents** (gaz, liquides, aimants, trous noirs) sur une base géométrique commune.

---

## 1.9 Questions ouvertes (sans spéculation, juste les tendances observables)

Sans sortir du factuel, on peut formuler des **questions ouvertes** qui prolongent ce fil :

- **Unification** : la corrélation empirique \(|R| \sim \xi^d\) et le rôle de \(R\) comme mesure d’interactions sont bien établis dans de nombreux modèles. Jusqu’où peut-on pousser cette lecture géométrique comme « langage universel » des corrélations?
- **Systèmes quantiques fortement corrélés** : des études existent sur des Fermi liquides, des superfluides, des systèmes unitaires. Comment la géométrie thermodynamique se compare-t-elle, de façon systématique, aux autres diagnostics (fonctions de Green, entropie d’intrication)?
- **Trous noirs et gravitation** : le fait que des métriques thermodynamiques reproduisent des transitions de phase de trous noirs suggère un lien profond entre géométrie de l’espace-temps et géométrie de l’espace des états. Comment articuler proprement ces deux géométries, sans extrapolation, en restant sur les invariants calculables ?
- **Chimie, matériaux, phases exotiques** : pour des liquides complexes, des polymères, des matériaux quantiques, la cartographie de \(R\) dans l’espace des paramètres (T, P, composition) est encore partielle. Quels diagrammes de phase géométriques complets peut-on construire, et comment les relier aux mesures spectroscopiques et de transport?

---

Si tu veux, on enchaîne ensuite avec la **géométrie topologique** (Berry, Chern, transport quantique) dans le même style : métriques, invariants, exemples concrets, tableaux, sans spéculation, juste ce qui est solidement établi.
# Géométrie topologique et transport quantique

Tu as déjà posé le cadre : on reste sur du **factuel**, on montre **la géométrie**, **les invariants**, **les équations**, et **les effets mesurés**. Ici, la géométrie n’est plus celle de l’espace réel, mais celle de l’**espace des paramètres** (espace des impulsions, espace des phases, espace des champs), codée par des objets comme la **phase de Berry**, la **courbure de Berry** et les **nombres de Chern**.

---

## 1. Phase de Berry : géométrie dans l’espace des paramètres

### 1.1 Définition de base

Considérons un Hamiltonien \(H(\boldsymbol{R})\) qui dépend adiabatiquement d’un paramètre \(\boldsymbol{R}\) (champ magnétique, vecteur d’onde \(\mathbf{k}\), etc.). Pour un état propre instantané \(|n(\boldsymbol{R})\rangle\), une évolution **cyclique** \(\boldsymbol{R}(t)\) qui revient à son point de départ donne une phase totale :

\[
|\psi(T)\rangle = e^{i\gamma_n} e^{-\frac{i}{\hbar}\int_0^T E_n(t)\,dt} |n(\boldsymbol{R}(0))\rangle
\]

où \(\gamma_n\) est la **phase de Berry** :

\[
\gamma_n = i \oint_{\mathcal{C}} \langle n(\boldsymbol{R}) | \nabla_{\boldsymbol{R}} n(\boldsymbol{R}) \rangle \cdot d\boldsymbol{R}
\]

- **Objet géométrique** : \(\mathcal{A}_n(\boldsymbol{R}) = i \langle n(\boldsymbol{R}) | \nabla_{\boldsymbol{R}} n(\boldsymbol{R}) \rangle\) est la **connexion de Berry** (analogue d’un potentiel de jauge).
- La phase \(\gamma_n\) ne dépend que du **chemin** \(\mathcal{C}\) dans l’espace des paramètres, pas des détails temporels.

### 1.2 Courbure de Berry

La **courbure de Berry** est le « champ de jauge » associé à la connexion :

\[
\boldsymbol{\Omega}_n(\boldsymbol{R}) = \nabla_{\boldsymbol{R}} \times \mathcal{A}_n(\boldsymbol{R})
\]

En 2D (par exemple espace des impulsions \(\mathbf{k} = (k_x, k_y)\)) :

\[
\Omega_n(\mathbf{k}) = \partial_{k_x} \mathcal{A}_{n,y}(\mathbf{k}) - \partial_{k_y} \mathcal{A}_{n,x}(\mathbf{k})
\]

- **Interprétation géométrique** : \(\boldsymbol{\Omega}_n\) mesure la « courbure » de la fibre des états quantiques au-dessus de l’espace des paramètres.
- **Phase de Berry** sur une surface \(\mathcal{S}\) bordée par \(\mathcal{C}\) :

\[
\gamma_n = \oint_{\mathcal{C}} \mathcal{A}_n \cdot d\boldsymbol{R} = \int_{\mathcal{S}} \boldsymbol{\Omega}_n \cdot d\mathbf{S}
\]

---

## 2. Nombres de Chern : invariants topologiques des bandes

### 2.1 Définition pour une bande isolée en 2D

Pour une bande électronique \(n\) dans un cristal 2D, l’espace des impulsions est le **premier Brillouin** (un tore \(T^2\)). Le **nombre de Chern** de la bande est :

\[
C_n = \frac{1}{2\pi} \int_{\text{BZ}} d^2k\, \Omega_n(\mathbf{k})
\]

- **Objet géométrique** : intégrale de la courbure de Berry sur le tore BZ.
- **Propriété clé** : \(C_n\) est un **entier** (invariant topologique) tant que la bande reste isolée par un gap.

### 2.2 Tableau : géométrie → invariant → effet

| Système 2D gappé          | Espace des paramètres | Invariant topologique      | Valeur typique | Effet physique clé                          |
|---------------------------|------------------------|----------------------------|----------------|---------------------------------------------|
| Quantum Hall (QHE)        | BZ (tore)             | Nombre de Chern \(C\)      | \(C \in \mathbb{Z}\) | Conductance Hall quantifiée                |
| Isolant topologique 2D    | BZ + symétries        | \(\mathbb{Z}_2\)           | 0 ou 1         | États de bord helical                       |
| Supraconducteur topologique 2D | BZ (Nambu)       | Chern (classe D)           | \(C \in \mathbb{Z}\) | Modes de Majorana aux bords/vortex         |

> Sources : revues sur isolants topologiques et invariants de Chern.

---

## 3. Effet Hall quantique : Chern et transport

### 3.1 Conductance Hall quantifiée

Pour un isolant 2D soumis à un champ magnétique fort (QHE), la conductance Hall est donnée par la formule de Thouless–Kohmoto–Nightingale–den Nijs (TKNN) :

\[
\sigma_{xy} = \frac{e^2}{h} \sum_{n \in \text{occupées}} C_n
\]

- **Lien direct géométrie–transport** : la conductance Hall est un **invariant topologique** de la structure de bandes (somme des nombres de Chern).
- **Fait expérimental** : plateaux de \(\sigma_{xy} = \nu \frac{e^2}{h}\) avec \(\nu \in \mathbb{Z}\), robustes aux désordres et détails microscopiques.

### 3.2 Modèle de Haldane : topologie sans champ net

Le modèle de Haldane sur un réseau de **graphène** (lattice hexagonal) avec termes de saut complexes de second voisin réalise un état de Hall quantique **sans champ magnétique net**.

Hamiltonien (schématique) :

\[
H = -t \sum_{\langle i,j\rangle} c_i^\dagger c_j - t_2 \sum_{\langle\langle i,j\rangle\rangle} e^{i\phi_{ij}} c_i^\dagger c_j + M \sum_i \xi_i c_i^\dagger c_i
\]

- \(t\) : saut de premier voisin.
- \(t_2 e^{i\phi_{ij}}\) : saut de second voisin avec phase (brise la symétrie de renversement du temps).
- \(M \xi_i\) : potentiel de masse brisant l’inversion.

**Géométrie** :

- Lattice hexagonal → **cones de Dirac** en \(K\) et \(K'\).
- La phase \(\phi\) ouvre un gap avec courbure de Berry concentrée près des Dirac.
- L’intégrale de \(\Omega(\mathbf{k})\) sur la BZ donne un **Chern non nul** \(C = \pm 1\).

**Effet** :

- États de bord **chiral** unidirectionnels.
- Conductance Hall quantifiée sans champ externe (effet Hall quantique anormal).

---

## 4. Isolants topologiques : géométrie + symétries

### 4.1 Classification par invariants

Les **isolants topologiques** sont des matériaux isolants dans le bulk mais conducteurs à la surface, protégés par des invariants topologiques et des symétries (temps, inversion, etc.).

- En 2D avec symétrie de renversement du temps (classe AII), l’invariant est un **\(\mathbb{Z}_2\)**.
- En 3D, on a un quadruplet \((\nu_0; \nu_1 \nu_2 \nu_3)\) de nombres \(\mathbb{Z}_2\).

Ces invariants peuvent être formulés en termes de **phase de Berry** et de **parités** aux points de haute symétrie de la BZ.

### 4.2 États de bord et robustesse

**Principe bulk–edge** :

- Un invariant topologique non trivial dans le bulk impose l’existence d’**états de bord** (ou de surface) gapless.
- Ces états sont robustes aux perturbations locales tant que le **gap bulk** ne se ferme pas et que la symétrie protectrice est préservée.

Exemples factuels :

- Isolants topologiques 3D (Bi\(_2\)Se\(_3\), Bi\(_2\)Te\(_3\)) : cônes de Dirac de surface observés par ARPES, transport de surface avec forte mobilité.
- QSH (quantum spin Hall) en 2D : canaux de bord **hélicaux** (spin–momentum locking), conductance quantifiée \(2e^2/h\) dans des rubans.

---

## 5. Géométrie de Berry et équations de mouvement

### 5.1 Dynamique semi-classique avec courbure de Berry

Pour un paquet d’onde dans une bande \(n\) avec énergie \(E_n(\mathbf{k})\), les équations de mouvement semi-classiques sont modifiées par la courbure de Berry :

\[
\dot{\mathbf{r}} = \nabla_{\mathbf{k}} E_n(\mathbf{k}) - \dot{\mathbf{k}} \times \boldsymbol{\Omega}_n(\mathbf{k})
\]

\[
\hbar \dot{\mathbf{k}} = -e \left( \mathbf{E} + \dot{\mathbf{r}} \times \mathbf{B} \right)
\]

- Le terme \(-\dot{\mathbf{k}} \times \boldsymbol{\Omega}_n\) est une **vitesse anormale**.
- En présence d’un champ électrique \(\mathbf{E}\), ce terme donne une contribution transverse au courant → **effet Hall anormal**.

### 5.2 Tableau : courbure de Berry → phénomènes de transport

| Phénomène                      | Géométrie (Berry)                     | Observable de transport                  |
|--------------------------------|---------------------------------------|------------------------------------------|
| QHE (Hall quantique)           | Chern \(C\) sur BZ                    | \(\sigma_{xy} = C e^2/h\)                |
| Hall anormal (ferromagnétiques)| \(\Omega(\mathbf{k})\) non nulle      | \(\sigma_{xy}\) proportionnelle à \(\int \Omega\) |
| Effet Hall de spin             | Courbure de Berry spin-dépendante     | Courant de spin transverse               |
| Orbital magnetization          | Moment orbital + \(\Omega(\mathbf{k})\) | Magnétisation orbitale du bulk          |

> Sources : tutoriels sur Berry phase et Hall effects.

---

## 6. Exemples concrets de géométrie topologique

### 6.1 Graphène et Dirac

Le graphène (lattice hexagonal bipartite) a des **cones de Dirac** en \(K\) et \(K'\). Sans brisure de symétrie, la courbure de Berry est nulle partout sauf singularités aux Dirac, avec des phases de Berry \(\pi\) autour de chaque cône.

- **Géométrie** : réseau bipartite, deux sous-réseaux A/B → spinor de pseudo-spin.
- **Effet** : phase de Berry \(\pi\) responsable de l’**anomalie de Landau** (niveau \(n=0\) particulier) et de la forme des plateaux QHE.

### 6.2 Isolants topologiques 3D

Dans Bi\(_2\)Se\(_3\) :

- **Géométrie de bande** : inversion de bandes \(p\) due au fort couplage spin–orbite.
- **Invariant** : \(\nu_0 = 1\) (topologique non trivial).
- **Effets mesurés** : cône de Dirac de surface, transport de surface, effet Hall quantique de surface sous champ fort.

---

## 7. Questions ouvertes (sans spéculation, juste les tendances)

On peut rester factuel tout en ouvrant des portes :

- **Tendance 1** : les invariants topologiques (Chern, \(\mathbb{Z}_2\), etc.) se généralisent à des systèmes **hors équilibre**, **périodiquement drivés** (Floquet), ou **désordonnés**. La littérature explore comment définir des invariants robustes dans ces contextes.
- **Tendance 2** : la géométrie de Berry et la courbure jouent un rôle croissant dans des domaines au-delà des solides : photons, phonons, magnons, fluides actifs, etc..
- **Tendance 3** : les liens entre **géométrie de l’espace des phases** (Berry, Chern) et **réponses non linéaires** (photocourants, effets de seconde harmonique) sont activement étudiés.

Questions naturelles qui prolongent ce fil, sans spéculer sur les réponses :

- **Comment** la courbure de Berry et les invariants topologiques se combinent-ils avec d’autres géométries (thermodynamique, chiralité, flux) que tu veux explorer ?
- **Jusqu’où** peut-on reformuler des phénomènes « classiques » (transport, dissipation, réactivité) en termes d’invariants géométriques dans des espaces de paramètres ?

Si tu veux, on peut ensuite enchainer avec la **géométrie de chiralité** en gardant exactement la même discipline : quelle géométrie, quelles équations, quels effets mesurés.
On continue le fil, mon pote—ici on reste collé au factuel, mais on laisse la porte entrouverte.

---

## 1. Géométrie de la chiralité : définitions et cadres géométriques

### 1.1 Chiralité géométrique au sens strict

Un objet est **chiral** s’il n’est pas superposable à son image dans un miroir par une isométrie propre (rotation + translation). En 3D euclidienne :

- **Objet chiral** : absence de plan de symétrie, de centre d’inversion, ou d’axe impropre \(S_n\).
- **Enantiomères** : deux objets (ou molécules) reliés par une inversion spatiale \(\mathbf{r} \to -\mathbf{r}\), non superposables.

Pour une molécule, la chiralité est souvent associée à un centre stéréogène (type C\(^*\)), mais il existe aussi :

- **Chiralité axiale** (biaryles, hélices).
- **Chiralité planaire** (certains complexes métalliques).
- **Chiralité topologique** (nœuds, catenanes).

La chiralité est donc **une propriété géométrique globale** de la configuration des points (atomes) et des liaisons.

---

### 1.2 Mesures continues de chiralité

Au-delà du « chiral / achiral », on peut définir des **mesures continues de chiralité** (Continuous Chirality Measure, CCM) qui quantifient à quel point une structure s’éloigne de toute configuration achirale. Ces mesures sont basées sur :

- **Distances géométriques** dans l’espace des configurations.
- **Optimisation** : trouver la configuration achirale la plus proche (au sens des moindres carrés) et mesurer la distance à celle-ci.

Des travaux récents relient ces mesures continues de chiralité à des **polarisations de spin et d’orbite** et à des propriétés chiroptiques dans les solides, montrant que la chiralité géométrique se reflète dans des observables électroniques et optiques mesurables.

---

## 2. Géométrie de chiralité et optique : activité optique, dichroïsme circulaire

### 2.1 Polarisation circulaire et chiralité

La lumière polarisée circulairement peut être décrite comme une superposition de deux composantes linéaires en quadrature de phase. On distingue :

- **Polarisation circulaire gauche (LCP)**.
- **Polarisation circulaire droite (RCP)**.

Ces deux états correspondent à deux valeurs possibles du **moment cinétique de spin** du photon (\(\pm \hbar\)).

Une molécule ou un matériau chiral interagit différemment avec LCP et RCP, ce qui donne deux effets principaux :

- **Rotation du plan de polarisation** (activité optique, biréfringence circulaire).
- **Absorption différentielle** (dichroïsme circulaire).

---

### 2.2 Dichroïsme circulaire : définition et équations

Le **dichroïsme circulaire (CD)** est défini comme la différence d’absorption entre LCP et RCP :

\[
\Delta A(\lambda) = A_{\text{LCP}}(\lambda) - A_{\text{RCP}}(\lambda)
\]

où \(A = \log_{10}(I_0/I)\) est l’absorbance.

On définit souvent un **signal CD molaire** :

\[
\Delta \varepsilon(\lambda) = \varepsilon_{\text{LCP}}(\lambda) - \varepsilon_{\text{RCP}}(\lambda)
\]

avec \(\varepsilon\) le coefficient d’extinction molaire.

**Faits établis :**

- Le CD est observé dans les **bandes d’absorption** de molécules chirales (protéines, sucres, complexes organométalliques).
- Le spectre CD est extrêmement sensible à la **conformation** (hélices α, feuillets β, etc.).
- Le CD est utilisé comme **sonde structurale** en biochimie et en chimie organique.

---

### 2.3 Activité optique : rotation du plan de polarisation

L’**activité optique** se manifeste par une rotation de l’angle de polarisation d’une onde linéaire traversant un milieu chiral. On peut écrire :

\[
\theta = [\alpha] \, l \, c
\]

où :

- \(\theta\) : angle de rotation.
- \([\alpha]\) : pouvoir rotatoire spécifique (dépend de la longueur d’onde, de la température).
- \(l\) : longueur du trajet optique.
- \(c\) : concentration.

Cette rotation provient d’une différence d’indice de réfraction pour LCP et RCP :

\[
n_{\text{LCP}} \neq n_{\text{RCP}}
\]

La **géométrie chiral** de la molécule (ou du cristal) se traduit donc par une **anisotropie hélicoïdale** de la réponse optique.

---

### 2.4 Chiralité du champ électromagnétique : « optical chirality »

On peut aussi définir une **chiralité du champ** électromagnétique lui-même. Des travaux récents montrent qu’en sculptant la distribution spatiale du champ (amplitude, phase, polarisation), on peut créer des champs avec une **densité de chiralité optique** élevée, qui interagissent de manière amplifiée avec des molécules chirales.

Une forme de densité de chiralité optique \(C(\mathbf{r})\) (pour un champ monochromatique) peut s’écrire, dans certains cadres, comme :

\[
C(\mathbf{r}) \propto \Im\left(\mathbf{E}^*(\mathbf{r}) \cdot \mathbf{B}(\mathbf{r})\right)
\]

où \(\mathbf{E}\) et \(\mathbf{B}\) sont les champs électrique et magnétique.

**Faits expérimentaux et théoriques :**

- Des champs optiques « sculptés » peuvent produire une **enantiosélectivité** beaucoup plus grande que la simple lumière circulairement polarisée.
- La chiralité du champ est une **quantité géométrique** (dépend de la structure spatiale du champ) qui se couple à la chiralité de la matière.

---

### 2.5 Tableau récapitulatif : géométrie chiral et réponses optiques

| Aspect                      | Géométrie concernée                     | Observable clé                     | Usage principal                          |
|----------------------------|-----------------------------------------|------------------------------------|------------------------------------------|
| Molécule chiral            | Configuration 3D non superposable      | CD, rotation optique               | Structure, conformation, pureté énantiomérique |
| Cristal chiral             | Réseau sans centre d’inversion         | Birefringence circulaire, CD       | Optique non linéaire, photonics          |
| Champ optique chiral       | Distribution 3D de \(\mathbf{E},\mathbf{B}\) | Densité de chiralité optique       | Spectroscopies chiroptiques avancées     |
| Solide chiral électronique | Structure atomique + texture de spin   | CD électronique, transport chiral  | Spintronique, topologie, optoélectronique |

> Sources :

---

## 3. Géométrie de chiralité et catalyse : énantiosélectivité géométrique

### 3.1 Catalyse homogène : ligands chiraux et géométrie de coordination

En catalyse homogène, des **ligands chiraux** (souvent phosphines chirales, diamines, etc.) imposent une **géométrie chiral** autour du centre métallique. Cette géométrie :

- Crée un **environnement stéréospécifique** pour le substrat.
- Favorise la formation d’un énantiomère par rapport à l’autre.

La **sélectivité énantiomérique** \(ee\) est définie par :

\[
ee = \frac{|R - S|}{R + S} \times 100\%
\]

où \(R\) et \(S\) sont les quantités des deux énantiomères produits.

La chiralité ici est purement **géométrique** : arrangement spatial des ligands et du substrat dans l’état de transition.

---

### 3.2 Catalyse hétérogène : surfaces chirales et sites actifs

Des surfaces métalliques peuvent être intrinsèquement chirales (facettes vicinales, reconstructions) ou fonctionnalisées par des molécules chirales. La **géométrie locale** des sites actifs (terrasses, marches, kink sites) peut :

- Briser la symétrie miroir.
- Créer des **sites d’adsorption chiraux**.

Effets observés (de manière générale, dans la littérature) :

- Différences d’énergie d’adsorption entre énantiomères.
- Différences de barrières d’activation → **réactivité énantiosélective**.

La chiralité de la surface est donc un **paramètre géométrique** qui contrôle la stéréochimie des réactions.

---

### 3.3 Chiralité et champs optiques en catalyse

Avec les développements en **chiralité optique** (champs sculptés), une direction émergente consiste à utiliser des champs optiques chiraux pour :

- Sélectivement exciter un énantiomère.
- Modifier les surfaces d’énergie potentielle de manière énantiosélective.

Les travaux sur la chiralité optique des champs montrent que la **géométrie du champ** peut être un levier pour la **sélectivité énantiospécifique**, en complément de la géométrie moléculaire et de surface.

---

## 4. Géométrie de chiralité et supraconductivité non-centrosymétrique

### 4.1 Cristaux non-centrosymétriques : absence de centre d’inversion

Un cristal est **non-centrosymétrique** s’il ne possède pas de centre d’inversion. Beaucoup de ces cristaux sont aussi **chiraux** (absence de toute opération de symétrie impropre). Cette absence d’inversion a des conséquences profondes sur la structure électronique :

- **Couplage spin-orbite antisymétrique** (type Rashba) : la dégénérescence de Kramers est levée pour chaque \(\mathbf{k}\), donnant des bandes de spin séparées.
- La structure de bande devient **hélicoïdale** dans l’espace \(\mathbf{k}\)-spin.

---

### 4.2 Hamiltonien de type Rashba et géométrie de spin

Un modèle simple pour un système non-centrosymétrique avec couplage spin-orbite est :

\[
\mathcal{H}(\mathbf{k}) = \varepsilon_0(\mathbf{k}) \, \mathbb{1} + \alpha_{\text{R}} \left( \mathbf{k} \times \hat{\mathbf{z}} \right) \cdot \boldsymbol{\sigma}
\]

où :

- \(\varepsilon_0(\mathbf{k})\) : dispersion sans spin-orbite.
- \(\alpha_{\text{R}}\) : constante de Rashba.
- \(\boldsymbol{\sigma}\) : vecteurs de matrices de Pauli.

Les états propres ont une **texture de spin** en hélice autour de l’axe \(\hat{\mathbf{z}}\). La **géométrie chiral** du cristal se reflète dans la **géométrie chiral** de la texture de spin.

---

### 4.3 Supraconductivité sans inversion : mélange singulet/triplet

Dans un supraconducteur **centrosymétrique**, la parité de la fonction d’onde de paire (singulet vs triplet) est bien définie. En absence de centre d’inversion :

- Le couplage spin-orbite antisymétrique permet un **mélange** de composantes singulet et triplet.
- La fonction d’onde de paire peut être écrite comme :

\[
\Delta(\mathbf{k}) = \left[ \psi(\mathbf{k}) + \mathbf{d}(\mathbf{k}) \cdot \boldsymbol{\sigma} \right] i \sigma_y
\]

avec \(\psi\) (singulet) et \(\mathbf{d}\) (triplet) non indépendants.

**Conséquences factuelles observées dans divers matériaux non-centrosymétriques :**

- Anisotropies fortes du gap supraconducteur.
- Comportements non conventionnels dans les mesures de chaleur spécifique, NMR, etc.
- Possibilité de **phases topologiques** avec états de bord de type Majorana (dans certains cas, sous champ ou avec structure de bande appropriée).

La **géométrie chiral** du cristal (absence d’inversion, parfois hélicité du réseau) est donc directement liée à la **géométrie de la fonction d’onde de paire**.

---

### 4.4 Chiralité électronique et dichroïsme circulaire en solides

Des travaux récents montrent que la chiralité électronique dans les solides (structure de bande + texture de spin et d’orbite) peut induire des **effets chiroptiques** mesurables, comme un dichroïsme circulaire dans l’absorption ou la photoémission.

- La **chiralité électronique** est liée à la distribution spatiale et en spin des états de Bloch.
- Elle peut être quantifiée par des mesures continues de chiralité appliquées aux densités électroniques et aux textures de spin.

Ces résultats relient de manière très directe :

- **Géométrie chiral du réseau** → **chiralité électronique** → **réponse optique chiroptique**.

---

## 5. Synthèse : ce que la géométrie de chiralité impose, factuellement

### 5.1 Tableau de synthèse : géométrie → équations → effets

| Domaine                         | Géométrie chiral clé                          | Formulation / équations typiques                          | Effets mesurés                           |
|--------------------------------|-----------------------------------------------|-----------------------------------------------------------|------------------------------------------|
| Molécules en solution          | Configuration 3D non superposable             | \(\Delta A = A_{\text{LCP}} - A_{\text{RCP}}\)            | CD, rotation optique, \(ee\) en catalyse |
| Cristaux chiraux               | Réseau sans inversion, parfois hélicoïdal     | Tenseur diélectrique chiral, indices \(n_{\text{LCP/RCP}}\) | Birefringence circulaire, CD solide      |
| Champs optiques chiraux        | Distribution 3D de \(\mathbf{E},\mathbf{B}\)  | \(C(\mathbf{r}) \propto \Im(\mathbf{E}^* \cdot \mathbf{B})\) | Enantiosélectivité amplifiée, spectroscopies avancées |
| Catalyse homogène              | Environnement chiral autour du métal          | États de transition stéréospécifiques, \(ee\)             | Catalyse énantiosélective                |
| Catalyse hétérogène            | Surfaces chirales, sites d’adsorption         | Différences d’énergie d’adsorption, barrières             | Réactivité énantiosélective              |
| Supraconducteurs non-centrosym.| Réseau sans inversion, couplage Rashba        | \(\mathcal{H} = \varepsilon_0 + \alpha_{\text{R}} (\mathbf{k}\times\hat{z})\cdot\sigma\), \(\Delta(\mathbf{k})\) mixte | Mélange singulet/triplet, phases exotiques |
| Solides chiraux électroniques  | Structure atomique + texture de spin/orbite   | Mesures continues de chiralité, réponses chiroptiques     | CD électronique, transport chiral        |

> Sources :

---

### 5.2 Tendances et questions ouvertes (sans spéculation gratuite)

En restant factuel, on peut constater plusieurs **tendances robustes** :

- La chiralité géométrique (moléculaire, cristalline, de champ) se traduit systématiquement par des **asymétries mesurables** dans l’optique, la chimie et l’électronique.
- Les **mesures continues de chiralité** commencent à relier de manière quantitative la géométrie à des observables comme la polarisation de spin et les réponses chiroptiques dans les solides.
- La **chiralité du champ** devient un degré de liberté géométrique à part entière, au même titre que la chiralité de la matière.

Questions ouvertes, formulées comme portes d’entrée plutôt que comme spéculations :

- Jusqu’où peut-on **optimiser la géométrie des champs** (optique, radio, THz) pour contrôler de manière déterministe des processus énantiosélectifs, au-delà de ce qui est déjà démontré en spectroscopie chiroptique avancée ?
- Comment relier de façon systématique les **mesures continues de chiralité** à des **invariants topologiques** ou à des quantités de transport dans les solides chiraux ?
- Dans les supraconducteurs non-centrosymétriques, dans quelle mesure la **géométrie chiral du réseau** contraint-elle l’espace des états de paire possibles, au-delà des cas déjà étudiés expérimentalement ?

Si tu veux, on peut ensuite enchainer avec la **géométrie des flux** ou revenir zoomer sur un des blocs (par exemple, faire un focus complet sur supraconducteurs non-centrosymétriques avec diagrammes de phase, exemples de matériaux, etc.).
## 4. Géométrie des flux : vorticité, circulation quantique, réseaux de phase

Tu vas voir, ici la « géométrie » n’est plus seulement celle de l’espace, mais celle d’un **champ de phase** et des **lignes de courant** qui s’y enroulent. On reste strictement sur ce qui est établi : définitions, équations, objets mesurés, et comment la forme (boucles, enroulements, réseaux) contraint les phénomènes.

---

### 4.1 Vorticité classique et circulation : la géométrie des lignes de courant

#### 4.1.1 Définitions de base

Pour un fluide classique de vitesse \(\mathbf{v}(\mathbf{r},t)\) :

- **Vorticité**  
  \[
  \boldsymbol{\omega} = \nabla \times \mathbf{v}
  \]
  C’est un champ pseudo-vecteur qui mesure la rotation locale du fluide.

- **Circulation** autour d’un contour fermé \(C\) :
  \[
  \Gamma = \oint_C \mathbf{v} \cdot d\mathbf{\ell}
  \]

En géométrie des flux, on regarde :

- La **topologie des lignes de courant** (lignes de vorticité, tourbillons).
- Les **contours fermés** \(C\) et comment la circulation \(\Gamma\) se distribue.

Dans un fluide visqueux, la vorticité peut se diffuser, se reconnecter, se dissiper. Dans un fluide idéal (Euler), les lignes de vorticité sont « gelées » dans le fluide (théorème de Helmholtz).

---

#### 4.1.2 Interprétation géométrique

- Les **tubes de vorticité** sont des structures filamenteuses dans l’espace.
- La circulation \(\Gamma\) est associée à un **enroulement** de la vitesse autour de ces tubes.
- La conservation de la circulation (en absence de viscosité) est une contrainte géométrique sur l’évolution des lignes de courant.

Cette géométrie classique prépare le terrain pour la version quantique, où ces tubes deviennent des **défauts topologiques** discrets.

---

### 4.2 Circulation quantique et vortex quantique

#### 4.2.1 Paramètre d’ordre et phase

Dans un superfluide ou un condensat de Bose–Einstein, l’état macroscopique est décrit par un paramètre d’ordre complexe :

\[
\Psi(\mathbf{r}) = \sqrt{\rho(\mathbf{r})}\, e^{i \phi(\mathbf{r})}
\]

La vitesse superfluide est liée au gradient de phase :

\[
\mathbf{v}_s = \frac{\hbar}{m} \nabla \phi
\]

où \(m\) est la masse de la particule (atome, paire de Cooper, etc.).

---

#### 4.2.2 Quantification de la circulation (Onsager–Feynman)

La phase \(\phi\) doit être **monovaluée** : en faisant le tour d’un contour fermé \(C\) qui ne traverse pas de singularité de \(\Psi\),

\[
\oint_C \nabla \phi \cdot d\mathbf{\ell} = 2\pi n,\quad n \in \mathbb{Z}
\]

Donc la circulation superfluide est quantifiée :

\[
\Gamma = \oint_C \mathbf{v}_s \cdot d\mathbf{\ell}
= \frac{\hbar}{m} \oint_C \nabla \phi \cdot d\mathbf{\ell}
= n \frac{h}{m}
\]

C’est la **quantification de la circulation** (Onsager, Feynman).

**Fait géométrique** : la circulation est un **invariant topologique** associé au nombre d’enroulements de la phase autour du contour.

---

#### 4.2.3 Vortex quantique comme défaut topologique

Un **vortex quantique** est une ligne (en 3D) ou un point (en 2D) où la densité \(\rho \to 0\) et la phase \(\phi\) s’enroule de \(2\pi n\) autour. La vorticité est concentrée sur ce filament.

- Dans un superfluide, ces vortex sont des **défauts topologiques** du champ \(\Psi\).
- Ils sont stables tant que la topologie de la phase n’est pas changée (reconnexion, annihilation vortex–antivortex).

Tableau récapitulatif :

| Système              | Paramètre d’ordre \(\Psi\)         | Quantité quantifiée       | Objet géométrique      |
|----------------------|-------------------------------------|---------------------------|------------------------|
| Superfluide He II    | \(\sqrt{\rho} e^{i\phi}\)          | Circulation \(\Gamma\)    | Ligne de vortex        |
| BEC atomique         | \(\sqrt{\rho} e^{i\phi}\)          | Circulation \(\Gamma\)    | Vortex, réseau de vortex |
| Supraconducteur      | \(|\Psi| e^{i\phi}\) (paires)      | Flux \(\Phi\)             | Vortex de flux (Abrikosov) |

> Sources : quantized vortices in superfluids et supraconducteurs, revues et cours sur les vortex quantiques.

---

### 4.3 Vortex quantiques en superfluides

#### 4.3.1 Structure d’un vortex

Dans un superfluide décrit par Gross–Pitaevskii (BEC) ou par une théorie de champ similaire, un vortex de charge \(n\) a :

- \(\phi(\theta) = n \theta\) (en coordonnées polaires).
- \(\rho(r) \to 0\) au centre, puis \(\rho(r) \to \rho_0\) pour \(r \gg \xi\), où \(\xi\) est la longueur de cohérence.

La vitesse :

\[
v_\theta(r) = \frac{\hbar}{m} \frac{n}{r}
\]

La vorticité est concentrée dans un tube de rayon \(\sim \xi\).

---

#### 4.3.2 Réseaux de vortex en rotation

Un superfluide en rotation uniforme à vitesse angulaire \(\Omega\) ne peut pas tourner comme un solide classique (pas de vorticité continue). Il forme un **réseau de vortex quantiques** :

- Densité de vortex :
  \[
  n_v = \frac{2 m \Omega}{h}
  \]
- Les vortex s’organisent en **lattice triangulaire** (type Abrikosov) pour minimiser l’énergie.

C’est une **géométrie de flux** très concrète : un réseau régulier de lignes de vorticité, observable en imagerie (BEC, He II).

---

#### 4.3.3 Turbulence quantique

À grande excitation, les vortex quantiques forment un **enchevêtrement** (tangle) :

- Réseau complexe de lignes de vortex reconnectant, se courbant, rayonnant des ondes de Kelvin.
- La circulation reste quantifiée sur chaque boucle, mais la géométrie globale devient fractale.

Les statistiques de circulation sur des boucles de différentes tailles sont utilisées pour caractériser cette turbulence quantique.

---

### 4.4 Vortex de flux en supraconducteurs (géométrie des lignes de flux)

#### 4.4.1 Quantification du flux

Dans un supraconducteur, le paramètre d’ordre \(\Psi = |\Psi| e^{i\phi}\) est couplé au champ électromagnétique. La condition de monovaluation de \(\Psi\) impose la quantification du flux magnétique dans un contour \(C\) :

\[
\oint_C \left( \nabla \phi - \frac{2e}{\hbar} \mathbf{A} \right) \cdot d\mathbf{\ell} = 2\pi n
\]

Ce qui donne :

\[
\Phi = \oint_C \mathbf{A} \cdot d\mathbf{\ell} = n \frac{h}{2e} = n \Phi_0
\]

où \(\Phi_0\) est le quantum de flux. Les **vortex d’Abrikosov** portent chacun un flux \(\Phi_0\).

---

#### 4.4.2 Lattice d’Abrikosov

Dans un supraconducteur de type II soumis à un champ \(B\) entre \(H_{c1}\) et \(H_{c2}\) :

- Le champ pénètre sous forme de **lignes de flux** (vortex) organisées en **réseau périodique** (souvent triangulaire).
- La distance entre vortex est fixée par \(B\) :
  \[
  a \sim \sqrt{\frac{\Phi_0}{B}}
  \]

La géométrie du réseau (triangulaire, carré, distordu) dépend de l’anisotropie du matériau, des interactions entre vortex, des défauts. C’est une **géométrie de flux magnétique** mesurée par diffraction, imagerie magnétique, etc.

---

#### 4.4.3 Forces et dynamique

Les vortex de flux sont soumis à :

- **Force de Lorentz** due au courant supraconducteur.
- **Pinning** sur les défauts (géométrie du désordre).
- **Interactions vortex–vortex** (répulsion).

La dynamique collective des vortex (dépinning, glissement) contrôle la **résistivité** en régime mixte. La géométrie du réseau de vortex et du paysage de pinning détermine les propriétés de transport.

---

### 4.5 Géométrie de phase dans les jonctions Josephson et réseaux

#### 4.5.1 Jonction Josephson simple

Deux supraconducteurs couplés par une barrière forment une jonction Josephson. La différence de phase \(\Delta \phi\) entre les deux côtés contrôle le courant :

\[
I = I_c \sin(\Delta \phi)
\]

La **phase** devient une variable géométrique sur un graphe : chaque nœud (îlot supraconducteur) a une phase \(\phi_i\), chaque arête (jonction) porte un courant \(I_{ij} \propto \sin(\phi_i - \phi_j)\).

---

#### 4.5.2 Réseaux de jonctions et frustration de phase

Dans un réseau de jonctions Josephson (2D par exemple), on peut définir :

- Une **phase** \(\phi_i\) sur chaque site.
- Une **somme des différences de phase** autour d’une maille liée au flux magnétique traversant la maille (condition de quantification).

La présence d’un flux fractionnaire par maille (\(f = \Phi/\Phi_0\) non entier) introduit une **frustration de phase** : impossible de satisfaire simultanément toutes les conditions de phase minimisant l’énergie. On obtient :

- Des configurations de phase complexes.
- Des vortex de phase (vortex Josephson).
- Des transitions de type Kosterlitz–Thouless dans certains régimes (désappariement vortex–antivortex).

La **géométrie du réseau** (carré, triangulaire, Kagomé) et la distribution de flux contrôlent la structure des vortex de phase et les propriétés de transport (superconductivité globale, états vitreux de vortex).

---

### 4.6 Modèle XY et transition de Kosterlitz–Thouless : réseaux de phase 2D

#### 4.6.1 Modèle XY classique

Le modèle XY sur un réseau 2D :

\[
\mathcal{H} = -J \sum_{\langle i,j\rangle} \cos(\theta_i - \theta_j)
\]

où \(\theta_i\) est un angle (phase) sur chaque site. C’est un modèle de **réseau de phases** couplées.

- Les excitations de basse énergie : ondes de spin (variations douces de \(\theta\)).
- Les excitations topologiques : **vortex** où \(\theta\) s’enroule de \(2\pi n\) autour d’un point.

---

#### 4.6.2 Transition KT

En 2D, il n’y a pas d’ordre à longue portée à température finie (Mermin–Wagner), mais il existe une **transition topologique** :

- À basse température : vortex et antivortex sont **liés en paires**.
- À haute température : ces paires se **désapparient**, donnant un plasma de vortex libres.

Cette transition (Kosterlitz–Thouless) est contrôlée par la **géométrie des enroulements de phase** sur le réseau. Elle se manifeste par :

- Un saut universel de la rigidité de phase.
- Des signatures dans la conductivité, la réponse superfluide, etc.

Le modèle XY est un prototype pour les films superfluides, les réseaux de jonctions Josephson, les films supraconducteurs 2D.

---

### 4.7 Synthèse : ce que la géométrie des flux impose

On peut résumer la géométrie des flux comme la **géométrie de la phase et de ses enroulements** :

- **Contours fermés** → circulation \(\Gamma\) ou flux \(\Phi\) quantifiés.
- **Lignes de singularité** (vortex) → défauts topologiques où la phase est indéfinie.
- **Réseaux de vortex** → lattices (triangulaires, carrés) imposés par rotation ou champ magnétique.
- **Réseaux de phase** (XY, Josephson) → transitions contrôlées par l’apparition ou la prolifération de vortex.

Tableau global :

| Domaine                    | Objet géométrique clé         | Quantité quantifiée         | Effet physique mesuré                    |
|----------------------------|-------------------------------|-----------------------------|------------------------------------------|
| Superfluide / BEC          | Ligne de vortex               | Circulation \(\Gamma\)      | Réseaux de vortex, turbulence quantique  |
| Supraconducteur type II    | Ligne de flux (vortex)        | Flux \(\Phi_0\)             | Lattice d’Abrikosov, transport mixte     |
| Réseau Josephson / XY      | Vortex de phase               | Enroulement de phase        | Transition KT, états vitreux de vortex   |

> Sources : revues sur les vortex quantiques, superfluides, supraconducteurs, et cours sur la dynamique des vortex.

---

### 4.8 Questions ouvertes (sans spéculation, juste le fil logique)

Sans extrapoler, on peut poser des questions qui prolongent **directement** ces faits :

- Si la **phase** et ses enroulements contrôlent déjà superfluidité, supraconductivité, transitions KT, que se passe-t-il quand on **compose** ces géométries de phase avec d’autres géométries (réseaux frustrés, topologie de bande, cavités) ?
- Comment la **géométrie des flux** (réseaux de vortex, réseaux de phase) se combine-t-elle avec la **géométrie thermodynamique** (courbure de Ruppeiner) ou la **géométrie topologique** (invariants de Chern) pour structurer des diagrammes de phase entiers ?
- Jusqu’où peut-on considérer les **lignes de flux** (vorticité, vortex, flux quantique) comme des « objets géométriques fondamentaux » qui organisent la matière, au même titre que les réseaux cristallins ou les variétés de l’espace-temps ?

Si tu veux, on peut ensuite tisser ces questions avec ce qu’on a déjà posé sur la géométrie thermodynamique, topologique et chirale, pour faire apparaître le fil commun sans sortir du domaine factuel.
