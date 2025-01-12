# TP Messagerie en JavaScript

Ce dépôt contient une implémentation d'une messagerie simple en HTML, CSS, et JavaScript, réalisée dans le cadre d'un TP sur les technologies web.

## Fonctionnalités

- **Interface utilisateur** :
  - Une zone d'affichage des messages.
  - Une zone de saisie pour entrer du texte.
  - Un bouton pour ajouter les messages.

- **Mise en page** :
  - Une disposition en colonne centrée grâce à Flexbox.
  - Les messages alternent entre la droite et la gauche pour une meilleure lisibilité.
  - Des barres de défilement apparaissent si le contenu dépasse la zone d'affichage.

- **Comportement interactif** :
  - Ajout de messages dynamiquement à l'aide de JavaScript.
  - Modification de l'apparence du champ de saisie en JavaScript (sans toucher au CSS).
  - Gestion des classes CSS pour appliquer des styles spécifiques (droite/gauche).

## Structure du projet

- **HTML** : Définition de la structure de base de l'interface utilisateur.
- **CSS** : Mise en forme et stylisation de l'interface (classes pour le conteneur, l'affichage, le texte, etc.).
- **JavaScript** : Ajout de la logique interactive, y compris :
  - Déplacement des messages de la zone de saisie vers la zone d'affichage.
  - Alternance entre les messages à droite et à gauche.
  - Modification de l'apparence de la zone de saisie au chargement de la page.

## Instructions

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/Corentin0502/TP-Messagerie-Javascript.git
   cd TP-Messagerie-Javascript
