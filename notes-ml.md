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

## Learning curves

- établir la courbe d'erreur sur le traning set et le dev set en fonction de leur taille permet d'évaluer la qualité du modèle
- on se base sur la performace désirée:
  - si la courbe du training set est éloignée de l'opti => biais
  - si la courbe du dev est éloignée du training => variance
- la lecture de la jonction des deux courbes ensemble permet de voir vers où le modèle, à son meilleur va tendre.s


comprehension de liste!"!!!