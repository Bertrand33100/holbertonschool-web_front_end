# Advanced HTML

## Présentation du projet

- **Niveau :** Novice
- **Auteur du projet :** David Dias, Senior Software Engineer chez HomeX
- **Poids :** 1
- **Formation :** Holberton School
- **Dépôt GitHub :** `holbertonschool-web_front_end`
- **Répertoire :** `html_advanced`
- **Technologie principale :** HTML5

## Description

Ce projet a pour objectif d'apprendre à structurer une page web en utilisant les éléments HTML5.

HTML (*HyperText Markup Language*) est un langage de balisage qui permet de définir la structure et le contenu d'une page web : titres, paragraphes, images, liens, listes, tableaux, vidéos et autres éléments.

Le projet utilise **Techium** comme nom d'entreprise fictive pour construire les différentes pages web.

L'objectif est de produire un HTML bien structuré, compréhensible, sémantique et conforme aux standards du Web.

Ce projet se concentre uniquement sur HTML. Le CSS et la mise en forme visuelle ne sont pas demandés à ce stade. Une page peut donc paraître simple ou peu esthétique : c'est normal.

## Objectifs pédagogiques

À la fin de ce projet, je dois être capable d'expliquer et d'utiliser les notions suivantes sans avoir besoin de rechercher systématiquement les réponses sur Internet.

### 1. Les bases du HTML

- Comprendre le rôle du HTML dans une page web.
- Respecter les bonnes pratiques d'écriture du HTML.
- Comprendre la structure générale d'un document HTML5.
- Utiliser correctement le doctype.
- Définir la langue du document et le sens de lecture.
- Utiliser les balises ouvrantes et fermantes lorsque cela est nécessaire.
- Respecter la casse, l'orthographe et l'imbrication des balises.

### 2. La structure d'une page HTML5

Connaître les principales balises qui constituent une page web :

- `<!DOCTYPE html>` : indique que le document utilise le standard HTML.
- `<html>` : élément racine du document.
- `<head>` : contient les métadonnées et les ressources associées au document.
- `<meta>` : définit des métadonnées.
- `<title>` : définit le titre affiché dans l'onglet du navigateur.
- `<link>` : permet notamment de relier une feuille de style.
- `<body>` : contient le contenu de la page affiché à l'utilisateur.

### 3. Le HTML sémantique

Comprendre pourquoi il est important de choisir des balises adaptées au rôle du contenu.

- `<header>` : représente une zone d'introduction ou d'en-tête.
- `<main>` : représente le contenu principal de la page.
- `<footer>` : représente le pied de page d'une section ou du document.
- `<article>` : représente un contenu autonome.
- `<nav>` : représente une zone de navigation.
- `<section>` : regroupe un contenu thématique.
- `<aside>` : représente un contenu complémentaire.
- `<div>` : regroupe des éléments sans leur attribuer de signification sémantique particulière.
- `<span>` : regroupe du contenu en ligne sans signification sémantique particulière.

### 4. Les titres et les paragraphes

- Utiliser les titres de `<h1>` à `<h6>`.
- Respecter une hiérarchie logique des titres.
- Structurer les paragraphes avec `<p>`.
- Utiliser `<br>` pour un saut de ligne lorsque cela est pertinent.
- Utiliser `<hr>` pour représenter une séparation thématique.

### 5. Les listes

- `<ul>` : crée une liste non ordonnée.
- `<ol>` : crée une liste ordonnée.
- `<li>` : représente un élément de liste.

### 6. Les liens et les images

- `<a>` : crée un lien hypertexte.
- `<img>` : intègre une image.
- `href` : indique la destination d'un lien.
- `src` : indique la source d'une image.
- `alt` : fournit un texte alternatif à une image.
- `<iframe>` : permet d'intégrer un autre document, par exemple une page externe lorsque son intégration est autorisée.

### 7. Les médias

Connaître les principales différences entre les formats d'image :

- **SVG** : format vectoriel adapté notamment aux icônes et aux illustrations.
- **GIF** : format prenant en charge l'animation.
- **PNG** : format matriciel prenant en charge la transparence.
- **JPG/JPEG** : format matriciel couramment utilisé pour les photographies.

Savoir également intégrer des médias :

- `<video>` : intègre une vidéo.
- `<audio>` : intègre un fichier audio.
- `<source>` : permet de préciser une source média.
- `<track>` : permet notamment d'ajouter des sous-titres à une vidéo.

### 8. Les tableaux

- `<table>` : définit un tableau.
- `<caption>` : définit le titre du tableau.
- `<thead>` : regroupe les lignes d'en-tête.
- `<tbody>` : regroupe le corps du tableau.
- `<tfoot>` : regroupe les informations de pied de tableau.
- `<tr>` : définit une ligne.
- `<th>` : définit une cellule d'en-tête.
- `<td>` : définit une cellule de données.

### 9. Les bonnes pratiques

- Écrire un HTML valide et bien structuré.
- Utiliser les balises selon leur fonction.
- Respecter l'ordre logique des titres.
- Fournir un texte alternatif pertinent aux images informatives.
- Éviter les balises utilisées uniquement pour leur apparence lorsque des éléments sémantiques sont adaptés.
- Vérifier le document avec le validateur W3C.

## Ressources

### Documentation et références

- [HTML 5.2](https://www.w3.org/TR/html52/)
- [MDN — HTML : langage de balisage hypertexte](https://developer.mozilla.org/fr/docs/Web/HTML)
- [MDN — Référence des éléments HTML](https://developer.mozilla.org/fr/docs/Web/HTML/Reference/Elements)
- [Can I use](https://caniuse.com/) — vérification de la compatibilité des fonctionnalités web.
- [W3C Validator](https://validator.w3.org/) — validation du code HTML.
- [HTML Cheat Sheet — WebsiteSetup](https://websitesetup.org/)

### Concepts Holberton

- [HTML — Elements of a Web Page](https://intranet.hbtn.io/concepts/870)
- [Description du projet Advanced HTML](https://intranet.hbtn.io/projects/2138)

## Contraintes du projet

- Le fichier `README.md` doit être présent à la racine du répertoire `html_advanced`.
- Le code doit respecter les standards HTML et être validé avec le validateur W3C lorsque la tâche le permet.
- Le nom de l'entreprise utilisé dans les pages est **Techium**.
- Les consignes de chaque tâche doivent être respectées précisément.
- Les noms des balises, leurs attributs et leur imbrication doivent être vérifiés attentivement.

## Organisation du projet

```text
holbertonschool-web_front_end/
└── html_advanced/
    ├── README.md
    └── 0-index.html
```

Cette arborescence correspond au début du projet. Les autres fichiers HTML seront ajoutés au fur et à mesure des tâches.

## Tâches

### Tâche 0 — Create your first webpage

**Fichier :** `0-index.html`

**Objectif :** créer le premier document HTML5.

#### Consignes

1. Ajouter `<!DOCTYPE html>` sur la première ligne, sans commentaire avant.
2. Ouvrir et fermer la balise `<html>`.
3. Définir l'attribut `lang` avec la valeur `en`, correspondant à l'anglais.
4. Définir l'attribut `dir` avec la valeur `ltr`, correspondant à une lecture de gauche à droite.
5. Ouvrir le fichier dans un navigateur et vérifier que la page est blanche.

#### Code attendu

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
</html>
```

#### Explication du code

- `<!DOCTYPE html>` : déclare un document HTML moderne.
- `<html>` : contient l'ensemble du document.
- `lang="en"` : indique que la langue principale du document est l'anglais.
- `dir="ltr"` : indique que le texte se lit de gauche à droite.
- `</html>` : ferme l'élément racine.

À cette première étape, le document ne contient ni `<head>` ni `<body>`. La consigne demande uniquement la structure minimale indiquée ci-dessus. Le validateur W3C peut signaler des éléments manquants : la consigne du projet autorise à ignorer cet échec pour cette tâche.

## Méthode de travail

Pour chaque tâche :

1. Lire attentivement les consignes.
2. Identifier les balises et les attributs demandés.
3. Créer le fichier HTML attendu.
4. Vérifier l'orthographe et la casse.
5. Ouvrir le fichier dans un navigateur.
6. Valider le HTML avec le W3C lorsque cela est demandé et applicable.
7. Comparer le résultat aux exigences du projet.
8. Enregistrer le travail dans Git et le publier sur GitHub selon les consignes de la formation.

## Conclusion

Ce projet constitue une première étape importante dans l'apprentissage du développement web front-end. Il permet d'acquérir les bases nécessaires pour structurer correctement une page web avant d'aborder la mise en forme avec CSS et l'interactivité avec JavaScript.

L'objectif principal est de comprendre le rôle de chaque élément HTML et de savoir construire un document accessible, cohérent et conforme aux standards du Web.
