# Mon Classeur Pokémon

Application web pour recenser ses cartes Pokémon : rangement par série et par extension, image de chaque carte, case « Je l'ai » et prix actuel du marché (Cardmarket en €, TCGplayer en $).

## Utilisation

- **En local** : télécharge `index.html` et ouvre-le dans ton navigateur (une connexion internet est nécessaire).
- **En ligne** : active GitHub Pages (Settings → Pages → branche `main`, dossier `/ (root)`).

## Fonctionnalités

- Toutes les séries et extensions, avec une barre de progression par extension
- Grille des cartes avec image ; les cartes manquantes sont grisées
- Filtres « Toutes / Je l'ai / Il me manque », recherche par nom ou numéro, tri par prix
- Fiche détaillée : tendance, prix moyen, prix bas, moyenne 30 jours, version holo, prix TCGplayer
- Valeur de ta collection et coût des cartes manquantes
- Cartes en français ou en anglais
- Export / import de ta collection (fichier JSON)

## Données

Les cartes, images et prix viennent de l'API gratuite [TCGdex](https://tcgdex.dev).
Tes cartes cochées sont enregistrées dans ton navigateur (localStorage) : pense à **Exporter** régulièrement une sauvegarde.
