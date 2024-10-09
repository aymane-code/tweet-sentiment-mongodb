# Projet d'Analyse de Sentiment des Tweets avec MongoDB et Python

Ce projet utilise **MongoDB** pour stocker des tweets et **Python** pour effectuer une analyse de sentiment. Avec des bibliothèques comme **NLTK** et **TextBlob**, le projet propose différentes méthodes pour évaluer les sentiments des tweets, permettant ainsi une comparaison entre les approches.

## Fonctionnalités

### Connexion et Gestion de la Base de Données MongoDB
- Utilisation de `pymongo` pour se connecter à MongoDB, stocker et récupérer les tweets.
- Filtrage et gestion des données de tweets pour un traitement optimal.

### Prétraitement des Tweets
- Anonymisation des mentions d’utilisateurs.
- Utilisation de `pandas` pour manipuler les données et les transformer en DataFrames.

### Analyse de Sentiment
- **NLTK** : Utilisation de l’analyseur de sentiment VADER pour classer les tweets en positif, négatif ou neutre.
- **TextBlob** : Calcul des sentiments en fonction de la polarité et assignation des labels correspondants.

## Prérequis
- Python 3.7+
- MongoDB installé et en cours d'exécution
- Bibliothèques nécessaires : `pandas`, `pymongo`, `nltk`, `textblob`

### Installation des dépendances :
```bash
pip install pandas pymongo nltk textblob
