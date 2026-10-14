# M203 – Gestion de données · Cours MySQL

Site statique (HTML/CSS/JS, sans build) regroupant les chapitres :

1. Tables temporaires
2. Les vues
3. Les fonctions
4. Les procédures
5. Verrouillage des tables (LOCK TABLES)
6. Structures de contrôle (IF, CASE, boucles)

## Publier sur GitHub Pages

1. Créer un dépôt GitHub (ex. `m203-mysql`) et y déposer **tout le contenu de ce dossier** (`index.html` à la racine).
2. Dans le dépôt : **Settings → Pages**.
3. *Build and deployment* → Source : **Deploy from a branch** → Branch : `main`, dossier `/ (root)` → **Save**.
4. Après 1 à 2 minutes, le site est disponible sur `https://<utilisateur>.github.io/<depot>/`.

Chaque chapitre est aussi accessible directement : `https://<utilisateur>.github.io/<depot>/#vues`.

## Structure

```
index.html          page d'accueil avec la sidebar
pages/              un fichier HTML par chapitre (utilisable seul)
.nojekyll           désactive Jekyll sur GitHub Pages
```
