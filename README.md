# Contenu du projet
1. Identification de profils (recherche_attaquant.ipynb)
Ce notebook simule un dataset de 500 attaquants évoluant dans des championnats de "Tier 2" (Eredivisie, Belgique, Autriche, etc.).

Critères de sélection : Moins de 24 ans, volume de tirs élevé et activité au pressing.

Méthodologie : Normalisation des données avec StandardScaler et calcul d'un score de similarité pondéré.

Résultat : Identification d'une cible prioritaire nommée "Player_42" et visualisation de son profil via un graphique radar (polar chart).

2. Analyse comparative (comparaison.ipynb)
Ce notebook compare la cible identifiée (Player_42) avec l'attaquant sortant du club (Striker_Outgoing).

Indicateurs clés : Non-Penalty xG/90, Goals/90, Shots/90 et Pressures.

Visualisation : Utilisation de graphiques à barres comparatifs pour valider que le remplaçant offre des fondamentaux statistiques supérieurs (notamment sur le pressing et les xG), malgré une légère sous-performance actuelle en buts réels.
