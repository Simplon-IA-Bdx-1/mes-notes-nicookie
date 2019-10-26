# Notes Machine Learning Yearling

## Precision vs Recall

- Precision:

  - Le nombre de vrais positifs sur l'ensemble des positifs prédits
  - Precision = TP / (TP + FP)

- Recall:

  - Le nombre de vrais positifs sur le nombre total de positifs dans le set
  - Recall = TP / (TP + FN)

- F1:

  - indice de l'efficassité d'un modèle basé sur Precision et recall:
  - F1 = 2 / ((1/Precision) + (1/Recall))

## Optimisation

- choisir un crière fixe et faire varier l'autre
- étendu: N critères, N-1 fixes et 1 varie en fonction de ces critères fixes
