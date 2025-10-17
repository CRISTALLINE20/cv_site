# Site CV – multi-profils (Support / Réseaux / Cyber)

Un site **statique**, **rapide** et **personnalisable** pour postuler et *sortir du lot*.  
Tout se configure dans `data/profiles.json`. Vous pouvez créer **autant de profils** que vous le souhaitez et partager une URL par profil (`?p=nomduprofil`).

## Démarrer

1. Ouvrez `index.html` dans votre navigateur (double-clic).
2. Choisissez un profil en haut à droite (Support, Réseaux, Cyber).
3. Cliquez sur **Exporter PDF** pour générer un PDF propre (mise en page dédiée).

## Personnaliser

- **Contenu** : modifiez/dupliquez les objets dans `data/profiles.json`.
- **Nom de l’URL** : le champ `"id"` de chaque profil sert dans `?p=ID`.
- **Couleur d’accent** : changez `theme.accent` par profil (ex: `#e11d48`).  
- **Avatar** : remplacez `assets/avatar.svg` par votre photo (même nom de fichier).  
- **vCard** : le bouton exporte automatiquement un fichier `.vcf` avec vos coordonnées.

## Partager un profil précis

Envoyez un lien direct comme :

```
index.html?p=support
index.html?p=reseaux
index.html?p=cyber
```

## Déployer

- **GitHub Pages** : uploadez ce dossier dans un repo puis *Settings → Pages → Deploy from branch*.
- **Netlify / Vercel** : glissez-déposez le dossier, c’est instantané (site statique).
- **Hébergement perso** : uploadez les fichiers tels quels.

## Imprimer / PDF

Le bouton **Exporter PDF** utilise une feuille de style d’impression dédiée (`@media print`).  
Astuces : format *A4*, marges par défaut, fond d’arrière-plan activé, en-têtes/pieds désactivés.

## Astuces de candidature

- Ajoutez un profil par **cible** (ex: `p=helpdesk`, `p=reseaux`, `p=cyber`).  
- Créez des **liens courts** (bit.ly, etc.) par profil à mettre sur vos mails/LinkedIn.  
- Ajoutez des **mots‑clés** du poste dans la section Compétences pour passer l’ATS.

Bon courage !
