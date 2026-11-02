# Projet 4 : Étude de santé publique sur la sous-nutrition (Python)

### Contexte
La **FAO** veut comprendre les mécanismes de la sous-nutrition mondiale pour orienter ses actions. En 2017, 9,8 % de la population mondiale, près de 784 millions de personnes, était en situation de sous-nutrition.

**Mon objectif :** répondre à une question en apparence paradoxale : pourquoi la faim persiste-t-elle alors que la production alimentaire mondiale est abondante ? Chaque chiffre présenté devait pouvoir être justifié par le code.

### Missions réalisées
* **Préparation des données :** assemblage de 4 fichiers FAO par jointures internes, pour ne garder que les pays disposant de toutes les données nécessaires.
* **Calcul central :** calories disponibles pour l'alimentation humaine rapportées au besoin minimal, pour mesurer la part de la population mondiale qui pourrait être nourrie.
* **Analyse des pertes :** pertes après récolte et part des céréales destinée à l'alimentation animale, jusqu'à des cas précis comme le manioc en Thaïlande, dont 80 % de la production part à l'export.
* **Disparités :** comparaison des pays selon leur disponibilité calorique par habitant.

### Résultats
* La production mondiale permettrait théoriquement de nourrir **111 %** de la population : la quantité n'est pas le facteur limitant, la distribution l'est.
* **13 %** de la production mondiale de céréales part vers l'alimentation animale.
* Trois recommandations : réduire les pertes post-récolte, réévaluer la part des céréales allouée aux animaux dans les régions en tension, limiter les dépendances commerciales excessives.

### Compétences & Outils
* **Langage :** Python
* **Librairies :** Pandas, NumPy, Matplotlib, Seaborn
* **Techniques :** jointures, filtres conditionnels, indicateurs démographiques et sanitaires

### Contenu du dépôt
* `notebooks/` : le notebook d'analyse
* `data-raw/` : les 4 fichiers FAO
* `reports/` : le notebook en PDF et la présentation
* `images/` : captures d'écran

<img src="images/Capture d'écran 2025-10-01 115855.png" width="500px"><img src="images/Capture d'écran 2025-10-01 115846.png" width="500px">
<img src="images/Capture d'écran 2025-09-24 122648.png" width="500px"><img src="images/Capture d'écran 2025-09-18 104721.png" width="500px">

---
📂 Dossier complet sur mon portfolio : [remydaura.github.io/p4.html](https://remydaura.github.io/p4.html)

*Ce projet fait partie de la formation Data Analyst d'OpenClassrooms.*
