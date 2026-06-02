# Dams Reprog - Site complet GitHub Pages

## Fichiers inclus
- index.html
- CNAME
- manifest.webmanifest
- apple-touch-icon.png
- icon-192.png
- icon-512.png
- README.md

## Option recommandée
Utiliser GitHub Pages pour le nouveau site principal :
damsreprog.fr

Et garder la boutique IONOS sur une page ou un sous-domaine :
boutique.damsreprog.fr
ou
damsreprog.fr/boutique si IONOS le permet encore.

## Si tu gardes IONOS pour la boutique
Ne supprime pas la boutique IONOS.
Dans le site principal, le bouton Boutique pointe vers /boutique.
Tu peux changer ce lien dans index.html si ta boutique est ailleurs.

## Déploiement GitHub Pages
1. Crée un dépôt GitHub nommé par exemple :
   damsreprog-site

2. Upload tous les fichiers du ZIP à la racine.

3. Va dans :
   Settings > Pages

4. Sélectionne :
   Deploy from branch
   Branch : main
   Folder : /root

5. Dans Custom domain, mets :
   damsreprog.fr

## DNS IONOS pour GitHub Pages
Pour le domaine principal damsreprog.fr, GitHub recommande les enregistrements A suivants :
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153

Pour www :
CNAME www -> tonpseudo.github.io

## Attention
Avant de changer le domaine principal, garde l'accès à la boutique IONOS.
Si ta boutique est actuellement sur damsreprog.fr, il faudra décider :
- soit garder IONOS en site principal,
- soit déplacer la boutique sur un sous-domaine,
- soit garder un lien externe vers la boutique.

## Liens déjà intégrés
Honda Dyno :
https://honda.damsreprog.fr

Zontes Dyno :
https://dyno.damsreprog.fr

Boutique :
/boutique

Contact :
/contact
