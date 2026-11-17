# DACPortable

Site statique prêt pour Cloudflare Pages.

## Déploiement recommandé : GitHub + Cloudflare Pages
1. Crée un dépôt GitHub, par exemple `dacportable`.
2. Mets tout le contenu de ce dossier à la racine du dépôt.
3. Dans Cloudflare : Workers & Pages > Create application > Pages > Import an existing Git repository.
4. Sélectionne le dépôt GitHub.
5. Branche de production : `main`.
6. Pour ce site HTML statique : Build command `exit 0`; Build output directory : `/` (ou laisse le répertoire racine selon l'interface proposée).
7. Lance le déploiement.
8. Cloudflare fournit une adresse `*.pages.dev`.
9. Si tu achètes un domaine, ajoute-le ensuite dans Pages > Custom domains.
10. Remplace `VOTRE-DOMAINE.fr` dans `robots.txt` et `sitemap.xml` par le domaine final.

## Amazon
Tracking ID : dacusbport-21

Les liens actuels utilisent des recherches Amazon avec le tracking ID. Quand les ASIN définitifs seront choisis, remplace-les par des liens directs vers les fiches produits.

## Avant mise en production
- Compléter les mentions légales.
- Ajouter l'identité de l'éditeur.
- Ajouter une vraie page contact si nécessaire.
- Configurer Search Console.
- Vérifier les liens affiliés et la conformité du compte Amazon Partenaires.
