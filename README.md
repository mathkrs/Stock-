# stock

Landing page de **stock**, un logiciel simple et professionnel d'inventaire et de point de vente pour les petits commerces chiliens (almacén, boulangerie, quincaillerie, minimarket, cave à boissons, boutiques de vêtements...).

## Ce que fait stock

- **Stock en temps réel** — chaque vente enregistrée met à jour l'inventaire à l'instant, sans calcul manuel ni surprise en fin de mois.
- **Alertes intelligentes** — avertit dès qu'un produit passe sous son seuil minimum, pour ne jamais rater un réapprovisionnement ni perdre une vente.
- **Scan de codes-barres** — via la caméra du téléphone ou un lecteur USB, pour ajouter des produits et faire l'inventaire en un geste.
- **Import / export** — chargement depuis Excel ou Google Sheets (reconnaissance automatique des produits existants) et export à tout moment ; les données restent toujours à l'utilisateur.
- **Multiplateforme** — mobile et ordinateur, synchronisés en continu ; le stock peut être géré depuis le comptoir ou n'importe où.
- **Licence à vie** — paiement unique, sans abonnement mensuel, mises à jour gratuites incluses pour toujours.

## Contenu du dépôt

- `landing.html` — page marketing en un seul fichier (pas de build, pas de dépendance). Comprend :
  - Deux thèmes (sombre « slate » / clair « jour »), basculables à la volée
  - Localisation complète ES / EN / FR avec détection automatique de la langue du navigateur
  - Maquettes animées de produit et de tableau de bord (CSS/SVG pur, aucune image)

## Lancer en local

Ouvrir simplement `landing.html` dans un navigateur — site entièrement statique, aucun serveur ni build nécessaire.

## Stack

- HTML/CSS/JS natif
- Google Fonts : Space Grotesk, Sora, IBM Plex Mono

## Licence

Tous droits réservés.
