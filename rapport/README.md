# Dossier du Rapport de Projet (`rapport/`)

Ce dossier héberge le rapport technique et académique du projet Blog des lauréats.

## 1. Organisation modulaire
Le rapport est découpé en chapitres indépendants dans le sous-dossier `chapitres/` pour faciliter la rédaction progressive :
- `chapitres/01-introduction.md` : Contexte, objectifs et périmètre.
- `chapitres/02-conclusion.md` : Bilan des réalisations et perspectives.

## 2. Compilation automatique
Le fichier unique consolidé `rapport-blog.md` est généré automatiquement à partir des chapitres à l'aide d'un script Node.js :
- Script : `concat-chapitres.js`
- Commande directe : `node concat-chapitres.js`
- Ou via npm : `npm run build`

## 3. Guide de rédaction
- Rédiger ou modifier les chapitres dans le sous-dossier `chapitres/`.
- Chaque fichier de chapitre doit commencer par son titre de niveau 1 (`# Chapitre N : ...`).
- Lancer le script de compilation après chaque modification pour mettre à jour `rapport-blog.md`.
- Respecter les règles générales : zéro tableau Markdown, liens relatifs et français professionnel.
