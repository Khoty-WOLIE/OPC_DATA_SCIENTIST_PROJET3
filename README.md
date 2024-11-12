# OPC_DATA_SCIENTIST_PROJET3
Préparez des données pour un organisme de santé publique


# Préparation et Analyse des Données Open Food Facts - Projet Santé Publique France



## Contexte

Je suis missionné pour travailler sur un projet pour **Santé publique France** visant à améliorer la qualité des données de la base **Open Food Facts**, une base de données open source répertoriant la qualité nutritionnelle des produits alimentaires. Cette base est largement utilisée par des particuliers et des organisations pour évaluer les qualités nutritionnelles des produits.

L'objectif est de développer un système de suggestion automatique pour faciliter la complétion des champs dans la base de données et améliorer la qualité des informations saisies. Avant de développer ce système, je dois me concentrer sur l’exploration et le nettoyage des données pour déterminer la faisabilité de cette approche.

## Objectifs du Projet

1. **Nettoyage des Données** : Explorer et nettoyer les données Open Food Facts pour identifier les valeurs manquantes, aberrantes, et les doublons. L'objectif est de préparer les données pour une analyse future et de poser les bases pour un système de suggestion automatique.
   
2. **Analyse Univariée et Bivariée** : Réaliser des analyses univariées et bivariées pour mieux comprendre les distributions des variables et les relations entre elles.

3. **Automatisation du Nettoyage** : Automatiser le processus de nettoyage pour s'assurer que le programme fonctionne même si la base de données évolue ou que de nouvelles entrées sont ajoutées.

4. **Respect du RGPD** : Examiner en quoi ce projet respecte les principes du RGPD et expliquer ces aspects dans un rapport pour publication sur le site d’Open Food Facts.

## Étapes du Projet

### Étape 1 : Nettoyage des Données

- **Objectif** : Nettoyer les données en identifiant et en traitant les valeurs manquantes et les doublons, et en repérant les variables pertinentes pour la suite de l'analyse.
- **Détails** :
  - Identifier les variables pertinentes pour l'analyse.
  - Supprimer les doublons et les lignes n'ayant pas de valeurs pertinentes pour la cible.
  - Créer un processus automatisé pour filtrer les variables et produits (lignes) à utiliser.
  - Supprimer les valeurs manquantes dans les variables cibles choisies et organiser les données de manière structurée.
- **Livrable** : Un notebook contenant le processus de nettoyage, automatisé à l’aide de **pandas**.

### Étape 2 : Analyse des Valeurs Aberrantes

- **Objectif** : Identifier et traiter les valeurs aberrantes qui pourraient fausser les résultats des analyses.
- **Détails** :
  - Utiliser des visualisations telles que des **boxplots** ou des **histogrammes** pour détecter les valeurs aberrantes.
  - Traiter les valeurs aberrantes à l’aide de méthodes comme la suppression, le remplacement par la médiane, ou des valeurs logiques en fonction du contexte.
  - Automatiser ces opérations pour assurer la répétabilité du processus.
- **Livrable** : Un notebook contenant les étapes de détection et de traitement des valeurs aberrantes.

### Étape 3 : Traitement des Valeurs Manquantes

- **Objectif** : Gérer les valeurs manquantes dans les variables cibles en utilisant des méthodes d'imputation adaptées.
- **Détails** :
  - Vérifier si les valeurs manquantes sont aléatoires ou s'il existe une cause systématique.
  - Utiliser des méthodes d'imputation (médiane, moyenne, ou autres) adaptées pour chaque type de variable.
  - Mettre en œuvre un processus qui respecte l'intégrité des données sans introduire de biais dans l'analyse.
- **Livrable** : Un notebook détaillant le processus de traitement des valeurs manquantes.

### Étape 4 : Analyse Univariée et Bivariée

- **Objectif** : Effectuer une analyse univariée pour comprendre la distribution des variables et une analyse bivariée pour explorer les relations entre elles.
- **Détails** :
  - Utiliser des **histogrammes**, **boxplots**, et **nuages de points** pour visualiser les distributions des variables et leurs relations.
  - Calculer des statistiques descriptives pour résumer les tendances des variables (moyenne, médiane, écart-type).
  - Analyser les corrélations entre les différentes variables pour identifier les relations importantes.
- **Livrable** : Un notebook contenant des visualisations et des statistiques pour chaque analyse.

### Étape 5 : Respect du RGPD

- **Objectif** : Préparer un rapport expliquant en quoi le projet respecte les principes du RGPD.
- **Détails** :
  - Identifier les 5 grands principes du RGPD et expliquer leur application dans le projet.
  - Préparer une explication à inclure sur le site Open Food Facts pour répondre aux questions liées à la conformité avec le RGPD.
- **Livrable** : Un rapport détaillant comment le projet respecte les 5 grands principes du RGPD.

### Étape 6 : Présentation Finale et Conclusion

- **Objectif** : Rédiger un rapport d’exploration et une présentation pour expliquer la méthodologie et les résultats de l’analyse à des non-experts.
- **Détails** :
  - Préparer une présentation vulgarisée des résultats de l’analyse.
  - Rédiger un rapport final concluant sur la faisabilité de l’application de suggestion automatique et la qualité des données explorées.
- **Livrable** : Une présentation PowerPoint claire et un rapport synthétique expliquant les résultats de l’analyse.

## Détails Techniques

- **Fichiers** :
  - `Open Food Facts` : Jeu de données Open Food Facts disponible sur le site officiel.
  - **Notebook de Nettoyage des Données** : Contient les étapes de nettoyage, automatisées à l'aide de **pandas** et **numpy**.
  - **Notebook d’Analyse** : Contient les analyses univariées, bivariées et multivariées.

- **Outils Utilisés** :
  - **Python**, avec les bibliothèques **pandas**, **numpy**, **matplotlib**, **seaborn** pour le nettoyage des données et la visualisation.
  - **Missigno** pour la gestion des valeurs manquantes.

- **Compétences Utilisées** :
  - Nettoyage des données et gestion des valeurs manquantes.
  - Analyse univariée, bivariée, et multivariée.
  - Automatisation des processus de traitement des données.
  - Communication des résultats dans un langage accessible aux non-experts.

## Résumé

Ce projet me permet de contribuer à l'amélioration de la base de données **Open Food Facts** en nettoyant les données et en développant un système de suggestion automatique. L’objectif final est de rendre la saisie des informations plus efficace tout en garantissant la qualité des données et leur conformité avec le RGPD. Les résultats de cette mission seront présentés à **Santé publique France** pour déterminer la faisabilité de l’application envisagée.
