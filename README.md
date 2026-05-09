<<<<<<< HEAD
# Systeme d'Information Geographique — Analyse de l'accessibilite spatiale au Senegal

Rapport d'analyse realise dans le cadre du cours de Systeme d'Information Statistique  
**Auteur :** Poko Ibrahim NOBA — Eleve Analyste Statisticien, ENSAE  
**Superviseur :** M. DIEYE — Professeur de Systeme d'information Statistique  
**Date :** Juin 2025

---

## Presentation du projet

Ce projet analyse l'accessibilite geographique aux infrastructures de sante et d'education a l'echelle des communes du Senegal, en utilisant les outils du Systeme d'Information Geographique (SIG).

L'objectif principal est de mesurer la distance la plus courte entre chaque commune et les infrastructures les plus proches (hopitaux, centres de sante, ecoles), afin d'identifier les zones bien desservies et celles en deficit d'acces.

---

## Objectifs

- Cartographier la repartition spatiale des equipements publics (sante & education)
- Identifier les communes les mieux et les moins bien desservies
- Proposer des recommandations d'amenagement du territoire
- Contribuer a la reduction des inegalites spatiales au Senegal

---

## Donnees utilisees

| Source | Description |
|--------|-------------|
| OpenStreetMap (OSM) via Geofabrik | Ecoles (amenity=school), Hopitaux (amenity=hospital), Centres de sante (amenity=clinic) au format .pbf |
| HDX (Humanitarian Data Exchange) | Limites administratives communales du Senegal (niveau 3) |

---

## Outils et Methodologie

**Logiciel :** QGIS (libre et open source)

**Etapes de traitement :**
1. Extraction des donnees OSM via l'extension QuickOSM
2. Nettoyage des donnees (suppression des doublons, harmonisation de la projection)
3. Calcul des distances au plus proche centre via l'outil "Distance au plus proche centre (ligne vers centre)"
4. Jointure attributaire pour enrichir la couche communes
5. Visualisation sous forme de cartes thematiques choroplethe

---

## Resultats principaux

### Hopitaux
- Bien desservies (moins de 15 km) : Dakar, Rufisque, Guediawaye, Thies, Mbour, Saly, Kaolack
- Zones critiques (plus de 75 km) : Velingara, Ouro Sidi, Mbane, Goudiry, Kedougou, Kolda, Matam

### Centres de sante
- Bien desservies (moins de 30 km) : Dakar, Rufisque, Thies, Fatick, Ziguinchor, Tamba Commune
- Zones critiques (plus de 150 km) : Velingara, Ouro Sidi, Kenieba, Medina Gounass (regions Est et Sud-Est)

### Infrastructures scolaires
- Bien desservies (moins de 8 km) : Dakar Plateau, Ngor, Thies, Tambacounda, Sedhiou
- Zones penalisees (plus de 40 km) : Ouro Sidi, Houdalaye, Mboula Ladgar, Sinthiou Bocar Ali

---

## Recommandations

- Construire de nouvelles ecoles, centres de sante et structures hospitalieres dans les communes isolees (Velingara, Ouro Sidi, Ndendory, Klossa, Simbandi Balante)
- Deployer des dispositifs mobiles (cliniques itinerantes, ecoles communautaires)
- Ameliorer le reseau routier pour reduire les inegalites d'acces
- Utiliser cette analyse comme base pour prioriser les investissements publics

---

## Structure du projet

```
analyse-spatiale-accessibilite/
|
|-- data/          # Donnees brutes (OSM, limites administratives)
|-- maps/          # Cartes thematiques produites sous QGIS
|-- rapport/       # Rapport d'analyse (PDF)
|   |-- rapport_analyse_sig_ensae_2025.pdf
|-- scripts/       # Scripts QGIS / PyQGIS si applicable
|-- README.md
```

---

## Licence

Donnees sources : OpenStreetMap (ODbL) — https://www.openstreetmap.org  
Limites administratives : HDX — https://data.humdata.org  
Travail academique — ENSAE Dakar, 2025
=======
# analyse-spatiale-accessibilite-infrastructures-sociales
Analyse spatiale de l'accessibilité aux infrastructures sociales du Sénégal
>>>>>>> 2114edc1702cb5ba3134989902ec77b6d04b0337
