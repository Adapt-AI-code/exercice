---

_please scroll down for English_

---

# Exercice Stagiaire

## Objectif
Cet exercice a pour objectif d’évaluer vos compétences sur des problématiques similaires à celles que nous traitons.
Vous devrez mettre en place une petite application de cartographie adossée à une base de données.

---

## Cahier des charges

L'application devra offrir, sur un fond de carte OSM, une représentation des polygones des parcelles cadastrales appartenant à des personnes morales, pour le département **02 (Aisne)**. Elle devra proposer, à travers une interface intuitive, le numéro SIREN des propriétaires.

**Bonus:** Afficher également la dénomination (le nom d'entreprise) du propriétaire.


## Ressources à considérer
- bases de données postGIS
- Fichier Parcellaire Express (PCI)
- Fichier des locaux et parcelles des personnes morales (aussi dit fichier MAJIC)
- Base SIRENE des entreprises et de leurs établissements

## Pistes de réflexion

Certaines ressources sont disponibles via API officielles ou tierces, d'autres non, vous devrez faire des choix sur celles que vous souhaitez ingérer et héberger en propre.

L'application devra suivre une architecture classique:

```
base de données <--- API <---> frontend
```

Nous vous laissons toute latitude concernant la stack exacte.

---

## Rendu du projet
📦 **Le code doit être rendu sur un dépôt GitHub.**  
- Créez un dépôt public ou privé (dans ce cas, donnez accès à l'équipe).
- Incluez un fichier **README.md** avec les instructions pour installer et exécuter votre application. **L'application devra impérativement pouvoir démarrer sur un environnement vierge.**
- N'hésitez pas à utiliser l'IA, cependant, veillez à ce que votre code reste expliquable.

---

# English version - Intern Exercise

## Objective
The purpose of this exercise is to assess your skills on problems similar to those we handle day to day. You will need to build a small map application connected to a database.

## Specifications
The application must display, on top of an OSM (OpenStreetMap) basemap, the polygons of cadastral parcels owned by legal entities (companies/organizations) for department 02 (Aisne), in France. It must provide, through an intuitive interface, the owners’ SIREN number (a unique number identifying a company).

**Bonus:** Also display the owner’s denomination (company name).

## Resources to Consider
- PostGIS database
- Parcellaire Express file (PCI Express)
- Fichier des locaux et parcelles des personnes morales (also called MAJIC file)
- SIRENE database of companies and their establishments

## Points to Consider
Some resources are available through official or third-party APIs, while others are not, so you will need to decide which data sources you want to ingest and host yourself.

The application should follow a standard architecture:

```text
database <--- API <---> frontend
```

You are free to choose the exact tech stack.

## Project Submission
📦 The code must be submitted in a GitHub repository.

- Create a public or private repository (if private, grant access to the team).
- Include a `README.md` file with instructions for installing and running your application. The application must be able to start in a clean environment.
- Feel free to use AI tools; however, make sure your code remains explainable.
