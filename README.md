# Analyse des interactions entre personnages d'un livre

Ce projet permet d'extraire les personnages d'un livre en format PDF, d'analyser leurs interactions à travers le texte et de visualiser ces relations sous forme de graphe. L'analyse est réalisée à l'aide de SpaCy pour l'extraction des entités et de NetworkX pour la création et la visualisation du graphe.

## Prérequis

Avant de pouvoir exécuter ce projet, vous devez installer les bibliothèques suivantes :

- `spacy` : pour le traitement de texte et l'extraction des entités nommées (NER).
- `networkx` : pour la création du graphe des interactions.
- `matplotlib` : pour la visualisation du graphe.
- `pdfplumber` : pour extraire le texte depuis un fichier PDF.
