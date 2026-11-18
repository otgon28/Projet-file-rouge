# Projet Fil Rouge — Solène Avril

**AMARJARGAL Otgon-Erdene**

Portfolio de photographe réalisé en HTML / CSS. Le site reprend la maquette fournie (vues ordinateur, tablette et mobile) : un en-tête, une section de présentation avec un menu de filtres, une galerie de photos, et un pied de page.

🔗 **Voir le site : [GitHub Pages](https://otgon28.github.io/Projet-file-rouge/)**

## Langages utilisés

* HTML5
* CSS3 (Flexbox, Grid, Media Queries)

## Polices

Les polices Yeseva One (titres) et Montserrat (texte courant) sont importées via l'API Google Fonts, intégrée dans le `<head>` du fichier HTML.

## Icônes

Les icônes (réseaux sociaux) viennent de Font Awesome, intégré via mon kit personnel, chargé lui aussi dans le `<head>`.

## Images

Les photos de la galerie viennent de Lorem Picsum, avec des liens configurés pour obtenir des images différentes à chaque photo.

## Structure HTML

Le fichier `index.html` suit une structure sémantique classique :

* `<header>` : logo du site et icônes des réseaux sociaux.
* `<main>`, qui contient trois blocs :
   * `.hero` : le titre d'accroche et un court texte de présentation.
   * `.filters` : le menu de catégories (`<nav>`) : Nature, Portrait, Art, Urbain, Animaux.
   * `.grid` : la galerie de 15 photos.
* `<footer>` : mentions de copyright.

## Mise en forme CSS

* Le header et le menu de filtres sont mis en page avec Flexbox, pour aligner leurs éléments en ligne.
* La galerie de photos utilise CSS Grid, pour organiser les photos en colonnes et lignes (4 colonnes sur ordinateur).
* Des media queries adaptent l'affichage sur tablette (5 colonnes) et sur mobile (3 colonnes, en-tête centré).