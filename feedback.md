# Feedback du prof

## Test Menu

### Enoncé

- 5 liens
- Lien "Blog" actif
- Changement d'état au survol

### Notions

- [x] Création d'un élément `<nav>` pour la sémantique
- [x] Organisation des liens dans une liste (1x `<ul>` et 5x `<li>`)
- [ ] Classe CSS spécifique pour le lien "actif"
- [x] Utilisation de la pseudo-classe `:hover` pour le survol

### Commentaires

- Il te manque la classe "active" pour signaler la page sur laquelle on se trouve (ici "Blog")
- Sinon nickel :thumbsup:

## Test Articles

### Enoncé

- 4 Articles
- Les images de gauche prennent toute la hauteur de l'article
- 1 lien vers chaque catégorie liée
- Changement d'état de chaque lien "catégorie" au survol
- 2 liens vers les réseaux sociaux
- Changement d'état des liens "réseaux sociaux" au survol
- Afficher la date de publication en haut à droite
- Afficher la catégorie et les réseaux sociaux en bas, quelque soit la hauteur de l'article
- Alterner les triangles bordant le dessous des artciles
- Afficher une ombre autour de l'article

### Notions

- [ ] Utilisation des balises `<section>` et/ou `<article>`
- [ ] Utilisation de `flex` pour afficher l'image de gauche en `stretch`
- [ ] Design du bouton "catégorie" (background, uppercase)
- [x] Design du bouton "réseaux sociaux" (border-radius, background)
- [x] Utilisation de la pseudo-classe `:hover` pour le survol
- [x] Utilisation de `flex` en direction `column` + `space-between` pour positionner la date, le texte et les liens en bas, sinon avec des `position:absolute;`
- [x] Triangle rose ou bleu avec la pseudo-classe `:nth-child(even)` pour les "pairs" et `:nth-child(odd)` pour les "impairs", sinon, avec 2 classes CSS
- [x] Ombre avec la propriété `box-shadow`

### Commentaires

- Il ne faut pas oublier la sémantique, c'est assez important
- Beaucoup de `flex` dans cette partie :wink:
- Le bouton "catégorie" ne ressemble pas assez à la créa
- Pour être certain que la date soit en haut, le texte au milieu et les liens en bas, le plus simple est d'afficher en `flex` et de changer la direction en `column`. Peu importe la longueur du date, le résultat sera toujours correct

## Test Gabarit

### Enoncé

- Image en arrière-plan
- Le contenu ne colle pas les bords de la fenêtre
- Le logo est placé en haut à gauche
- Un bouton standard (suivant)
- Changement d'état du bouton standard au survol (précédent)

### Notions

- [x] Utilisation des 3 balises sémantiques principales `<header>`, `<main>` et `<footer>`
- [x] Propriétés CSS dans un fichier séparé du HTML + import avec `<link>`
- [x] Image en background et répétée sur le `<body>`
- [ ] Un "container"/"wrapper" ou un `<main>` avec une propriété `max-width` + `margin:auto;`
- [x] Logo hors du flux avec `position:absolute;`
- [x] Bouton standard avec coins arrondis grâce à `border-radius`
- [x] Bouton standard avec les textes en majuscule grâce à `text-transform`
- [x] `background-color` change sur les boutons standards au survol avec la pseudo-classe `:hover`
- [ ] Chargement des fichiers Javascript en bas de page

### Commentaires

- Tu as bien mis `<header>`, `<main>` et `<footer>`, par contre, il est préférable sémantiquement parlant qu'ils soient totalement séparé (frères et soeurs, mais pas enfants)
- Pour centrer un site qui ne prend pas toute la largeur, le mieux est de définir `max-width` + `margin:0 auto;` pour la centrer
- Sinon RAS :ok_hand:

## Test Footer

### Enoncé

- Barre horizontale de séparation
- A gauche :
  - le texte du copyright
  - le nom de l'agence
- A droite :
  - 4 liens

### Notions

- [x] Utilisation de `flex` ou `CSS Grid` sinon `float`, pour les 2 colonnes (gauche et droite)
- [x] `border-top` pour la barre horizontale
- [x] Utilisation du code HTML ou Unicode pour le &copy;
- [x] Création d'un élément `<nav>` pour la sémantique
- [x] Organisation des liens dans une liste (1x `<ul>` et 4x `<li>`)

### Commentaires

- Le footer n'est pas centré
- Sinon RAS :ok_hand:

## Test Responsive

### Enoncé

- Rendre le site "Responsive"
- Optimiser l'affichage selon plusieurs breakpoints
- Sur des écrans plus petits, le contenu central colle les bords de la fenêtre

### Notions

- [x] Balise meta pour le viewport : `<meta name="viewport" content="width=device-width, initial-scale=1">`
- [x] Utilisation de 3 breakpoints ou plus (`@media (min-width:768px) { ... }`)
- [ ] Définition des propriétés CSS en "Mobile First"
- [ ] Optimisation de l'affichage pour mobile
- [ ] Optimisation de l'affichage pour tablet
- [x] Optimisation de l'affichage pour desktop
- [ ] Menu burger en mobile

### Commentaires

- Quand on code un site Responsive, on commence par coder la version mobile puis, selon les breakpoints, on ajoute des propriétés pour les appareils plus grands => "Mobile First"
- La version mobile n'était pas assez optimisée, dommage :(
- La version tablet n'était pas assez optimisée, dommage :(
- Le top pour la navigation en mode mobile, c'est de mettre en place un menu "Burger" et c'est beaucoup plus simple avec Bootstrap :wink:
- En mode "mobile", on va d'abord afficher les liens du footer, puis, en dessous, le copyright

## Général

- [x] Utilisation de balises HTML avec valeur sémantique
- [ ] Précision des ciblages/selectors
- [x] Utilisation de préfixes (compatibilité avec anciens navigateurs)
- Qualité du code
  - [ ] indentation et lisibilité du code
  - [ ] Présence de commentaires dans le code
- Options
  - [ ] Utilisation de transformations / animations

### Commentaires

- Excellente évaluation, bravo :clap:
- Très bonne évaluation, bravo :clap:
- Attention à l'indentation, c'est primordial pour bien coder, surtout en équipe
