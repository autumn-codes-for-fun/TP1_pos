# TP1_pos
🧠 TP : Étiquetage morpho-syntaxique (Part-of-Speech Tagging)
🎯 Objectif du TP

L’objectif de ce travail pratique est d’explorer le fonctionnement d’un étiqueteur morpho-syntaxique (PoS tagger) à travers différentes étapes :

préparation et chargement d’un corpus (ici Sequoia – Universal Dependencies),

extraction et transformation des données linguistiques,

comparaison entre les étiquettes prédites et les étiquettes de référence (gold),

calcul de mesures de performance (micro, macro, et globale).

📚 Données utilisées

Le corpus utilisé est Sequoia, issu des Universal Dependencies (UD) :
👉 UD_French-Sequoia
Installation:
ouvrir ou copier coller le contenu du jupyter dans un IDE python

Execution:

## 🚀 Exécuter le notebook en ligne

Clique sur le badge ci-dessous pour ouvrir le notebook directement dans Google Colab :

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/autumn-codes-for-fun/TP1_pos/blob/main/TP1_POSTAG.ipynb)

---
🧮 Évaluation du tagger

Plusieurs fonctions ont été développées pour mesurer la performance :

1. Vérification phrase par phrase

Compare une liste de PoS prédits à un dictionnaire gold standard :
1. Vérification phrase par phrase

Compare une liste de PoS prédits à un dictionnaire gold standard :
2. Micro accuracy

Somme du nombre total de PoS correctement étiquetés :
3. Macro accuracy

Moyenne de l’exactitude par catégorie grammaticale :
4. Évaluation globale du tagger
5.📊 Résultats obtenus
🧰 Librairies utilisées

json : lecture et écriture du corpus

conllu : conversion du format UD

spacy (optionnel) : test avec un modèle PoS automatique fr_core_news_sm
