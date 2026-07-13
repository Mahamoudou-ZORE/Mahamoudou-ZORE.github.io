# Site perso — Mahamoudou ZORE (HTML pur, sans Quarto)

Aucune installation nécessaire. Ce sont des fichiers statiques prêts à l'emploi.

## 1. Avant de publier
- Ajoute une photo carrée nommée `profile.jpg` à la racine du dossier (à côté de `index.html`).
- Dans `index.html`, remplace :
  - `https://www.linkedin.com/in/REPLACE-ME` par ton lien LinkedIn
  - `https://github.com/REPLACE-ME` par ton lien GitHub
  (ou supprime la ligne `<a>` correspondante si tu ne veux pas l'afficher)

## 2. Voir le site en local
Double-clique simplement sur `index.html` — il s'ouvre dans ton navigateur, aucun serveur requis.

## 3. Publier sur GitHub Pages
1. Crée un dépôt GitHub (ex: `ton-username.github.io`, ou un dépôt classique).
2. Mets tous les fichiers de ce dossier (`index.html`, `research.html`, `styles.css`, `profile.jpg`, `CV_ZORE-Mahamoudou.pdf`) à la racine du dépôt.
3. Dans les paramètres du dépôt : Settings > Pages > Source = "Deploy from a branch" > Branch = `main`, dossier = `/ (root)`.
4. Ton site sera en ligne à `https://ton-username.github.io/` (ou `.../nom-du-depot/`).

Aucune commande, aucun build : tu peux modifier directement le texte dans `index.html` et `research.html` avec n'importe quel éditeur de texte, puis re-publier (git add / commit / push).

## Fichiers
- `index.html` — page Home
- `research.html` — page Research
- `styles.css` — style partagé par les deux pages
- `CV_ZORE-Mahamoudou.pdf` — CV téléchargeable
