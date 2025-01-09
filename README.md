# MusicAnalysisPython
Ce projet vise à analyser les tendances musicales en utilisant des bibliothèques Python pour manipuler, visualiser et modéliser des données. Il repose sur un dataset contenant des informations sur des chansons telles que le titre, l'artiste, le genre, l'année de sortie et le nombre d'écoutes. L'objectif principal est d'extraire des insights utiles, comme les genres dominants ou les années marquantes, et de construire un modèle prédictif pour estimer la popularité des chansons.

# requierements
Un fichier requierement est mise à disposition pour ilustrer les dépendanaces utiliser pour ce projet
Vous pouvez les installer grace à la commande: !pip install requirements.txt

# arborescence
Ce projet est composé d'un dossier "data1" où est stoqué deux fichier .csv qu'on va étuliser durant tout le projet. Le csv Spotify-2000 est le dataset brute et le cleaned_spotify_data.csv est la version néttoyé avec que des champs important qu'on utilisera durant tout le projet.
Le fichier texte requierements contient toutes les dépendanaces de ce projet.
Deux fichier ipynb sont mis à disposition pour regrouper les differents code avec des commentaire explicatives dans un sens cronologique selon les consignes. Impossible de se perdre avec ça.

# Évaluation du modèle
## Résultats
- **R²** :le modèle explique 78% de la variance des données
- **MAE** :le modèle fait une erreur moyenne de 10,000 écoutes par chanson

## Ce que je penses de ce modèle
Le modèle est globalement satisfaisant, mais il peut être amélioré. Un R² de 0.78 montre que le modèle capture bien la relation entre les variables explicatives et le nombre d'écoutes, mais il reste une marge d'erreur significative. 
Les axes d'amélioration possibles incluent :
1. Ajouter d'autres variables explicatives comme la durée de la chanson, le pays, ou même les paroles.
2. Tester des modèles plus complexes comme la régression polynomiale ou les arbres de décision.
