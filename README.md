# Site CV – multi-profils

Deux façons d'ouvrir :
1) **index-embedded.html** → *tout-en-un* (recommandé pour double-clic, aucun fetch).
2) **index.html** → version multi-fichiers (lit `data/profiles.json`).

## Astuce si sections vides
- Si vous ouvrez `index.html` en `file://`, certains navigateurs bloquent le chargement JSON. Utilisez `index-embedded.html` ou un petit serveur local :
  ```bash
  python -m http.server 8000
  ```
  puis http://localhost:8000.

Tout le contenu est dans `data/profiles.json` (ou la balise `<script id="profilesData">` pour la version tout-en-un).
