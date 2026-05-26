# youtube-llm
## objectif du projet

STAGE ──────────────────────────────────────────
│  Notebook 1   EDA benchmark 26 créateurs
│  Notebook 2   Modélisation + comparaison
│  Étape 3      Interface marché (26 créateurs)
│  Étapes 4-6   Notebook BIMO + interface privée

APRÈS ──────────────────────────────────────────
│  YouTube Data API intégrée
│  Channel ID → scraping → prédiction
│  Outil générique marché marocain
│  Potentiel SaaS / offre agence

Étapes 1-3 — Produit "Marché"

Notebook EDA sur les 26 créateurs benchmark
Modèle entraîné sur ce dataset général
Interface commercialisable : outil d'analyse du marché YouTube marocain
Cible : agences de comm, marques, youtubeurs qui veulent se positionner
La valeur : "sur ce marché, si tu publies ce type de contenu, voilà le potentiel"

Étapes 4-6 — Produit "BIMO"

Notebook EDA spécifique à la chaîne BIMO
Modèle entraîné sur la data BIMO uniquement
Interface privée pour BIMO : outil personnalisé pour ses décisions éditoriales
La valeur : "toi BIMO, avec ton audience, si tu publies ça jeudi à 20h..."

## squelette du projet
Youtbe-LLM
|
L____annexe
|
L____data
    L____ benchmarkcsv
    L____ scrapping
    L____ statsbimo
|
L____models
|
L____notebooks
|
L README.md