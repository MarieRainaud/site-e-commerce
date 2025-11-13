# Projet individuel d'évaluation de cours HTML / CSS
# Création d'un site E-commerce

Ce projet a été réalisé dans le cadre de l'évaluation finale du cours de HTML/CSS.
Vous pouvez accéder au site via le lien dans About.

## Consignes :

Dans le cadre du projet que vous allez réaliser il est nécessaire que vous puissiez présenter :

Une page d'accueil, comprenant :
- Une barre de navigation fonctionnelle
- Une section "Catégories" avec quelques catégories mises en avant
- Quelques produits mis en avant

Au moins 4 pages catégories distinctes, comprenant :
- Le nom de la catégorie de produits
- Une grille de prévisualisation de produits comprenant :
- Une image du produit
- Le nom du produit
- Le prix du produit
Chaque boîte de produit doit envoyer vers une page produit

Au moins 8 pages produits distinctes, comprenant :
- Au moins 3 images du produit
- Le titre du produit
- Une description complète du produit
- Les caractéristiques du produit
- Une boîte d'achat (En stock, acheter le produit, etc.)
- Une section "Produits recommandés"

Une page Support, comprenant :
- Un formulaire de contact fonctionnel

Le site doit être responsive pour Mobile, Tablettes et Desktop.

Le site doit répondre aux critères d'accessibilités définis par le RGAA et abordés dans le cours.

Il ne doit pas y avoir de liens morts sur le site internet.

## Structure du projet
/index.html : Page d'accueil
/style.css : Feuille de styles
/support.html : Page support
/img : Toutes les photos du site

4 dossiers :
- /arbustes
- /begonias
- /iris
- /rosiers

Ces dossiers sont chacun composés de :
- index : Page catégorie
- 3 pages produits
- 9 pages pour grossir les images

## Technologies utilisées
#### HTML
#### CSS
#### JavaScript uniquement pour rendre le formulaire fonctionnel

## Fonctionnalités générales
### Accessibilité et Responsive Design

Utilisation d'unités relatives rem pour des taille de police ajustables et pouvoir utiliser le zoom jusqu'à 200%.

Contraste entre le texte et le fond.
Apparition d'un soulignement ou d'un encadrement au passage de la souris sur un lien clickable.

Suppression des styles par défaut des navigateurs (margin: 0; font-weight: normal;, etc.)

Mise en place d'une limite de taille à 1200px pour que le contenu reste lisible sur les grands écrans.
Mise en place d'une media query à partir de moins de 768px pour convenir aux tablettes et téléphones.

Mise en place d'un skip-link permettant d'aller directement au menu principal dès la première tabulation.
Alt clairs pour les images afin de faciliter la compréhenion pour les lecteurs d'écran.

Utilisation de la police Comic Neue, reconnue comme adéquate pour les personnes dyslexiques.

Création d'un mode sombre avec fond noir, texte blanc, liens soulignés qui deviennent bleus au passage de la souris.

### Structure et Mise en Page

Utilisation des conteneurs et sections logiques et organisation cohérente des éléments de la page.
Utilisation de Flexbox et Grid pour une meilleure mise en page.
Gestion des espacements (gap, padding, margin).

### Optimisation CSS

Utilisation de classes réutilisables pour éviter la redondance.
Organisation logique du code.
Utilisation de:hover, :focus, :active pour l’interactivité.

## Fonctionnalités des pages
### Page d’accueil avec navigation
#### Navigation
Création d'un menu sous forme de barre sur dekstop.
Sur mobile et tablette, hamburger permettant de dérouler le menu par dessus le contenu grâce à une checkbox.
Aria-label pour indiquer aux lecteurs d'écran où ouvrir le menu sur mobile et tablette.

#### Section catégories et produits
Utilisation de <a> pour les liens avec les pages catégories et produits.
Utilisation de grid pour créer une grille de produits.
Positionnement du texte en absolute pour qu'il s'affiche sur l'image.
Mise en place d'un background noir légérement transparent pour faciliter la lecture.

#### Footer
Création d'un footer précisant les crédits et informations personnelles.

### Pages catégories
Idem que pour la Section catégories et produits de la page d'accueil.

### Pages produits
Utilisation de Flex pour la galerie de photos pour une meilleure lisibilité sur mobile et tablette.
Création de pages qui s'ouvrent dans un nouvel onglet pour pouvoir zoomer sur les photos.
Création de barres visuelles des mois pour la floraison et la plantation, rendue inacessible aux lecteurs d'écran pour qui ça a été remplacé par un paragraphe afin d'avoir accès à l'information.
Mise en place d'un scroll horizontal pour les produits recommandés.

### Page support
Création d'un formulaire de contact fonctionnel et accessible.
Utilisation de JavaScript pour le rendre fonctionnel.

## Sources d’images 
Toutes les photographies présentes sur ce site ont été prise par moi-même.
