# Premier projet avec le framework Alpine.js : Codage d'une calculatrice
Date de création : 13/10/2024

## **Langage(s) de programmation utilisé(s) pour ce projet** : 
HTML5, CSS3, JavaScript

## Description du projet :
Ce projet est une calculatrice réalisée dans un fichier HTML, puis stylisée avec un fichier CSS. Cette calculatrice a pour principe de traiter et calculer les valeurs saisies par l'utilisateur grâce à des fonctions rédigées en Javascript.

## Contenu du dossier :
- Un fichier **index.html** contenant [le code source de la calculatrice](index.html) ;

- Un fichier **style.css** pour [la stylisation et la mise en forme de la calculatrice](style.css) ;

- Un dossier **pricedown** pour [l'édition de la police des éléments de la calculatrice](pricedown).

## Description du code source du projet :

**HTML5**

### **Balise _head_ du fichier [index.html](index.html) :**

- Inclusion d'une première balise _<script></script>_ pour utiliser le framework
[***Alpine.js***](alpine.dev) ;

- Inclusion d'une balise _<link>_ pour implémenter une feuille de style en **CSS**

### **Balise _body_ du fichier [index.html](index.html) :**

- Nouvelle balise _<script></script>_ pour définir les fonctionnalités de la calculatrice en **JavaScript** à travers une fonction nommée "calculator". Au sein de cette fonction, nous retrouvons des fonctionnalités pour :
    - Afficher la valeur du bouton sur lequel l'utilisateur a appuyé à l'écran ;
    - Effacer la/les valeur(s) présente(s) sur l'écran ;
    - Afficher le résultat du calcul ou un message d'erreur.

- Définition d'une _div_ contenant les éléments pour "matérialiser" la calculatrice :
    - Un _<input>_ qui fait office d'écran pour la calculatrice ;
    - Une _div_ qui regroupe tous les boutons de la calculatrice. Ces boutons ont la particularité d'effectuer une action par rapport à la fonctionnalité qui lui a été assignée.

**CSS**

- Stylisation de la calculatrice dans sa globalité avec le fichier [style.css](style.css) :
    - Nouvelle police d'écriture pour les éléments de la calculatrice (boutons, input, ...) ;
    - Une nouvelle palette de couleur pour la calculatrice et ses éléments ;
    - Une disposition plus convenable et appropriée (calculatrice placée au centre de la page, des touches bien alignées avec des dimensions adaptées, ...) ;
    - Ajout de nouvelles animations (transition de couleurs lorsque la souris passe sur les boutons).

## Roadmap du projet :
- Amélioration des fonctions pour un meilleur contrôle des valeurs saisies par l'utilisateur (par exemple) :
    - Des messages d'erreurs personnalisés en fonction de l'opérateur selectionné ;
    - Limiter le nombre d'éléments affichés sur la calculatrice, que ce soient pour le résultat du calcul ou encore la saisi de ces valeurs par l'utilisateur ;

- Ajouter de nouveaux boutons (bouton pour élever la valeur entrée au carré, ...) ;
- Essayer de rendre cette calculatrice responsive, pour un meilleur confort sur différents appareils.
