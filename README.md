# Projet NLP de Détection de Catastrophes sur Twitter
## Description
Ce projet utilise des techniques de Machine Learning et de traitement du langage naturel (NLP) pour analyser des milliers de tweets collectés aux États-Unis. L'objectif est de prédire si un tweet annonce ou commente une catastrophe (disaster) au moment où il a été publié.

## Données
### Dataset principal
Le dataset principal est nommé socialmedia-disaster-tweets-DFE.csv. Il contient des milliers de tweets collectés par des agences.

### Train et Test Sets
train.csv : Utilisé pour entraîner le modèle. Il contient une colonne target où :

1 indique que le tweet annonce une catastrophe.
0 indique que le tweet ne parle pas de catastrophe.
test.csv : Utilisé pour tester le modèle. Il ne contient pas la colonne target.
