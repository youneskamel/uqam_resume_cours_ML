# MIGD UQAM : resumés des cours ML 🎓

Un repo qui contiendra un document markdown qui resume ce quel'on a appris durant les cours d'apprentissage automatique que nous avons suivi a l'uqam. Ceux ci sont inf7710, inf8100 et inf7370.

## INF7710 ⛏️

## INF8100 📊

Le cours INF8100, intitulé concepts et techniques en fouille et exploration de données. Ce cours est une introduction générale à la science des données, qui couvre également les  mathématiques nécessaire à l'étude de ce sujet.

La première séance de cours a servi à définir ce qu’est la science des données et quels sont ces buts. Une phrase du cours qui semble bien incarner ce qu’est la science des données est la suivante :

“Un scientifique de données a pour rôle d’extraire des informations exploitables (actionable insights) des données"

Lors de ce cours nous avons aussi discuté des outils utilisés par les scientifiques de données tels que python, R et les Jupyter notebooks. Nous avons également défini les étapes d’un projet en science de données (définition de la question , sélectionner des données, pré-traitement, transformation, fouille, evaluation et validation)

Les cours suivants nous permirent de revoir les mathématiques préalables à la science des données, soit l'algèbre linéaire et les statistiques. Nous avons revu les additions et multiplication de vecteurs/matrices, les valeurs propres et la décomposition en valeurs singulières notamment, pour l'algèbre linéaire.

Pour les statistiques, nous avons vu la loi des grands nombres, les tests statistiques, les p-values, les lois de probabilités, etc…

Puis, le chapitre/cours suivant fut une étude d’un projet de science des données de bout en bout. A l’aide d’un notebook Jupyter nous avons mené un petit projet de science des données en classe tout en expliquant chaque étape. Cela nous a permis de voir en détail le nettoyage des données, la transformation des données et la visualisation par exemple.

Nous avons ensuite abordé la régression, une technique statistique qui permet de créer des modèles pour faire de la prédiction et de la classification. Nous avons vu la régression linéaire, logistique et polynomiale. Nous avons également abordé d'autres types de modèles tels que les SVM. Ce chapitre est une introduction aux fondamentaux de l'apprentissage automatique supervisé, il fut donc crucial pour nous.

Les notions abordées ensuite sont celles de la réduction de la dimensionnalité et celle du partitionnement. Nous avons notamment traité le sujet de l’analyse en composante principale (PCA/ACP) et de la LDA (linear discriminant analysis). Ensuite, nous avons appris les algorithmes k-means, les mélanges gaussiens et l’algorithme Expectation Maximization. Nous avons donc été introduits à différents algorithmes centraux de l’apprentissage non-supervise. 

## INF7370 🤖

Le cours INF7710, intitulé apprentissage automatique, est un cours d’introduction générale à l’apprentissage automatique, couvrant la majorité des sujets du domaine. Le cours nous a permis à la fois de mettre en pratique des algorithmes d'apprentissage automatique, mais aussi d'apprendre les mathématiques et les algorithmes derrière différents modèles.

Le premier cours commence par définir l'apprentissage automatique, soit ; 

“ll s’agit de concevoir des algorithmes capables, à partir d’un nombre important d’exemples, d’en assimiler la nature afin de pouvoir appliquer ce qu’ils ont ainsi appris aux cas futurs.”

En d’autres termes, l’apprentissage automatique est un ensemble de techniques permettant à un programme de réaliser un tâche et de s'y améliorer sans être programmé explicitement. Nous avons également abordé la distinction entre l’apprentissage supervisé et non-supervisé (c.a.d. la présence d'étiquettes ou labels).

Le deuxième cours fut une introduction aux arbres de décision. Ce terme caractérise un type de modèle d’apprentissage automatique dont la représentation est une structure de données d’arbre. Ces arbres permettent de prendre des décisions en répondant aux questions contenues dans leurs feuilles et en suivant la branche associée à la réponse. Nous avons notamment vu l'algorithme de Hunt pour entraîner les arbres de décision.

Le troisième cours porta sur l'apprentissage d’ensembles. Cette technique consiste à apprendre différents modèles d’apprentissage automatique et à les combiner afin d’obtenir une meilleure performance. Il existe notamment, le bagging, le pasting et le boosting, différentes formes d’apprentissage d’ensemble.

Ensuite, nous avons abordé la classification bayésienne naïve. Cette technique permet de faire de la classification en utilisant la formule de Bayes :


P(A|B) = P(B|A).P(A) / P(B) 

Nous avons ensuite expliqué les réseaux bayésiens. Ces réseaux permettent de représenter les probabilités conditionnelles de divers événements de façon compacte. En utilisant, également la formule de Bayes, ils permettent de faire de la prédiction et de la classification.

Les séances qui suivirent furent dédiées aux réseaux de neurones. Les réseaux de neurones artificiels sont un type de modèle d’apprentissage automatique dont la représentation est un réseau inspiré vaguement des neurones humains.

Nous avons vu comment la rétro-propagation de Hinton est utilisée pour entraîner les réseaux de neurones en utilisant le gradient de l’erreur pour mesurer à quel point chaque neurone est responsable de l’erreur. 

Cette approche a néanmoins un point faible, le problème du gradient disparaissant. Nous avons abordé les différents types d'initialisation ainsi que les différentes fonctions d'activation qui permettent de pallier ce problème. Nous avons également traité différents optimiseurs tels que adagrad, nesterov accelerated gradient ou ADAM. 

Nous avons ensuite vu différentes architectures de réseaux de neurones telles que les auto encodeurs, les réseaux de neurones convolutifs et les réseaux de neurones récurrents.

Le cours s’est terminé en abordant les thèmes des SVM et enfin du partitionnement, une technique d’apprentissage supervisé.
Pour les étudiants de la MIGD visant un profil orienté ML engineer, ou Data scientist oriente ML, ce cours fut probablement le plus important de notre formation. Nous sommes reconnaissant qu’il ait été traité par un prof compétent et de façon rigoureuse et profonde.
