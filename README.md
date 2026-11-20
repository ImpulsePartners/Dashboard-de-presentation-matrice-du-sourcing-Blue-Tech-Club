# Dashboard de présentation – matrice du sourcing Blue Tech Club

Document confidentiel Impulse Partners, protégé par un code d'accès.

## Comment fonctionne la protection

Le contenu du dashboard (matrice, fiches, données) est chiffré en AES-256 dans `index.html`. Le code d'accès n'est stocké nulle part dans le dépôt : il sert à déchiffrer la page dans le navigateur. Sans le code, le fichier ne contient qu'un écran de saisie et un bloc de données illisibles.

- La case « Se souvenir de cet appareil pendant 30 jours » évite de retaper le code sur un ordinateur de confiance.
- Le bouton cadenas, en haut à droite du dashboard, verrouille la page et oublie le code mémorisé.

Limites : toute personne qui connaît le code peut le transmettre, et il n'y a pas de comptes individuels. Pour changer le code, il faut régénérer `index.html`, puis remplacer le fichier dans le dépôt ; l'ancien code cesse alors de fonctionner.

## Mise en ligne sur GitHub Pages

1. Déposer `index.html`, ce README et le dossier `logos/` à la racine du dépôt.
2. **Settings > Pages > Build and deployment** : source « Deploy from a branch », branche `main`, dossier `/ (root)`, puis **Save**.
3. Le site est disponible après une à deux minutes.

Le dashboard s'ouvre aussi hors connexion, par double-clic sur `index.html`, avec le même code.

## Logos

Les logos se déposent dans `logos/` sous un identifiant neutre (par exemple `logos/l-1a2b3c4d.png`), afin que le dépôt public ne révèle pas la liste des entreprises. La page « Gestion des logos » du dashboard (lien en bas de page) donne le nom à utiliser pour chaque entreprise et indique quels logos manquent.
