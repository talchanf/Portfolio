# Portfolio de Chantal Furnon

Mon portfolio personnel : présentation, CV, projets et passions. Site statique en HTML, CSS et JavaScript, sans framework.

## Pages

| Page | Contenu |
|---|---|
| `index.html` | Accueil : présentation, parcours, perspectives |
| `cv.html` | Aperçu du CV, téléchargement, compétences, diplômes et certificats |
| `projets.html` | Projets mis en avant |
| `passions.html` | Sommaire des passions, avec une page par thème dans `passions/` (cinéma, musique, jeux vidéo, psychologie, anime) |

## Particularités

- Fond étoilé animé dessiné sur un `canvas`
- Menu déroulant vers les sous-pages de Passions
- Cartes dont le résumé apparaît au survol (films, séries, jeux, anime), avec l'image en fond flou
- Cartes musique : un extrait est lu au survol pendant qu'un vinyle tourne
- Encarts de remplacement automatiques tant qu'une image n'a pas été ajoutée
- Site adapté aux écrans mobiles

## Technologies

HTML, CSS, JavaScript, polices Google Fonts (Fraunces et Sora).

## Voir le site

1. Télécharger tous les fichiers du dépôt.
2. Décompresser `assets.zip` à la racine, pour obtenir le dossier `assets/`.
3. Ouvrir `index.html` dans un navigateur.

Pour que les extraits audio et les téléchargements fonctionnent partout, il vaut mieux servir le site avec un petit serveur local (`python -m http.server`) ou le publier en ligne (GitHub Pages, Netlify).

## Structure

```
index.html, cv.html, projets.html, passions.html
passions/        pages de chaque passion
assets/
  css/           feuille de style
  js/            scripts
  images/        photos, affiches, pochettes
  audio/         extraits musicaux
  cv/            aperçus et PDF du CV
```
