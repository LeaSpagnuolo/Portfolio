CHERRY LINE — correctif consolidé (26 octobre 2026)

Contenu : app.js, index.html, styles.css.

Installation :
1. Décompresser le ZIP.
2. Dans le dépôt GitHub existant, remplacer uniquement app.js, index.html et styles.css par ceux-ci.
3. Garder le dossier Media/ et ses fichiers tels quels.
4. Commit/push, attendre GitHub Pages, puis faire un rechargement forcé du navigateur.

Corrections incluses dans le code :
- Tous les chemins statiques utilisent le dossier exact Media/ (M majuscule).
- Suppression de la grille décorative de la page Hero.
- Women2Women intégré depuis YouTube en 16:9.
- Interview Average Rob gardée en 9:16.
- La Conception : bloc descriptif et légende centrés.
- Sport Content 3 utilise l'embed TikTok et garde un lien de secours vers la vidéo originale.
- Les carrousels Sport/School conservent leurs médias statiques et leurs lecteurs hébergés.

Vérifications : syntaxe JavaScript et intégrité du ZIP. La lecture réelle des vidéos hébergées/locales n'a pas pu être testée dans le navigateur de production. Si un fichier .mov est encodé avec un codec non pris en charge par le navigateur, il devra être réexporté en MP4 H.264/AAC ; changer le code ne peut pas convertir son encodage.
