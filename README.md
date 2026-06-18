# 💧 Analyse mondiale de l'accès à l'eau potable avec Power BI

## 🎯 Objectif

Concevoir un tableau de bord interactif permettant d'analyser l'accès à l'eau potable à l'échelle mondiale et d'identifier les pays prioritaires pour les actions d'une ONG internationale.

## 📌 Contexte

Projet réalisé dans le cadre de la formation **Data Analyst OpenClassrooms**.

L'ONG fictive **DWFA (Drinking Water For All)** souhaite mieux cibler ses investissements afin d'améliorer l'accès à l'eau potable dans les pays les plus vulnérables.

Le tableau de bord a pour objectif d'aider les décideurs à identifier rapidement les zones prioritaires en combinant plusieurs indicateurs socio-économiques et sanitaires.

## ❓ Problématique

Comment exploiter des données internationales afin de repérer les pays présentant les plus fortes difficultés d'accès à l'eau potable et orienter efficacement les actions de développement ?

## 📂 Sources de données

Les données proviennent de plusieurs organismes internationaux :

* OMS (WHO)
* Banque Mondiale
* FAO

### Indicateurs étudiés

* Taux d'accès à l'eau potable
* Population
* Taux de mortalité lié à l'eau
* Indice de stabilité politique
* Répartition géographique

## 🛠️ Méthodologie

### Préparation des données

* Nettoyage des données
* Gestion des valeurs manquantes
* Harmonisation des noms de pays
* Création des dimensions géographiques
* Création d'une dimension temporelle

### Modélisation Power BI

Création d'un modèle relationnel comprenant :

* Tables de faits
* Dimensions Pays
* Dimensions Continent
* Dimension Année

### Création des indicateurs

Développement de mesures permettant :

* L'analyse du niveau d'accès à l'eau
* L'évaluation des risques sanitaires
* La comparaison entre pays
* Le calcul d'un score de priorité

## 📊 Structure du tableau de bord

### Page 1 : Vue Monde

* Vision globale des indicateurs
* Carte mondiale
* KPI principaux

### Page 2 : Vue Régionale

* Analyse par continent
* Comparaison régionale
* Classement des zones prioritaires

### Page 3 : Vue Pays

* Analyse détaillée par pays
* Évolution temporelle
* Indicateurs spécifiques

## 📈 Principaux indicateurs

* Population concernée
* Taux d'accès à l'eau potable
* Taux de mortalité lié à l'eau
* Indice de stabilité politique
* Score de priorité DWFA

## 💡 Valeur ajoutée métier

Le tableau de bord permet :

* D'identifier les pays les plus vulnérables
* De prioriser les investissements de l'ONG
* D'orienter les actions de terrain
* D'appuyer les décisions stratégiques avec des données fiables

## 🧰 Technologies utilisées

* Power BI Desktop
* Power Query
* DAX
* Excel
* CSV

## 📁 Structure du projet

```text
dashboard/
│
├── dwfa_water_dashboard.pbix

data/
│
├── water_access.csv
├── mortality.csv
├── political_stability.csv

presentation/
│
├── presentation.pdf

README.md
```

## 📊 Visualisations réalisées

* Carte mondiale interactive
* KPI Cards
* Graphiques en barres
* Courbes temporelles
* Classements dynamiques
* Filtres interactifs

## ✅ Compétences développées

* Power BI
* Power Query
* DAX
* Modélisation de données
* Data Visualisation
* Analyse géographique
* Analyse de données publiques
* Storytelling de données
* Aide à la décision

## 🌍 Impact métier

Ce projet démontre comment les données peuvent être utilisées pour soutenir les décisions d'organisations internationales et contribuer à une meilleure allocation des ressources dans le domaine de l'accès à l'eau potable.

## 👨‍💻 Auteur

**Mohamed Zaidi**
