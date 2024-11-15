# Site web MusiqueEntrePotes

> Adresse : [Partager vos hits avec vos amis en leur laissant le choix d'écouter sur Deezer, Spotify, Apple Music ou YouTube](https://musique.entre-potes.fr/)

> Nom de code : `ZikShare` ou `ZKS`

## Présentation

Le site *MusiqueEntrePotes* permet de faire découvrir un titre musical à ses amis en créant une page listant les liens vers les principaux sites d'écoute en ligne proposant une offre gratuite (Deezer, Spotify, Apple Music,...), et pas seulement YouTube.

Ainsi, chacun clique directement sur le lien correspondant à son service de streaming pour écouter le morceau.

## Fonctionnement

Ce site utilise les APIs des fournisseurs de streaming pour rechercher le morceau souhaité dans chacun des services.
Les résultats sont ensuite agrégés pour être présentés à l'écran.

## Technologies

### Symfony

- Version `2.7.6`

### PHP

- Version `5.6.40` (via **MAMP** sur macOS : `http://zikshare/app_dev.php`)

### Base de données

- Utilise **Doctrine** via Symfony

