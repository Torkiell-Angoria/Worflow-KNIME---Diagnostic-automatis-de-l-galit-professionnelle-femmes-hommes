#  Workflow KNIME - Diagnostic de l'Égalité Professionnelle Femmes / Hommes

##  Objectifs du projet

Chaque année avant le 1er mars, les entreprises de plus de 50 salariés doivent publier leur index de l'égalité professionnelle entre les femmes et les hommes, comme l'exige la loi française.

L’objectif de ce projet est de concevoir un workflow automatisé sous KNIME permettant de :

- Réaliser un diagnostic de l’égalité professionnelle à partir des données du Système d’Information des Ressources Humaines (SIRH),
- Visualiser les indicateurs clés sous forme de graphiques,
- Exporter un fichier .csv prêt à être utilisé pour des analyses ultérieures dans Tableau Software,
- Respecter le RGPD en anonymisant les données sensibles,
- Fournir un score d’égalité femmes-hommes et proposer des recommandations d'amélioration.

Ce diagnostic permet de renforcer la politique d’égalité et d'attirer davantage de talents.

##  Outils utilisés

Outil	Utilisation principale
KNIME	Automatisation du diagnostic, transformation de données, création de graphiques
Excel / CSV	Fichiers source issus du SIRH
Documentation officielle	Pour identifier les indicateurs à suivre (guide ministère du travail)

##  Présentation du Worflow

Le workflow KNIME se décompose en plusieurs étapes :
1-2. Chargement et nettoyage des données
    Suppression des doublons, valeurs manquantes, erreurs
    Anonymisation des noms et identifiants pour respecter le RGPD

3. Préparation des variables
    Création de variables catégorielles.

4. Calcul des indicateurs
    Choix des indicateurs:
        Écart de rémunération femmes-hommes
        Écart de taux d’augmentation
        Écart de taux de promotion
        Pourcentage de salariées revenues de congé maternité ayant eu une augmentation
         Répartition femmes-hommes parmi les 10 plus hautes rémunérations

5. Visualisation 
    Génération de graphiques illustrant les écarts et répartitions
    Création de dashboard automatisé

6. & Export des résultats
     Génération d’un fichier .csv contenant toutes les métriques prêtes à être utilisées dans Tableau

##  Résultats obtenus
 1. Un fichier CSV complet prêt à être réutilisé

 2. Un dashboard avec  :
    - des graphiques
    -Score égalité femmes-hommes calculé selon la méthode officielle
    -Recommandations stratégiques proposées pour améliorer le score l’année suivante


## Conclusion
Ce projet d’automatisation du dashboard avec KNIME a été très enrichissant et plaisant à réaliser. J’ai pu exploiter pleinement les capacités d’ETL de KNIME pour préparer, nettoyer et agréger les données de manière fluide grâce à son interface intuitive basée sur des noeuds visuels.
KNIME s’est révélé très adapté pour ce type de projet, offrant une automatisation efficace et une bonne facilité d’utilisation. Cependant, il peut montrer des limites sur des volumes de données très importants, ce qui peut ralentir les performances. Pour de très gros jeux de données, d’autres solutions pourraient être envisagées.


    





