# Analyse des performance d'un site web, comparaison par periodes
Analyse de l’évolution des performances d’un site web (trafic, profil utilisateur, URL et ciblage) sur deux périodes afin d’identifier les variations et les axes d’optimisation.

## Contexte :

Ce projet a été réalisé dans le cadre d’un stage en tant que data analyst.
Il porte sur l’analyse des performances d’un site web à partir de données extraites de Matomo (anciennement Piwik).
Les données ont été anonymisées et/ou simulées pour des raisons de confidentialité.

L’analyse compare deux périodes distinctes afin d’évaluer l’évolution de l’activité et des comportements :
- Baseline, les données correspondent aux 3 premiers mois de l'existance du site pour avoir une base stable de ce qu'était le site à ses débuts.
- Postbaseline, les données correspondent aux mois suivants jusqu'à aujourd'hui pour comprendre la progression et l'état actuel du site sans l'influence de ses premiers mois.

## Problématique

L’objectif est de comprendre :
- Comment le trafic évolue entre deux périodes
- Si le profil des utilisateurs change
- Quelles URL performent ou sous-performent
- Quels axes d’optimisation peuvent être identifiés

Pour cela seront analysés le trafic du site, l'évolution des profils utilisateurs, les performances des URL et une segementation des URL pour comprendre les catégories de visiteurs et les cibles.

## Outils utilisés

- Python (numpy, pandas, matplotlib) : préparation, nettoyage des données et pré-analyse
- Power BI : analyse, modélisation, visualisation


## Préparation des données

Avant l’analyse, les données ont été préparées afin de garantir leur cohérence :
- normalisation
- conversion de format
- filtrage des données non exploitables

Cette étape a été réalisée à l’aide d'un script Python (voir python - nettoyage_df.py)

