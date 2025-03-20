# 🚀 Lunar Lander AI - Apprentissage par Renforcement

## 📌 Description
Ce projet implémente une **intelligence artificielle (IA) capable de piloter un vaisseau spatial** afin d'effectuer un atterrissage contrôlé dans l’environnement **Lunar Lander** d’OpenAI Gym.

L’objectif est de concevoir un **agent intelligent** qui apprend à ajuster la poussée et l’orientation du vaisseau pour maximiser ses chances d’atterrissage en toute sécurité, tout en minimisant sa consommation de carburant.

## 🎯 Objectifs
- Entraîner un agent IA avec des **algorithmes d’apprentissage par renforcement** (Reinforcement Learning).
- Optimiser **les décisions prises** pour effectuer un **atterrissage en douceur**.
- Tester **différentes méthodes d’apprentissage** afin d’améliorer la performance de l’IA.

## 🏗️ Technologies utilisées
- **Python** 🐍
- **Gymnasium** (Simulation de l’environnement Lunar Lander, remplaçant Gym OpenAI)
- **NumPy** (Manipulation des données et calculs matriciels)
- **Matplotlib** (Visualisation des performances)
- **PIL (Python Imaging Library)** (Gestion des images et des vidéos)
- **IPython Display** (Affichage interactif des résultats)
- **Time** (Gestion des délais et timing d’exécution)
- **Swig** (Outil pour interfacer C/C++ avec Python, nécessaire pour certaines dépendances)

## ⚙️ Algorithmes utilisés
L’IA apprend en interagissant avec l’environnement et en recevant des **récompenses** selon ses actions. Nous utilisons les algorithmes suivants :

1. **Q-learning** : Apprentissage tabulaire basé sur des valeurs d'état-action, amélioré avec l’algorithme de **Tile Coding (Tiling)** pour mieux représenter un espace d’états continus.

## 📊 Résultats attendus
L'agent doit être capable de :
✅ **Maîtriser la poussée et l'orientation** du vaisseau.
✅ **Gérer efficacement son carburant** pour éviter d’être à court.
✅ **Effectuer un atterrissage précis et en douceur** en maximisant les récompenses.
