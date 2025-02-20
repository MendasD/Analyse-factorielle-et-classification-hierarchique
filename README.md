# Analyse factorielle et classification hiérarchique
---

## 📌 **Présentation du projet**  

Ce projet constitue le travail final du **cours d'analyse des données multidimensionnelles**. Il met en application des méthodes statistiques avancées à travers une **classification hiérarchique sur les composantes principales** issues d'une analyse factorielle. L'objectif est d'exploiter ces outils pour structurer et interpréter un ensemble de données économiques et démographiques.  

### 🎯 **Objectifs spécifiques**  
Le projet couvre plusieurs aspects clés du cours, notamment :  

- Justifier l'utilisation de la **classification hiérarchique** sur les **composantes principales**.  
- Réaliser une **analyse factorielle** adéquate sur le jeu de données fourni.  
- Appliquer la **classification hiérarchique** sur ces composantes principales.  
- Construire un **indice synthétique normalisé** basé sur les résultats de l'analyse factorielle.  
- Découper l'indice obtenu en **classes homogènes** à l'aide de la méthode des **k-means**.  
- Effectuer une **analyse factorielle discriminante** en utilisant la **classe d’indice** obtenue comme variable superviseur.  

Nous commencerons par une **présentation des données** avant d'aborder chaque étape méthodologique.  

---

## 📊 **Présentation de la base de données**  

Le jeu de données utilisé dans ce projet a été fourni par l'enseignant. Il est au format **Excel** et décrit **120 pays** à l'aide de **12 variables quantitatives** reflétant des indicateurs économiques et démographiques.  

### 🏷️ **Description des variables**  

| Variable | Description |
|----------|------------|
| `Croi_PIB/hab` | Taux de croissance du PIB par habitant |
| `Ctr_agri_PIB(%)` | Contribution de l'agriculture à la création de richesse |
| `Poids_Exp_sur_PIB(%)` | Poids des exportations dans le PIB |
| `Ctr_Tertiaire_PIB(%)` | Contribution du secteur tertiaire à la création de richesse |
| `Ctrind_PIB(%)` | Contribution de l'industrie à la création de richesse |
| `Tx_Eau_potable` | Taux d'accès à l'eau potable |
| `Taux_pene_Tel_mob` | Taux de pénétration du téléphone mobile |
| `Part_Pop_0-14_ans` | Part des enfants dans la population totale |
| `Part_Pop_65ans_et_plus` | Part des personnes âgées dans la population totale |
| `Pop_rurale` | Part de la population vivant en milieu rural |
| `Croi_pop` | Taux de croissance démographique |
| `Use_Index_Internet` | Indice d'utilisation d'Internet |

---

## 🚀 **Méthodologie et étapes d'analyse**  

1. **Prétraitement des données** : Vérification des valeurs manquantes et standardisation des variables.  
2. **Analyse factorielle** : Identification des composantes principales et justification de leur utilisation.  
3. **Classification hiérarchique** : Segmentation des pays en groupes homogènes sur la base des composantes principales.  
4. **Construction d’un indice synthétique** : Création d’un score normalisé pour chaque pays.  
5. **Clustering par k-means** : Découpage de l’indice synthétique en classes.  
6. **Analyse factorielle discriminante (AFD)** : Validation des classes obtenues en étudiant leur pouvoir discriminant.  

---

## 🔧 **Outils utilisés**  

- **Langage** : R  
- **Packages principaux** : `FactoMineR`, `ggplot2`, `corrplot`, `cluster`, `MASS`  
- **Visualisation** : ACP (Analyse en Composantes Principales), dendrogramme, boxplots, heatmaps, etc.  

---

## 📂 **Organisation du projet**  

- `data/` : Contient le fichier de données.  
- `scripts/` : Contient les scripts R pour chaque étape de l'analyse.  
- `results/` : Contient les visualisations et résultats obtenus.  
- `README.md` : Ce document expliquant le projet.  

---

## 📢 **Auteurs et contact**  

📧 Contact : christnzonde@gmail.com  
📖 Cours : Analyse des données multidimensionnelles  
🏫 Institution : Ecole Nationale de la Statistique et de l'Analyse Economique Pierre Ndiaye (ENSAE)  

---
