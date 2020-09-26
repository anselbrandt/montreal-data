# Dictionnaire de données

[Download GeoJSON](http://donnees.ville.montreal.qc.ca/dataset/unites-evaluation-fonciere)

- ID_UEF (Numérique) : Identifiant unique système
- CIVIQUE_DEBUT (Numérique) : Numéro civique (plage - début)
- CIVIQUE_FIN (Numérique) : Numéro civique (plage - fin)
- NOM_RUE (Texte variable) : Nom de rue
- SUITE_DEBUT (Texte variable) : Numéro unité (appartement ou local)
- ETAGE_HORS_SOL (Numérique) : Nombre d'étages hors sol;
- NOMBRE_LOGEMENT (Numérique) : Nombre de logement;
- ANNEE_CONSTRUCTION (Numérique) : Année de construction;
- CODE_UTILISATION (Numérique) : Codification CUBF;
- LIBELLE_UTILISATION (Texte variable) : Descriptif CUBF;
- CATEGORIE_UEF (Liste de valeur) : Catégorie unité évaluation (Régulier ou Condominium);
- MATRICULE83 (Numérique) : Matricule au rôle foncier (système géographique NAD83 MT8);
- SUPERFICIE_TERRAIN (Numérique) : Superficie du terrain pour fin d'évaluation foncière;
- SUPERFICIE_BATIMENT (Numérique) : Aire d'étages du bâtiment, soit surface brute correspondant à la somme des aires de chacun des étages entiers du bâtiment principal et, le cas échéant, de celles de l’attique, du garage intégré et de la verrière intégrée;
- NO_ARROND_ILE_CUM (Numérique) : Identifiant de l'arrondissement ( Référence identifiant MAMROT );
- MUNICIPALITE (Numérique) : Identifiant interne de la municipalité.

  - Baie-D'Urfé : 02
  - Beaconsfield : 03
  - Côte-Saint-Luc : 04
  - Dollard-Des Ormeaux : 05
  - Dorval : 06
  - Hampstead : 07
  - Kirkland : 10
  - L'Île-Dorval : 09
  - Mont-Royal : 13
  - Montréal : 50
  - Montréal-Est : 14
  - Montréal-Ouest : 15
  - Pointe-Claire : 20
  - Sainte-Anne-de-Bellevue : 23
  - Senneville : 22
  - Westmount : 29

Note: La valeur numérique -1 est équivalente "Null" et signifie "non-applicable".

### Limites:

- L'aire d'étage n'apparaît que dans les cas où il n'y a qu'un seul bâtiment dans l'unité d'évaluation
- Le nombre d'étages inscrit pour les unités de type «Condominium» est celui exclusif de l'unité et non pas de l'immeuble dans lequel est située l'unité.
- Le nombre de logements inscrit pour les unités de type «Condominium» est celui de l'unité et non pas le nombre de logements compris dans l'immeuble où est située l'unité.
- Pour les copropriétés divises «condominium», les unités d'évaluation se superposent sur un même emplacement
- Les matricules fonciers qui ont été modifiés et pour lesquels la géométrie n'a pas encore été mise à jour sont représentés une géométrie temporaire (carré 2mx2m)
