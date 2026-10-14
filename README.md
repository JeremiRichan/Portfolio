# Portfolio — Jeremi Richan Tossy Ratodisoa

Site statique HTML/CSS, sans bibliothèque JavaScript, sans cookies ni outil de suivi.

## Contenu

- `index.html` : portfolio responsive en français
- `cv-systemes-reseaux-cybersecurite.pdf` : CV orienté systèmes, réseaux et cybersécurité
- `cv-developpeur-web-full-stack.pdf` : CV orienté développement web full-stack
- `favicon.svg` : icône du site
- `_headers` : en-têtes de sécurité pour les hébergeurs statiques compatibles (par exemple Cloudflare Pages et Netlify)
- `robots.txt` : autorisation d'indexation

## Mise en ligne rapide

### GitHub Pages
1. Créez un dépôt GitHub (pour un site de projet, le dépôt peut porter le nom `portfolio`).
2. Envoyez tous les fichiers de ce dossier à la racine du dépôt.
3. Dans **Settings → Pages**, sélectionnez la branche et le dossier racine, puis enregistrez.
4. Attendez la publication et testez le site sur téléphone et ordinateur.

GitHub Pages ne prend pas en charge le fichier `_headers` : les protections côté navigateur prévues dans le HTML restent actives, mais les en-têtes HTTP de ce fichier ne seront pas appliqués par cet hébergeur.

### Cloudflare Pages ou Netlify
Importez le dépôt et déployez le dossier racine. Ces plateformes peuvent appliquer le fichier `_headers`.

## Vérifications avant publication

- Ouvrir les deux CV depuis les boutons de la page.
- Tester les liens des projets, GitHub, LinkedIn, téléphone et courriel.
- Vérifier l'affichage mobile et le mode sombre.
- Lancer Lighthouse et un validateur HTML après mise en ligne.

## À personnaliser ensuite

Les liens fournis pour Scraper Facebook, PRESENCE et le scraping Python mènent au profil GitHub, car les CV ne donnent pas les URL exactes des dépôts individuels. Remplacez-les par les URL directes de chaque dépôt dès qu'elles sont confirmées. Les deux liens de démonstration sont conservés tels qu'ils apparaissent dans le CV.
