# Ai-TP1
# Partie 1 — Préparation de l’environnement
## 1 Quelle est la commande pour installer une bibliothèque avec pip ?

- pip install nom_de_la_bibliotheque

## 2 Différence entre nltk et spaCy :

- NLTK = ancienne bibliothèque, utile pour l’apprentissage et la recherche (plus bas niveau, plus lente).
- spaCy = plus moderne et optimisée, orientée vers l’industrie (rapide, meilleure précision).

# Partie 2 — Nettoyage du texte
## Pourquoi mettre le texte en minuscules ?

- Pour éviter les doublons.
- L’ordinateur doit les considérer comme le même mot.

## Exemple avant/après :

- Texte original : Hello World! NLP is FUN 😄, isn't it?
- Texte nettoyé : hello world nlp is fun 😄 isnt it

# Partie 3 — Tokenisation et Stopwords

## Que représentent les stopwords ?
- Ce sont des mots très fréquents sans valeur sémantique ( Exemple : “the”, “a”, “in”, “is”...) .

## Quelle proportion du texte est supprimée ?
- Souvent 30 à 60 % selon le texte.

# Partie 4 — Lemmatisation

## Différence entre stemming et lemmatisation :

- Stemming : coupe le mot (approche brute) → “playing” → “play”, “studies” → “studi”

- Lemmatisation : retourne la forme correcte du mot (“studies” → “study”) en tenant compte de la grammaire.

## Pourquoi cette étape est importante ?
- Elle regroupe les formes d’un même mot, donc réduit la complexité du vocabulaire et améliore la qualité de l’analyse sémantique.














