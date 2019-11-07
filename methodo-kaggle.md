# Methodologie Kaggle pour un problème de classification

## Compétition Kaggle

- inscription sur une compétition Kaggle
- récupération des fichiers
- Analyse des données  fournies par Kaggle
- Comprendre les résultats attendus par Kaggle
- Regarder comment sont scorés les résultats

## BigML

- Utilisation de la librairie Pandas pour manipuler les ficheirs test et train
- Création de Dataframes pandas
- Nettoyage des données:
  - gestion des NAN
  - gestion des vides
- Avec de l'API de BigML:
  - créations des sources
  - créations des datasets
  - split du train_full en train et val
  - en boucle tant que ca n'est pas satisfaisant:
    - entrainement d'un modèle sur le train
    - batch prediction sur val
    - évaluation de la performance et des erreurs:
      - analyse des erreurs (i.e. sortir les 100 plus grandes)
      - matrice de confusion
      - matrice de coûts
      - Calcul de l'AUC
    - création des courbes d'apprentissage:
      - train sur train
      - et train sur val
    - modifications sur les features
- essais sur différents types de modèles
- comparaison entre les courbes d'apprentissage des différents modèles

## Envoi des résultats

- préparer avec Pandas les fichiers pour l'envoi Kaggle
- utilisaiton de l'API Kaggle pour soumission des fichiers
