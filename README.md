# MORTEN360

Prototype de plateforme opérationnelle pour MORTEN, en un seul fichier (`index.html`).

- **Vue Opérations** (pour l'équipe) : dashboard, calendrier, shows, espace de travail par show (11 onglets), tâches en liste ou Kanban, centre de décisions, équipe, documents, finances, contacts, rapports, réglages, création de show.
- **Vue Morten** (pour l'artiste, pensée pour le téléphone) : le show du soir, les décisions qui l'attendent, son planning, ses shows et ses contacts.

Un bouton en haut permet de passer d'une vue à l'autre. Tout est cliquable : chaque lien mène à une page, les décisions, statuts de tâches, filtres et réglages fonctionnent (les données restent dans le navigateur le temps de la visite).

Les dates et lieux viennent de la liste de tournée publique de MORTEN (état au 1er octobre 2026). Les statuts, tâches, personnes, l'événement privé de Monaco et l'événement de marque à Paris sont des exemples.

## Mettre le site en ligne avec GitHub Pages

1. Sur github.com, crée un nouveau dépôt (par exemple `morten360`).
2. Clique sur **Add file > Upload files**, dépose `index.html` (et ce `README.md`), puis **Commit changes**.
3. Va dans **Settings > Pages**.
4. Sous **Build and deployment**, choisis **Deploy from a branch**, la branche `main`, le dossier `/ (root)`, puis **Save**.
5. Après une à deux minutes, le site est en ligne à `https://ton-identifiant.github.io/morten360/`.

## À savoir

- La navigation utilise des liens du type `#/ops/shows`, qui fonctionnent sur GitHub Pages sans configuration.
- Le site sera public. Une balise `noindex` demande aux moteurs de recherche de ne pas le référencer, mais toute personne qui a le lien peut l'ouvrir.
- Pour mettre à jour les données, modifie les listes `SHOWS`, `TASKS` et `DECISIONS` en haut du script.
