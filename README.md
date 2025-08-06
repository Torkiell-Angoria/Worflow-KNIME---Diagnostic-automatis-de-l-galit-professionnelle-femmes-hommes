# 🟣 Workflow KNIME - Diagnostic de l'Égalité Professionnelle Femmes / Hommes
## 🎯 Objectif du projet

Chaque année avant le 1er mars, les entreprises de plus de 50 salariés doivent publier leur index de l'égalité professionnelle entre les femmes et les hommes, comme l'exige la loi française.

L’objectif de ce projet est de concevoir un workflow automatisé sous KNIME permettant de :

    Réaliser un diagnostic de l’égalité professionnelle à partir des données du Système d’Information des Ressources Humaines (SIRH),
    Visualiser les indicateurs clés sous forme de graphiques,
    Exporter un fichier .csv prêt à être utilisé pour des analyses ultérieures dans Tableau Software,
    Respecter le RGPD en anonymisant les données sensibles,
    Fournir un score d’égalité femmes-hommes et proposer des recommandations d'amélioration.

Ce diagnostic permet de renforcer notre politique d’égalité, d’améliorer notre marque employeur, et d'attirer davantage de talents dans un contexte de forte croissance.
## 🧰 Outils utilisés
Outil	Utilisation principale
KNIME	Automatisation du diagnostic, transformation de données, création de graphiques
Tableau Software	Visualisation avancée (futur usage à partir du fichier .csv)
Excel / CSV	Fichiers source issus du SIRH
Documentation officielle	Pour identifier les indicateurs à suivre (guide ministère du travail)

## 🔍 Présentation du Worflow

Le workflow KNIME se décompose en plusieurs étapes :

    Chargement et nettoyage des données

        Suppression des doublons, valeurs manquantes, erreurs

        Anonymisation des noms et identifiants pour respecter le RGPD

    Préparation des variables

        Création de variables catégorielles : sexe, type de contrat, ancienneté, rémunération, promotion, etc.

    Calcul des indicateurs

        Choix de 5 indicateurs minimum recommandés :

            Écart de rémunération femmes-hommes

            Écart de taux d’augmentation

            Écart de taux de promotion

            Pourcentage de salariées revenues de congé maternité ayant eu une augmentation

            Répartition femmes-hommes parmi les 10 plus hautes rémunérations

    Visualisation

        Génération de graphiques illustrant les écarts et répartitions

        Export automatique des visuels en .png

    Export des résultats

        Génération d’un fichier .csv contenant toutes les métriques prêtes à être utilisées dans Tableau

## 📊 Résultats obtenus

    ✅ Fichier CSV complet avec les indicateurs clés

    ✅ Graphiques clairs pour la présentation en plénière

    ✅ Score égalité femmes-hommes calculé selon la méthode officielle

    ✅ Recommandations stratégiques proposées pour améliorer le score l’année suivante





