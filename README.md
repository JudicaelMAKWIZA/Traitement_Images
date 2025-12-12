# Traitement et Analyse d'Images (M1 IA & Data Science, Unikin)

Ce dépôt contient les travaux pratiques (TP1 et TP2) réalisés dans le cadre du cours de Traitement d'Images, sous la supervision du **Prof. Masakuna Jordan**.

Le travail se concentre sur l'application et l'analyse de différentes techniques de manipulation d'images (amélioration du contraste, réduction de bruits, et détection de contours) en utilisant la librairie **OpenCV** avec Python.

## Structure du Projet

| Dossier/Fichier | Description |
| :--- | :--- |
| `TP1_Correction_Contraste/` | Contient le Notebook d'implémentation du TP1 (Correction de Contraste). |
| `TP2_Filtres_Contours/` | Contient le Notebook d'implémentation du TP2 (Filtres, Bruits, Contours). |
| `Data_TP1.zip/` | Archive contenant les images originales utilisées dans les TPs. |
| `Rapport_TP1.pdf` | Rapport d'analyse final du TP1. |
| `Rapport_TP2.pdf` | Rapport d'analyse final du TP2. |

---

## I. TP1 : Correction de Contraste

**Objectif :** Évaluer et comparer différentes techniques d'amélioration du contraste sur des images sombres ou à faible dynamique.

### Méthodes Appliquées

* **Transformation Linéaire** (Implémentation manuelle)

* **Correction Gamma** (Implémentation manuelle)
* **Égalisation d'Histogramme** (OpenCV)

## II. TP2 : Filtres (Bruits et Contours)

**Objectif :** Appliquer des filtres spatiaux pour la réduction des bruits et la mise en évidence des contours.

### 1. Réduction des Bruits

Analyse comparative des filtres sur différents types de bruit (Gaussien et Impulsionnel) :

* Filtre Moyenneur
* Filtre Gaussien
* Filtre Médian
* Filtre Min (Érosion)
* Filtre Max (Dilatation)

### 2. Détection de Contours

Application et évaluation des méthodes de gradient :

* Seuillage sur la **Norme du Gradient** (Opérateur de Sobel).
* Filtre de **Canny** (Algorithme multi-étapes pour des bords fins et continus).

---

## Processus pour Tester le Travail

Pour exécuter les notebooks et reproduire les résultats :

### 1. Prérequis

Assurez-vous d'avoir Python 3.10+ installé.

### 2. Cloner le Dépôt

```bash
git clone [https://github.com/JudicaelMAKWIZA/Traitement_Images.git](https://github.com/JudicaelMAKWIZA/Traitement_Images.git)
cd Traitement_Images
```

---

### 3. Installation des Dépendances

Installez les librairies nécessaires : opencv-python, numpy, et matplotlib :

```bash
pip install opencv-python numpy matplotlib jupyter
```

---

Installez toutes les librairies Python requises en utilisant le fichier requirements.txt :

```bash
pip install -r requirements.txt
```
