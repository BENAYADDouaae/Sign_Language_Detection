# Sign Language Detection

**Deep Learning project for ASL sign language detection using Convolutional Neural Networks (CNN).**

---

## Description du projet

Ce projet met en œuvre un modèle de **Deep Learning** dédié à la **reconnaissance des signes du langage des signes américain (ASL)** à partir d’images.  
Il a pour objectif de **favoriser l’inclusion des personnes sourdes et malentendantes** en facilitant la **traduction automatique des gestes en texte** lisible par tous.

---

## Contenu du projet

Le projet repose sur un **notebook Jupyter unique (.ipynb)** qui regroupe l’ensemble des étapes suivantes :

- **Préparation et nettoyage du dataset**  
- **Conception et entraînement du modèle CNN**  
- **Évaluation des performances** à l’aide de métriques classiques  
- **Visualisation des résultats** et interprétation du modèle  

---
## Objectifs
- Construire un modèle capable de reconnaître les lettres A–Z et chiffres 0–9 de la langue des signes.
- Comparer les performances entre :
   - un réseau de neurones convolutionnel (CNN) personnalisé,
   - et un modèle pré-entraîné ResNet50 (transfer learning).
- Obtenir une précision élevée tout en maintenant une exécution rapide et optimisée.

---
## Technologies utilisées

- Python 3.x  
- TensorFlow / Keras  
- NumPy / Pandas  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## Exécution du projet

Le projet est disponible sous forme d’un **notebook Jupyter interactif** hébergé sur **Kaggle**.  
Vous pouvez l’exécuter directement en ligne sans aucune installation locale.

➡️ [**Cliquez ici pour ouvrir et exécuter le projet sur Kaggle**](https://www.kaggle.com/code/benayaddouaae/projet-sign-language/edit)

---

## Jeu de données utilisé

Les données proviennent du dataset **American Sign Language (ASL)** disponible sur [Lien](https://www.kaggle.com/datasets/ayuraj/asl-dataset) .  
Elles comprennent :
- Les **26 lettres** de l’alphabet (A–Z)
- Les **10 chiffres** (0–9)

La répartition des données est la suivante :
- 80 % : Entraînement  
- 10 % : Validation  
- 10 % : Test  
