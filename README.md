# Projet Dataviz : Football Transfers

## Objectif
Ce projet de datavizualisation se concentre sur la visualisation des transferts de football, en mettant en lumière les transferts de joueurs entre les clubs.
L'objectif est de fournir des informations visuelles intuitives sur les mouvements de joueurs, les clubs impliqués et l'évolution des coûts des transferts au fil des saisons.

## Auteurs
Groupe 8 :
- Siham KIARED
- Kévin TANG
- Yann VINCENT

M2 Data Science
2023-2024
Université Claude Bernard Lyon 1

Enseignant référant : Aurélien TABARD

![image](https://github.com/ks-tang/DataViz/assets/102915124/f557ff87-03a7-4285-90a8-56a764846b90)

## Fonctionnalités principales
- **Carte interactive :** Visualisez le parcours des joueurs et les transferts de joueurs entre les clubs sur une carte du monde.
- **Graphiques dynamiques :** Explorez l'évolution des prix des transferts au fil des saisons.
- **Informations détaillées :** Obtenez des détails sur les transferts, les clubs et les joueurs sélectionnés.

## Exécution du projet
Projet visible via ce lien : https://ks-tang.github.io/DataViz_FootballTransfers/

## Utilisation
1. Choisissez un joueur ou un club dans les listes déroulantes.
2. Explorez les transferts, les graphiques et les informations détaillées.
3. Utilisez le slider pour sélectionner une saison spécifique.

## Difficultés rencontrées

Pour pouvoir placer les clubs sur la carte, nous avons eu besoin de trois jeux de données. Un contenant les noms des clubs et ceux des stades, un autre avec les noms des villes et leurs coordonnées de localisation, et un dernier avec les transferts des joueurs ainsi que les noms des clubs associés. Nous avons donc dû relier ces trois jeux de données en utilisant plusieurs fonctions dans le code. Nous avons également rencontré des problèmes pour harmoniser les données. En effet, la langue utilisée dans chaque jeu de données n'était pas la même, et les noms des clubs ne correspondaient pas non plus. Par exemple, pour les villes, il y avait une différence entre Neapol et Naples, ou entre SSC Napoli et Napoli pour les clubs. Nous avons donc dû modifier manuellement les fichiers CSV afin de pouvoir relier les jeux de données. Nous avons également dû gérer les cas de doublons. Par exemple, il existe de nombreuses villes dans le monde portant le nom de Barcelone. Ainsi, tous nos transferts vers le FC Barcelone étaient dirigés vers l'Amérique latine sur la carte. Tout ce travail nous a beaucoup ralenti et nous a empêchés de consacrer davantage de temps aux autres fonctionnalités.

