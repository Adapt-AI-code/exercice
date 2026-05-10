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

