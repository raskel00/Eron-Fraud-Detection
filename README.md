### Présentation du Projet

En 2000, Enron était l'une des plus grandes entreprises des États-Unis. En 2002, l'entreprise a fait faillite en raison d'une fraude généralisée au sein de ses activités. Dans l'enquête fédérale qui a suivi, une quantité importante d'informations généralement confidentielles a été rendue publique, comprenant notamment des dizaines de milliers de courriels et des données financières détaillées concernant les hauts dirigeants.

Pour ce projet, j'ai construit des modèles prédictifs en utilisant les modules scikit-learn, NumPy et pandas en Python. L'objectif était d'identifier les personnes d'intérêt (POI), qui sont des individus ayant été inculpés, ayant conclu un règlement ou un accord de plaidoyer avec le gouvernement, ou ayant témoigné en échange d'une immunité de poursuites. Le Corpus Enron a été utilisé comme base de données pour les fonctionnalités de prédiction.

### Étapes du Projet

#### Étape 1 : Analyse des Données
- **Nombre de personnes dans l'ensemble de données Enron** : 143
- **Nombre de POI (Personnes d'Intérêt)** : 16

#### Étape 2 : Enquête sur les Valeurs Aberrantes
Identification et traitement des valeurs aberrantes dans les données financières.

#### Étape 3 : Création de Nouvelles Fonctionnalités
- Création de nouvelles caractéristiques financières telles que `salary_of_total_payments` et `salary_of_total_stock_value`.
- Création de la colonne `poi_ratio` pour le pourcentage des messages liés aux POI.
- Développement de fonctionnalités pour mesurer les connexions de courriels entre POI.

#### Étape 4 : Sélection d'Algorithmes et Réglage des Paramètres
- Comparaison de plusieurs algorithmes de classification.
- Sélection des caractéristiques avec l'analyse ANOVA F-test.
- Création de pipelines utilisant PCA, SelectKBest et SVM.
- Optimisation des paramètres pour RandomForest et SVM avec validation croisée.

### Résultats

Le modèle de prédiction a permis d'identifier efficacement les POI, démontrant des connexions significatives entre les e-mails et les transactions financières des personnes impliquées dans la fraude.

Découvrez plus en détails ce projet et comment ces outils peuvent transformer l'analyse de données dans la lutte contre la fraude ! #DataScience #MachineLearning #Enron #FraudDetection #Python
