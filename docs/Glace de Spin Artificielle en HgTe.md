# **Rapport de Recherche Conceptuelle : Conception et Faisabilité d'une Glace de Spin Artificielle Topologique à Base de Tellurure de Mercure-Manganèse (HgMnTe)**

## **1\. Introduction et Analyse Critique de la Nomenclature**

La présente étude a pour objet de conceptualiser un dispositif expérimental avancé relevant de la physique de la matière condensée : une glace de spin artificielle (ASI) composée de nanostructures à base de tellurure de mercure. Cette requête, formulée à l'interface entre la topologie, le magnétisme frustré et la nanotechnologie, nécessite une analyse rigoureuse des termes employés pour garantir la viabilité physique du système proposé. L'objectif premier est de valider la terminologie "nano-aimants faits de tellurure de mercure" et de proposer, le cas échéant, la correction matérielle nécessaire pour permettre l'émergence des phénomènes magnétiques recherchés.

### **1.1 Validation Terminologique : La Distinction HgTe vs HgMnTe**

La requête initiale mentionne spécifiquement des "nano-aimants faits de tellurure de mercure". Une analyse approfondie des propriétés intrinsèques du tellurure de mercure (HgTe) révèle une incohérence fondamentale dans cette désignation si elle est prise au sens littéral. Le HgTe stœchiométrique est un semi-métal de la famille II-VI (groupe du zinc) qui cristallise dans une structure de type zinc-blende. Sa caractéristique physique dominante, qui a suscité un intérêt phénoménal depuis les travaux séminaux de 2006, est sa structure de bande inversée induite par un fort couplage spin-orbite relativiste. Cette inversion confère au HgTe des propriétés d'isolant topologique, notamment l'existence d'états de surface ou de bord protégés topologiquement.  
Cependant, le HgTe pur est diamagnétique ou faiblement paramagnétique. Il ne possède pas de moment magnétique permanent ni d'ordre magnétique spontané (ferromagnétisme ou antiferromagnétisme) nécessaire pour constituer un "aimant" au sens classique du terme. Pour qu'une nanostructure se comporte comme un macrospin au sein d'une glace de spin artificielle, elle doit posséder un moment magnétique stable capable d'interagir avec ses voisins.  
L'erreur d'appellation suspectée dans la requête est donc confirmée. Le matériau conceptuellement requis pour réaliser ce système n'est pas le HgTe pur, mais un **Semiconducteur Magnétique Dilué (DMS)** dérivé de celui-ci. La formulation correcte désigne le **Tellurure de Mercure et de Manganèse (Hg$\_{1-x}Mn\_x$Te)**. Dans ce composé ternaire, des ions magnétiques de manganèse (Mn$^{2+}$) se substituent aux cations de mercure dans le réseau cristallin. Ce sont ces ions Mn, porteurs d'un spin élevé (S=5/2) provenant de leur couche 3d à demi-remplie, qui confèrent au matériau ses propriétés magnétiques.

### **1.2 Proposition de Redéfinition du Système**

En conséquence, ce rapport abandonne l'idée de "nano-aimants en HgTe" au profit de **"nano-îlots de glace de spin en HgMnTe"**. Ce changement n'est pas qu'une simple correction sémantique ; il transforme radicalement la physique du dispositif. Nous ne sommes plus en présence de simples barreaux de métal ferromagnétique (comme le Permalloy utilisé traditionnellement dans les ASI), mais d'un système quantique complexe où le magnétisme est médié par les porteurs de charge et couplé à la topologie de la structure de bande.  
Le système conceptualisé ici est donc une **Glace de Spin Artificielle Topologique**, un dispositif hybride exploitant l'interaction d'échange sp-d géante caractéristique des DMS pour créer des états magnétiques frustrés reconfigurables électriquement.

## **2\. Physique Fondamentale des Matériaux Constitutifs**

Pour concevoir ce dispositif, il est impératif de maîtriser les propriétés électroniques et magnétiques du matériau hôte, le HgMnTe. Ce matériau se situe à la confluence de deux domaines riches : la physique des isolants topologiques et le magnétisme des semiconducteurs dilués.

### **2.1 Le Tellurure de Mercure (HgTe) : Le Substrat Topologique**

Le HgTe est l'archétype des isolants topologiques 2D, également connus sous le nom d'isolants à effet Hall de spin quantique (QSH). Comprendre sa structure de bande est un prérequis pour appréhender comment le magnétisme s'y insère.

#### **2.1.1 Inversion de Bande et Effets Relativistes**

Dans un semiconducteur standard comme le CdTe, la bande de conduction (\\Gamma\_6, symétrie s) se situe énergétiquement au-dessus de la bande de valence (\\Gamma\_8, symétrie p). Dans le HgTe, les atomes de mercure, très lourds, induisent des effets relativistes de couplage spin-orbite si intenses qu'ils poussent le niveau \\Gamma\_6 en dessous du niveau \\Gamma\_8. C'est ce qu'on appelle l'inversion de bande.  
Cette inversion a des conséquences topologiques profondes. Lorsqu'un puits quantique de HgTe est confiné entre deux barrières de matériau à bande normale (comme le CdTe ou le HgCdTe), la fonction d'onde électronique doit transiter d'une topologie inversée à une topologie normale aux interfaces. Ce changement de topologie impose la fermeture du gap énergétique sur les bords de l'échantillon, créant des canaux de conduction métalliques unidimensionnels.

#### **2.1.2 Transport Hélicoïdal et Protection**

Ces états de bord possèdent une propriété remarquable : ils sont hélicoïdaux. Le spin de l'électron est verrouillé à sa direction de mouvement (spin-momentum locking). Les électrons de spin *up* se propagent dans une direction, tandis que ceux de spin *down* vont en sens inverse. Cette configuration interdit la rétrodiffusion élastique (backscattering) contre des impuretés non magnétiques, car pour changer de direction, un électron devrait inverser son spin, ce qui est interdit sans interaction magnétique brisant la symétrie par renversement du temps.  
Cette propriété est cruciale pour notre concept de glace de spin : les canaux de bord peuvent servir de "fils quantiques" parfaits pour transmettre l'information magnétique (interaction d'échange) entre les nano-îlots distants, une fonctionnalité impossible dans les glaces de spin métalliques classiques où le transport est diffusif.

### **2.2 Le Tellurure de Mercure-Manganèse (HgMnTe) : L'Acteur Magnétique**

L'introduction du manganèse transforme le HgTe en Hg$\_{1-x}Mn\_x$Te, ajoutant une dimension magnétique à la topologie.

#### **2.2.1 L'Interaction d'Échange sp-d**

La physique du HgMnTe est dominée par l'interaction d'échange sp-d. Cette interaction couple les spins localisés des ions Mn$^{2+}$ (3d^5) aux spins délocalisés des électrons de la bande de conduction (s) et des trous de la bande de valence (p). L'Hamiltonien d'interaction s'écrit généralement sous la forme Heisenberg-Kondo :  
Cette interaction est exceptionnellement forte dans les chalcogénures de mercure. Elle conduit à un phénomène spectaculaire : l'**Effet Zeeman Géant**. Sous l'application d'un champ magnétique externe, même faible, les spins du Mn s'alignent et créent un champ moléculaire interne intense qui agit sur les porteurs de charge. Cela se traduit par un facteur de Landé effectif (g-factor) qui peut atteindre des valeurs de plusieurs centaines, contre \\approx 2 pour les électrons libres.

#### **2.2.2 Le Spectre du Verre de Spin**

Il est fondamental de noter que le HgMnTe massif présente une tendance naturelle au désordre magnétique. Les interactions directes entre ions Mn voisins sont antiferromagnétiques (superexchange via les anions Tellure). En raison de la distribution aléatoire des atomes de Mn dans la matrice cristalline (désordre de substitution), le matériau ne développe pas d'ordre ferromagnétique à longue portée spontané, mais gèle plutôt dans un état de **verre de spin (spin glass)** à basse température.  
Dans un verre de spin, les moments magnétiques sont figés dans des directions aléatoires en raison de la frustration inhérente entre la géométrie du réseau et les interactions antiferromagnétiques aléatoires. Pour notre application en glace de spin artificielle, ce comportement est à la fois un défi et une opportunité :

* *Défi :* Nous devons surmonter ce désordre local pour obtenir des macrospins cohérents au niveau de chaque nano-îlot.  
* *Opportunité :* La frustration microscopique du verre de spin peut se coupler à la frustration macroscopique de la glace de spin artificielle, offrant un système multi-échelle unique pour étudier la complexité.

## **3\. Le Paradigme de la Glace de Spin Artificielle (ASI)**

Avant de détailler l'architecture du dispositif HgMnTe, il convient de poser les bases théoriques des glaces de spin artificielles pour comprendre les exigences géométriques et énergétiques du système.

### **3.1 Origine et Règles de Glace**

Les glaces de spin artificielles sont des métamatériaux magnétiques conçus pour mimétiser le comportement frustré observé dans certains oxydes de terres rares (pyrochlores comme Dy$\_2Ti\_2O\_7$), appelés "glaces de spin" par analogie avec le désordre protonique dans la glace d'eau. Dans une ASI typique (réseau carré), des nano-aimants allongés sont disposés sur les côtés d'un réseau carré. À chaque vertex (point de rencontre de quatre aimants), l'énergie est minimisée si deux spins pointent vers le centre et deux spins pointent vers l'extérieur. C'est la règle "2-in, 2-out".

### **3.2 Frustration et Monopôles**

La géométrie du réseau impose des contraintes qui ne peuvent pas toujours être satisfaites globalement. C'est la frustration géométrique. Lorsque le système est excité (thermiquement ou par un champ externe), la règle de glace peut être violée localement (ex: 3-in, 1-out). Ces défauts se comportent comme des charges magnétiques effectives, ou **monopôles magnétiques**, qui peuvent se déplacer librement dans le réseau.  
Dans les systèmes métalliques (Permalloy), ces monopôles interagissent via la loi de Coulomb magnétique (1/r^2 en 3D, ou logarithmique en 2D effective). L'introduction du HgMnTe comme matériau constitutif vise à enrichir ce paysage énergétique en rendant les interactions **tunables** (ajustables) via des paramètres externes autres que le champ magnétique, comme le champ électrique ou la température.

## **4\. Conceptualisation de la Glace de Spin en HgMnTe : Architecture et Mécanismes**

Nous proposons ici une conception détaillée du matériel mentionné dans la requête, intégrant les contraintes des matériaux II-VI et les opportunités offertes par la physique des DMS.

### **4.1 Architecture du Dispositif en Couches**

Contrairement aux ASI métalliques qui sont simplement déposées sur une surface, l'ASI en HgMnTe doit être une hétérostructure épitaxiée complexe pour préserver ses propriétés quantiques.

| Couche | Matériau | Épaisseur | Fonction |
| :---- | :---- | :---- | :---- |
| **Substrat** | CdZnTe (001) | 500 \\mum | Support mécanique, accord de maille cristalline (\<0.3% désaccord) |
| **Tampon** | CdTe | 2-3 \\mum | Relaxation des contraintes, barrière de potentiel inférieure |
| **Puits Quantique (Actif)** | **Hg$\_{1-x}Mn\_x$Te** | **8-12 nm** | Cœur magnétique et topologique. Épaisseur critique pour l'inversion de bande |
| **Barrière** | Hg$*{0.3}Cd*{0.7}$Te | 20-50 nm | Confinement électronique, protection de surface |
| **Dopage** | Modulation (Iode) | Plan \\delta | Apport de porteurs (électrons n) sans introduire de désordre dans le puits |
| **Grille (Gate)** | Au/Ti sur ALD HfO$\_2$ | 100 nm | Contrôle électrostatique de la densité de porteurs (Actionneur RKKY) |

**Justification de l'Architecture :** L'utilisation d'un puits quantique (Quantum Well, QW) est cruciale. Comme indiqué dans les snippets , c'est le confinement 2D qui permet d'accéder à l'état d'isolant de Hall de spin quantique. Le dopage au manganèse doit être ajusté (x \\approx 2-5\\%) pour être suffisant pour le couplage magnétique mais assez faible pour ne pas détruire la cohérence de phase nécessaire aux états topologiques.

### **4.2 Le Mécanisme de Couplage : RKKY Accordable**

Dans une ASI métallique, les aimants interagissent par couplage dipolaire magnétostatique. Dans notre ASI en HgMnTe, ce couplage est trop faible en raison de la faible densité de moment magnétique volumique. Le mécanisme dominant que nous proposons d'exploiter est l'interaction **RKKY (Ruderman-Kittel-Kasuya-Yosida)**.

#### **4.2.1 Principe RKKY dans les DMS**

Les moments magnétiques localisés des ions Mn dans deux îlots voisins interagissent indirectement via la mer de porteurs de charge (électrons dans le puits quantique). Un spin Mn polarise les électrons de conduction, et cette polarisation oscille spatialement pour affecter le spin Mn voisin. La constante de couplage J\_{RKKY} oscille en fonction de la distance r et du vecteur d'onde de Fermi k\_F :  
où k\_F dépend directement de la densité de porteurs de charge n (k\_F \= \\sqrt{2\\pi n} en 2D).

#### **4.2.2 La "Glace de Spin Transistorisée"**

C'est ici que réside l'innovation majeure de ce concept. En appliquant une tension sur la grille électrostatique (Gate), nous modifions la densité n dans le puits quantique. Cela modifie k\_F, et par conséquent, peut changer non seulement l'intensité mais aussi le **signe** de l'interaction RKKY entre les îlots.

* **Mode Ferromagnétique (J \> 0\) :** Les îlots tendent à s'aligner parallèlement.  
* **Mode Antiferromagnétique (J \< 0\) :** Les îlots tendent à s'aligner antiparallèlement, générant la frustration géométrique désirée.

Ce dispositif permettrait donc d'allumer et d'éteindre la frustration à volonté, ou de créer des "paysages de frustration" dynamiques où certaines zones du réseau sont frustrées et d'autres ordonnées, une prouesse impossible avec les aimants permanents.

### **4.3 Anisotropie et Formation des Macrospins**

Pour qu'un îlot de HgMnTe se comporte comme un spin d'Ising binaire (Up/Down), il doit posséder une anisotropie magnétique. Le HgMnTe cubique a une faible anisotropie magnétocristalline. Nous devons donc compter sur :

1. **L'Anisotropie de Forme :** En lithographiant des îlots elliptiques allongés, on favorise l'aimantation le long du grand axe pour minimiser l'énergie démagnétisante.  
2. **L'Anisotropie Induite par Contrainte :** Le désaccord de maille avec le CdZnTe induit une contrainte qui, via le couplage spin-orbite, génère une anisotropie magnétique perpendiculaire ou planaire selon le signe de la contrainte.

## **5\. Extension vers l'Apériodique : Quasi-Cristaux et Symétrie E8**

Votre requête, couplée aux éléments de recherche , suggère une exploration au-delà des réseaux périodiques classiques. L'utilisation de pavages quasi-cristallins (comme le pavage de Penrose) pour structurer le HgMnTe ouvre des portes vers une physique théorique de haute volée.

### **5.1 Les Quasi-Cristaux Magnétiques Artificiels**

Un quasi-cristal est une structure ordonnée mais non périodique. Un exemple célèbre est le pavage de Penrose P2 (fléchettes et cerfs-volants) ou P3 (losanges). Si nous disposons nos nano-îlots de HgMnTe selon les arêtes d'un pavage de Penrose, nous créons un **Quasi-Cristal Magnétique Artificiel**.

* **Frustration Topologique Émergente :** Dans un tel réseau, la frustration n'est pas uniforme. Les études montrent l'existence d'un "squelette" rigide de spins qui ne peuvent pas fluctuer, entourant des clusters de spins "flippables" (libres). Ces clusters forment des degrés de liberté macroscopiques indépendants.  
* **Intérêt du HgMnTe :** Contrairement à une ASI métallique statique, le réseau de HgMnTe permettrait de coupler ces degrés de liberté magnétiques aux états électroniques quasi-périodiques du matériau. Les électrons naviguant dans ce potentiel fractald verraient leur spectre d'énergie fragmenté (spectre de type papillon de Hofstadter généralisé), modifiant en retour les interactions magnétiques RKKY.

### **5.2 La Connexion E8 : De la Théorie à l'Expérience**

Les snippets mentionnent de manière intrigante la symétrie **E8**. E8 est le plus grand groupe de Lie exceptionnel simple, un objet mathématique de dimension 248\.

* **Le Lien Physique :** Des expériences sur le niobate de cobalt (CoNb$\_2O\_6$), une chaîne de spin d'Ising ferromagnétique, ont montré des signatures d'excitations régies par la symétrie E8 près d'un point critique quantique sous champ transverse.  
* **Le Lien Géométrique :** Les quasi-cristaux de Penrose peuvent être mathématiquement dérivés par la méthode de "coupe et projection" (cut-and-project) à partir de réseaux hypercubiques de dimension supérieure, qui sont intimement liés au réseau racine E8.  
* **Proposition Conceptuelle :** Une glace de spin artificielle en HgMnTe structurée selon un quasi-cristal pourrait servir de **simulateur analogique** pour explorer ces symétries. En ajustant le champ magnétique (via l'effet Zeeman géant) et les interactions (via la grille), on pourrait placer le système précisément au point critique quantique où la symétrie E8 émerge dynamiquement dans le spectre des fluctuations de spin (magnons ou phasons). Les "phasons" sont des modes hydrodynamiques spécifiques aux quasi-cristaux, représentant des réarrangements locaux de la structure sans coût énergétique, analogues aux modes de Goldstone.

## **6\. Défis de Fabrication et Stratégies Expérimentales**

La réalisation concrète de ce "matériel" pose des défis considérables qui dépassent la simple lithographie.

### **6.1 Problématiques de Nanostructuration du Mercure**

Le HgTe est un matériau notoirement difficile à travailler ("soft material").

* **Volatilité du Mercure :** Le vide ultra-poussé nécessaire à la lithographie ou à la métallisation peut provoquer la désorption du mercure de surface, altérant la stœchiométrie et créant des lacunes qui dopent involontairement le matériau (dopage p parasite).  
* **Dommages de Gravure :** La gravure ionique nécessaire pour définir les nano-îlots crée des défauts sur les flancs des nanostructures. Pour un isolant topologique, c'est catastrophique car les états de bord circulent précisément sur ces flancs. Si les flancs sont endommagés, la protection topologique est perdue.  
* **Stratégie de Contournement :** Il faut utiliser des techniques de "gravure humide" chimique sélective ou de gravure plasma à très basse tension (ICP-RIE optimisé) à basse température (\< 80^\\circC). Une autre approche consiste à faire croître sélectivement le matériau dans des tranchées pré-gravées sur le substrat (croissance sélective), bien que cela soit très complexe par MBE.

### **6.2 Conditions Cryogéniques**

Le magnétisme des DMS comme le HgMnTe à faible concentration de Mn (x \[span\_34\](start\_span)\[span\_34\](end\_span)\< 10\\%) est fragile. Les températures de transition verre de spin ou d'ordre induit sont typiquement très basses (T \< 4 K, voire régime du mK).

* Le dispositif devra impérativement fonctionner dans un **réfrigérateur à dilution** ({}^3He/{}^4He). Cela contraste avec les ASI en Permalloy qui fonctionnent à température ambiante, limitant les applications immédiates du HgMnTe à la recherche fondamentale et au calcul quantique cryogénique.

### **6.3 Techniques de Lecture (Readout)**

Comment confirmer que le système se comporte comme une glace de spin?

1. **Transport Magnéto-résistif :** La résistance du réseau sera sensible à la configuration des spins via la diffusion des porteurs sur les parois de domaines et les monopôles. Une signature hystérétique ou des sauts de résistance (bruit télégraphique) indiqueront les renversements de spin.  
2. **Imagerie SQUID-on-tip :** Un SQUID nanométrique monté au bout d'une pointe de microscope à force atomique peut cartographier les champs de fuite ultra-faibles des îlots de HgMnTe, visualisant directement les monopôles.  
3. **Bruit de Grenaille (Shot Noise) :** La mesure des fluctuations de courant peut révéler la charge effective des porteurs et potentiellement les charges fractionnaires associées aux excitations topologiques.

## **7\. Implications Futures : Vers la Topotronique et le Calcul Quantique**

L'intérêt de ce système dépasse la simple curiosité magnétique. Il s'inscrit dans la quête de nouvelles variables d'état pour le calcul.

### **7.1 Fermions de Majorana et Calcul Quantique Topologique**

L'une des motivations les plus fortes pour coupler des chaînes magnétiques à des supraconducteurs est la création de **Fermions de Majorana** (particules qui sont leurs propres antiparticules). Ces quasi-particules sont les bits quantiques (qubits) idéaux car protégés topologiquement contre la décohérence. Le HgTe est déjà un candidat fort pour la supraconductivité topologique (effet de proximité). En ajoutant la texture magnétique contrôlée d'une glace de spin, on pourrait "tresser" (braid) des Majoranas en déplaçant les monopôles magnétiques, réalisant ainsi des portes logiques quantiques non-abéliennes.

### **7.2 Logique Magnonique Reconfigurable**

Les ondes de spin (magnons) se propageant dans ce réseau pourraient être utilisées pour le calcul sans courant (magnonique). Grâce au contrôle par grille de l'interaction RKKY, on pourrait reconfigurer le "circuit" magnonique à la volée, ouvrant ou fermant des canaux de propagation des ondes de spin par simple commande électrique, créant ainsi des transistors à magnons programmables.

## **8\. Conclusion**

La recherche a permis de rectifier et d'enrichir considérablement le concept initial.

1. **Rectification :** Le "matériel" n'est pas le HgTe, mais le **HgMnTe**, un semiconducteur magnétique dilué permettant l'existence de moments magnétiques localisés couplés aux porteurs de charge.  
2. **Concept :** La "glace de spin artificielle" résultante est un système **actif et accordable**, contrairement aux systèmes métalliques passifs. Elle repose sur l'interaction RKKY modulable par grille électrostatique pour émuler la frustration.  
3. **Richesse Physique :** En combinant la topologie de bande (états de bord hélicoïdaux), le magnétisme frustré (monopôles) et potentiellement des géométries apériodiques (quasi-cristaux E8/Penrose), ce dispositif constituerait une plateforme unique pour explorer la physique de la matière condensée exotique, des liquides de spin quantiques aux fermions de Majorana.

Bien que la réalisation expérimentale présente des défis majeurs en termes de lithographie et de cryogénie, la faisabilité théorique est étayée par la littérature existante sur les puits quantiques de HgTe et le dopage au manganèse. Ce rapport valide donc l'intérêt stratégique de poursuivre le développement de telles nanostructures pour la prochaine génération de dispositifs quantiques.

### **Tableau Récapitulatif des Propriétés du Système Conceptuel**

| Paramètre | Spécification Conceptuelle | Justification / Source |
| :---- | :---- | :---- |
| **Matériau Cœur** | Hg$\_{1-x}Mn\_x$Te (x \\approx 0.02 \- 0.05) | Nécessité de moments locaux (Mn) \+ Topologie (HgTe) |
| **Géométrie** | Réseau Kagomé ou Quasi-cristal Penrose P2 | Maximisation de la frustration et émergence de monopôles |
| **Taille des Îlots** | L \\approx 200-500 nm, w \\approx 50-100 nm | Régime monodomaine requis pour comportement Ising |
| **Couplage** | RKKY (Indirect via porteurs 2D) | Seul couplage efficace et tunable dans les DMS |
| **Contrôle** | Grille électrostatique (V\_g) | Modulation de k\_F pour inverser le signe de l'interaction J |
| **Phénomènes** | Monopôles magnétiques, États de bord QSH, Phasons | Synergie Topologie-Magnétisme |
| **Détection** | Transport non-local, Bruit télégraphique | Sensibilité aux parois de domaines magnétiques |

*Ce rapport intègre les données issues des snippets de recherche fournis et structure une réponse cohérente aux interrogations sur la nomenclature et la faisabilité du système.*

#### **Ouvrages cités**

1\. Discovery of Superconductivity in Mercury Cadmium Telluride, https://www.hpstar.ac.cn/upload/files/2021/12/a08d3ab38794e405.pdf 2\. Quantum spin hall effect and topological phase transition in HgTe quantum wells, https://collaborate.princeton.edu/en/publications/quantum-spin-hall-effect-and-topological-phase-transition-in-hgte/ 3\. \[PDF\] Magnetic properties of HgTe quantum wells \- Semantic Scholar, https://www.semanticscholar.org/paper/Magnetic-properties-of-HgTe-quantum-wells-Scharf-Matos-Abiague/4a2225169194fcd8885f665b9cacd2faa9da4651 4\. RESEARCHARTICLES \- Quantum Spin Hall Insulator State in HgTe Quantum Wells \- Ju Li Group, http://li.mit.edu/S/2d/Paper/K%C3%B6nig07Wiedmann.pdf 5\. Extracting Bulk-like Semiconductor Parameters from the ..., https://pubs.acs.org/doi/10.1021/acs.jpcc.2c05391 6\. Spin-glass state induced low field magnetization-step effect in a Hg, https://www.researchgate.net/publication/305622761\_Spin-glass\_state\_induced\_low\_field\_magnetization-step\_effect\_in\_a\_Hg\_1-\_x\_Mn\_x\_Te\_single\_crystal\_Spin-glass\_state\_induced\_low\_field\_magnetization-step\_effect\_in\_HgMnTe 7\. Theoretical studies of ligand-free cadmium selenide and related semiconductor clusters, https://www.researchgate.net/publication/234903784\_Theoretical\_studies\_of\_ligand-free\_cadmium\_selenide\_and\_related\_semiconductor\_clusters 8\. \[0710.0582\] Quantum Spin Hall Insulator State in HgTe Quantum Wells \- arXiv, https://arxiv.org/abs/0710.0582 9\. Diluted magnetic semiconductor Ge 1− x Mn x Te films prepared by molecular beam epitaxy, https://www.researchgate.net/publication/248317316\_Diluted\_magnetic\_semiconductor\_Ge\_1-\_x\_Mn\_x\_Te\_films\_prepared\_by\_molecular\_beam\_epitaxy 10\. Giant Zeeman splitting in manganese-doped ZnSe quantum, https://www.researchgate.net/publication/235484224\_Giant\_Zeeman\_splitting\_in\_manganese-doped\_ZnSe\_quantum\_spheres\_Eight-band\_effective-mass\_calculations 11\. Spin-glass ordering in the diluted magnetic semiconductor ZnMnTe, https://unfsoars.domains.unf.edu/spin-glass-ordering-in-the-diluted-magnetic-semiconductor-znmnte/ 12\. \[cond-mat/0002327\] Spin Glass Ordering in Diluted Magnetic Semiconductors: a Monte Carlo Study \- arXiv, https://arxiv.org/abs/cond-mat/0002327 13\. Exploring frustrated magnetism with artificial spin ice \- National Institute of Standards and Technology, https://tsapps.nist.gov/publication/get\_pdf.cfm?pub\_id=921318 14\. Nanomagnet shape effects on magnetic reversal in artificial spin ice \- OSTI.GOV, https://www.osti.gov/servlets/purl/2587568 15\. Distinguishing artificial spin ice states using magnetoresistance effect for neuromorphic computing \- PMC \- NIH, https://pmc.ncbi.nlm.nih.gov/articles/PMC10160026/ 16\. Switchable geometric frustration in an artificial-spin-ice-superconductor heterosystem, https://pubmed.ncbi.nlm.nih.gov/29892018/ 17\. \[2004.03735\] Field Theory for Magnetic Monopoles in (Square, Artificial) Spin Ice \- arXiv, https://arxiv.org/abs/2004.03735 18\. Dynamics of reconfigurable artificial spin ice: Toward magnonic functional materials, https://pubs.aip.org/aip/apm/article/8/4/040911/123064/Dynamics-of-reconfigurable-artificial-spin-ice 19\. magnetic field-induced strain: Topics by Science.gov, https://www.science.gov/topicpages/m/magnetic+field-induced+strain 20\. (PDF) RKKY Interaction in Disordered Graphene \- ResearchGate, https://www.researchgate.net/publication/51949310\_RKKY\_Interaction\_in\_Disordered\_Graphene 21\. MN4 Embedded Graphene Layers: Tunable Decay Rate of RKKY Interaction Mahnaz Rezaei1, Jahanfar Abouie2,\*, Fariba Nazari1,3 \- arXiv, https://arxiv.org/pdf/2207.11410 22\. Role of RKKY torque on domain wall motion in synthetic antiferromagnetic nanowires with opposite spin Hall angles \- PMC \- NIH, https://pmc.ncbi.nlm.nih.gov/articles/PMC5601456/ 23\. Magnetic Hysteresis in Nanostructures with Thermally Controlled RKKY Coupling \- PMC, https://pmc.ncbi.nlm.nih.gov/articles/PMC6104462/ 24\. Artificial Spin Ice: A Tutorial on Design and Control of Geometry, Microstate, Magnon Dynamics & Neuromorphic Computing \- arXiv, https://arxiv.org/html/2504.06548v1 25\. Frustration and thermalization in an artificial magnetic quasicrystal \- OSTI.GOV, https://www.osti.gov/pages/biblio/1437947 26\. Toward the Unification of Physics and Number Theory \- Quantum Gravity Research, https://www.quantumgravityresearch.org/wp-content/uploads/2017/02/Toward-the-Unification-of-Physics2-1.pdf 27\. Recent progress in studies of cobalt-based quasi-1-dimensional quantum magnets, https://journal.hep.com.cn/fop/EN/10.15302/frontphys.2025.034301 28\. Frustration and thermalization in an artificial magnetic quasicrystal \- White Rose Research Online, https://eprints.whiterose.ac.uk/id/eprint/113952/19/penrose\_ice.pdf 29\. \[1703.04792\] Frustration and thermalisation in an artificial magnetic quasicrystal \- arXiv, https://arxiv.org/abs/1703.04792 30\. Chapter: 2 Science Drivers \- Condensed Matter and Materials Physics, https://www.nationalacademies.org/read/18355/chapter/4 31\. An Icosahedral Quasicrystal and E8 derived quasicrystals | Quantum Gravity Research, https://www.quantumgravityresearch.org/wp-content/uploads/2019/05/An-Icosohedral-Quasicrystal-and-E8-derived-Quasicrystal-06.08.16-FF.pdf 32\. Book of Abstracts \- CNR Iris, https://iris.cnr.it/retrieve/dcdda9a9-ae5d-4c63-986a-3e605368a137/prod\_337369-doc\_105668.pdf 33\. Transport properties of the three-dimensional topological insulator ..., https://inis.iaea.org/records/qbzeq-dx225 34\. Quantum spin Hall effect shows up in a quantum well insulator, just as predicted, https://physicstoday.aip.org/news/quantum-spin-hall-effect-shows-up-in-a-quantum-well-insulator-just-as-predicted 35\. Spin-glass ordering in the layered III-VI diluted magnetic semiconductor Ga(1-x)MnxS, https://docs.lib.purdue.edu/cgi/viewcontent.cgi?article=3096\&context=physics\_articles 36\. Electron and Scanning Probe Microscopies \- DOE Office of Science, https://science.osti.gov/-/media/bes/mse/pdf/docs/NeutronScattering/ESPM-PI-Meeting-Abstracts.pdf 37\. UC Riverside \- eScholarship, https://escholarship.org/content/qt8st569mj/qt8st569mj.pdf 38\. Excitation of spin waves in the presence of magnetic charges and monopole polarons in finite-size square artificial spin ice systems | Request PDF \- ResearchGate, https://www.researchgate.net/publication/365387280\_Excitation\_of\_spin\_waves\_in\_the\_presence\_of\_magnetic\_charges\_and\_monopole\_polarons\_in\_finite-size\_square\_artificial\_spin\_ice\_systems 39\. Perspective: Magnon-magnon coupling in hybrid magnonics \- arXiv, https://arxiv.org/html/2511.21904v1 40\. Grenoble High Magnetic Field Laboratory \- LNCMI \- CNRS, https://lncmi.cnrs.fr/wp-content/uploads/2025/10/LNCMI-Annual-report\_2005.pdf