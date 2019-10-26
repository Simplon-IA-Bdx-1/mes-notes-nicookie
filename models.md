# Les types de modèles

## Baseline

Base de performance humaine sur laquelle on peut s'appuyer pour évaluer la performance du mmodèle.

### classification

- random
- mode classifier -> donne tout le temps la classe négative; comparer l'accuracy.

### Régression

- mean regressor -> Calcul et comparaison de MAPE

## Random classifier

Output aléatoire

## Mode classifer

Renvoie toujours le même output

- 0% de **Faux Négatifs** *FN*
- % de **Faux positifs** *FP* en fonction de la répartition des classes.

## Mean regressor

S'appuie sur la valeur moyenne des outputs sans s'occuper des features

## Data leak

Les données d'apprentissage donnent des infos pour les données de test. Du coup le modèle **apprend la solution mais pour une mauvaise raison** -> il ne peut donc pas **généraliser** son apprentissage à d'autres données.

## Split entre training data et test data

En fonction du nombre de données, on va adapter la répartition du split. Par exemple avec des millions de données on pourra faire du 95% **train** et 5% **test** alors qu'avec peu de données on fera 50/50...
La nature du problème *(contexte)* peut faire adapter aussi le split.

### split linéaire

Dans certains cas de figure, on s'assure que dans le **train** et dans le **val** on est la même répartiton que dans le **train-full**

## Analyse Modèle

## Globalité

- feature importance (quelles features ont le plus pesé dans la prédiction du modèle)
- PDP

## Erreurs et prédiction sur val

- MAPE
- Matrice confusion
- Prédiction individuelle : on regarde celles qui ont le plus gros taux d'erreur et on cherche pourquoi.
  - on classe la colone par taux d'erreur décroissant
