# Drame Sow — Gestion Boutique

Application web statique pour une boutique de lait caillé.

## Mise en ligne avec GitHub Pages
1. Créez un dépôt GitHub public nommé `drame-sow`.
2. Ajoutez `index.html` à la racine du dépôt.
3. Ouvrez Settings → Pages.
4. Dans Build and deployment, choisissez Deploy from a branch.
5. Choisissez `main` et `/ (root)`, puis Save.
6. Ouvrez l'adresse GitHub Pages affichée par GitHub.

## Données
- Les données sont enregistrées dans le navigateur/appareil (localStorage).
- Utilisez Exporter régulièrement pour créer une sauvegarde JSON.
- Pour transférer vers un autre appareil, ouvrez l'application sur l'autre appareil puis Importer la sauvegarde.
- GitHub Pages héberge l'application mais ne synchronise pas automatiquement les données entre appareils.

## Personnalisation
Les catégories de dépenses initiales sont définies au début du script dans `EXPENSE_DEFAULTS`.
Les produits de vente peuvent être ajoutés depuis l'onglet Stock.
