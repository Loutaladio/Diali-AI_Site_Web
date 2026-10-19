# Diali AI — site officiel

Copie publique du site vitrine bilingue de Diali AI. Le dépôt géré par Manus reste la source canonique du projet. Le fichier `dialiweb.zip` présent avant cette copie est conservé.

## Lancer en local

Avec Python 3, depuis la racine du dépôt :

```bash
python3 -m http.server 3000
```

Puis ouvrir `http://localhost:3000`.

## Fichiers

- `index.html` : page complète et métadonnées sociales.
- `styles.css` : styles responsive.
- `script.js` : versions française et anglaise, menu mobile et calculateur indicatif.
- `assets/` : logo, illustration hero et portraits fournis pour l’équipe.
- `manus-routes.json` : manifeste de route du site.
- `dialiweb.zip` : archive déjà présente dans le dépôt, conservée sans modification.

Le site est statique et n’exige ni compte ni backend. Les polices Google Fonts et les icônes Font Awesome sont chargées depuis leurs CDN. Le calculateur présente des hypothèses de projection, pas des résultats acquis ni une offre commerciale.
