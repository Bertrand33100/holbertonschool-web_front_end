# Advanced CSS — Holberton School

## Description du chapitre

Le chapitre **Advanced CSS** a pour objectif d'approfondir les connaissances en CSS afin de créer des interfaces web plus élaborées, structurées et professionnelles.

Après avoir appris les bases du HTML et du CSS, ce chapitre permet de mieux comprendre les mécanismes de mise en page, la gestion des styles et les techniques nécessaires pour reproduire fidèlement une maquette web.

**Auteur :** David Dias, Senior Software Engineer chez HomeX  
**Niveau :** Novice  
**Poids :** 1

## Objectifs pédagogiques

- Approfondir les propriétés CSS.
- Comprendre l'organisation et la hiérarchie des styles.
- Maîtriser les sélecteurs CSS et leur spécificité.
- Améliorer la mise en page des éléments HTML.
- Utiliser les unités, les couleurs, les espacements et les dimensions.
- Organiser les feuilles de style de manière claire et maintenable.
- Appliquer les bonnes pratiques de développement CSS.
- Reproduire une interface web à partir d'une maquette.

## Notions importantes

### 1. Les sélecteurs CSS

Les sélecteurs permettent de cibler les éléments HTML auxquels appliquer des styles.

Exemples :
- Sélecteur de balise : `p`
- Sélecteur de classe : `.container`
- Sélecteur d'identifiant : `#header`
- Sélecteur de descendant : `.container p`

### 2. La cascade et la spécificité

La cascade détermine quelles règles CSS sont appliquées lorsqu'un élément correspond à plusieurs déclarations.

La spécificité permet de départager certaines règles concurrentes. L'ordre des déclarations et l'utilisation de `!important` peuvent également influencer le résultat.

### 3. Le modèle de boîte — Box Model

Chaque élément HTML est représenté par une boîte composée de plusieurs parties :

- **Content** : le contenu de l'élément.
- **Padding** : l'espace intérieur entre le contenu et la bordure.
- **Border** : la bordure de l'élément.
- **Margin** : l'espace extérieur autour de l'élément.

La propriété `box-sizing: border-box` permet d'inclure le padding et la bordure dans les dimensions déclarées avec `width` et `height`.

### 4. Les couleurs et la typographie

CSS permet de personnaliser l'apparence du texte et des éléments grâce aux propriétés suivantes :

- `color` : couleur du texte.
- `background-color` : couleur d'arrière-plan.
- `font-family` : famille de police.
- `font-size` : taille du texte.
- `font-weight` : épaisseur du texte.
- `line-height` : hauteur de ligne.
- `text-align` : alignement du texte.

### 5. Les dimensions et les unités

Les unités CSS permettent de définir les tailles et les espacements.

Exemples :
- `px` : pixels.
- `%` : pourcentage de la taille de référence.
- `em` : unité relative à la taille de police de référence.
- `rem` : unité relative à la taille de police de l'élément racine.
- `vw` et `vh` : unités relatives aux dimensions de la fenêtre d'affichage.

### 6. La mise en page

CSS permet d'organiser les éléments sur une page grâce à différentes propriétés et techniques, notamment :

- `display` : définit le comportement d'affichage.
- `position` : contrôle le positionnement des éléments.
- `margin` et `padding` : gèrent les espacements.
- `width` et `height` : définissent les dimensions.
- Flexbox et CSS Grid : permettent de créer des mises en page adaptées aux besoins du projet.

Les techniques à étudier dépendent des exercices précis du chapitre.

## Bonnes pratiques

- Utiliser des noms de classes explicites.
- Éviter les répétitions inutiles dans les feuilles de style.
- Organiser les règles CSS de manière cohérente.
- Privilégier des sélecteurs simples et compréhensibles.
- Vérifier le rendu visuel dans le navigateur.
- Respecter la structure HTML existante.
- Écrire un code lisible et facile à maintenir.

## Compétences développées

À travers ce chapitre, les compétences travaillées portent sur :

- La compréhension approfondie du fonctionnement de CSS.
- La personnalisation de l'apparence des éléments HTML.
- La gestion des dimensions et des espacements.
- La compréhension de la cascade et de la spécificité.
- L'organisation des styles.
- La réalisation d'interfaces web plus soignées.

## Conclusion

Le chapitre Advanced CSS permet de consolider les bases du développement front-end et de progresser vers la création d'interfaces web plus professionnelles.

La maîtrise de CSS est essentielle pour transformer une structure HTML en une page web agréable à lire, cohérente et adaptée aux besoins d'un projet.

Les notions acquises serviront de base pour aborder des sujets plus avancés, comme le responsive design, les animations CSS et la création de composants d'interface réutilisables.
