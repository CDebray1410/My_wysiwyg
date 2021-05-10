## Index
1. Infos générales
2. Fonctionnalités
3. Installation
4. Utilisation
___
## 1) Infos générales
- Nom du projet : My_wysiwyg
- Statut du projet : Fini
    - Version : 1.0
- Auteurs : 
    - Christopher Debray  ( linkedin : https://www.linkedin.com/in/christopher-debray/ )
    - Floran Lebreton  ( linkedin : https://www.linkedin.com/in/floran-lebreton-84829220b/ )
- Objectif ( résumé du sujet ) :
    - Le but du projet est de créer un wysiwyg ( What you see is what you get ) , fait avec JQuery sous la forme d'un plugin.
- Compétence apprise :
    - JQuery
___
## 2) Fonctionnalités
##### Ajout d'une barre d'outils afin de modifier du texte tapé le texte peut être :
- En gras
- En italique
- Texte barré
- Différentes tailles de caractère :
    - Petite
    - Moyenne
    - Grande
- Différentes couleurs de texte :
    - Blanc
    - Noir
    - Rouge
    - Vert
    - Bleu
- Dark mode
___
## 3) Installation
Suivez bien les étapes ci-dessous !
Pour utiliser le plugins il faut : 
- Avoir relié JQuery à la page ou l'on souhaite utiliser le plugin
- Puis ensuite relier le script my_wysiwyg.js
***Pour finir il faut intégrer le code suivant dans une balise de type script :***
<pre>
    <code>
        $('textarea').my_wysiwyg({});
    </code>
</pre>
- Cela activera le my_wysiwyg sur l'élément mit entre les parenthèse, ici **textarea**, contenant les fonctions de base :
    - Texte gras
    - Texte italique
- Voici les options qu'il est possible d'activer et comment les activer :
<pre>
    <code>
        $('textarea').my_wysiwyg(
            {
                buttons: ["bold", "line-through", "italic", "font-size", "strikeThrough", "color"],
                style: "dark"
            }
        );
    </code>
</pre>
- "buttons" permet de définir les boutons affichés.
- "style : 'dark'" indique si le dark mode doit être activé ou non
___
## 4) Utilisation
**En séléctionnant ou en tapant du texte, il suffit d'appuyer sur l'un des boutons pour le modifier !**