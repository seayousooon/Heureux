# Heureux — Site web

Une première page pour fédérer des idées, projets, réalisations et procédés positifs, dans un esprit constructif.

Le cadrage du projet et le MVP sont décrits dans [README.md](./README.md).

## Fichiers

- `index.html` : page d'accueil responsive en français, styles et script intégrés.
- `readme.md` : instructions d'utilisation et de publication.
- `.nojekyll` : publication des fichiers statiques sans traitement Jekyll.

## Utilisation

Ouvrir `index.html` dans un navigateur. Aucun logiciel, dépendance ou compilation nécessaire.
Le menu filtre six thèmes. Tous restent visibles lorsque JavaScript est désactivé.

Le MVP cible la consultation de procédés classés par thèmes, la proposition de procédés et la connexion par e-mail ou Google.

La page actuelle présente ce cadrage et filtre les thèmes. Le catalogue de procédés, les comptes utilisateurs, la publication et le stockage de contributions restent à développer.
Ces fonctionnalités nécessitent un service d'authentification et un stockage adaptés ; GitHub Pages sert les fichiers statiques.

## Activer GitHub Pages

1. Ouvrir https://github.com/seayousooon/Heureux/settings/pages
2. Dans **Build and deployment**, choisir **Deploy from a branch**.
3. Choisir la branche **main**, puis le dossier **/(root)**.
4. Cliquer sur **Save**, puis attendre le déploiement et utiliser **Visit site**.

Adresse habituelle après activation : https://seayousooon.github.io/Heureux/

Le dépôt est désormais public et peut utiliser GitHub Pages avec GitHub Free.

Documentation officielle : https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Personnalisation

Modifier les textes, les thèmes et les couleurs directement dans `index.html`.
Conserver le nom `index.html` à la racine de la branche publiée.
Les modifications envoyées à la branche source sont publiées après le déploiement GitHub Pages.
