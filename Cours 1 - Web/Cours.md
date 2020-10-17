## Cours 1 - Le web
Objectifs : - Savoir ce qu’est une page web, comment est-elle générée, quels langages utiliser pour en créer une.
            - Connaître les bases des langages HTML et CSS
            - Être capable de créer un site web statique, avec ce que vous aurez appris durant le cours, avec les langages HTML et CSS.
            
Bonjour, bienvenue dans ce premier cours, destiné au web.

Dans celui-ci, nous allons voir qu’est-ce qu’une page web, comment en créer une, quels langages utiliser… vous allez également créer vos propres sites web, a travers différents challenges.

Nous allons, au fil du cours, vous donner plusieurs exercices / challenges, afin de tester vos connaissances, ainsi que voir, avec vous, ce que vous aimeriez apprendre en plus, revoir, approfondir etc.

Rappelez-vous que ce cours est pour vous, c’est donc vous qui allez le construire. N’hésitez donc pas à poser toutes vos questions / suggérer de nouvelles leçons, afin que nous faisions une leçon dessus.

<hr>

### Prérequis :

Avant de commencer le cours, vous aurez besoin d'un **IDE** (*Integrated Developement Environement*), autrement dit, un éditeur de code. Pour ce cours, nous vous conseillons **__Sublime Text__** , qui est un **IDE** simple d'utilisation, léger, fluide...

> Pour le télécharger, vous pouvez cliquer sur [ce lien](https://download.sublimetext.com/Sublime%20Text%20Build%203211%20x64%20Setup.exe) (Uniquement pour les PC sous Windows). Pour les autres système d'exploitation, vous pouvez choisir le bon programme sur [cette page](https://www.sublimetext.com/3).

Vous aurez également besoin d'activer l'extension des fichiers, dans votre explorateur de fichiers, pour cela, veuillez suivre le tutoriel suivant :
> - Ouvrez votre explorateur de fichiers
> - En haut, cliquez sur l'onglet "Affichage" puis, cochez la case "Extensions de noms de fichiers".

*Un navigateur internet sera également nécessaire.*

<hr>

### I - Introduction

Pour commencer, savez-vous comment est généré une page internet ?

On peut commencer par ouvrir notre navigateur puis, cliquer sur la touche F12 de votre clavier. (Si cela ne fonctionne pas, vous pouvez utiliser CTRL+MAJ+I).

On peut, ensuite, cliquer sur « Éléments », dans cette section, on peut observer le code **Front-End** (Tout ce qui est visuel) qui anime la page.

Vous pouvez, si vous le souhaitez, modifier / supprimer / ajouter certains éléments.

**__Attention__** : **Ceci est juste local , c’est à dire que cela n’apparaît uniquement dans votre navigateur, seulement vous pouvez-voir ces modifications. Vous n’êtes pas en train « de hacker » Google. Pour le voir par vous même, vous pouvez recharger la page, les éléments se remettent comme avant votre modification.**

<hr>

### II - Commencement

Le langage HTML est un langage de balisage et non de programmation : le code s'écrit entre des marqueurs appelés balises qui indiquent au navigateur comment interpréter ce code. La plupart des balises vont par deux : l'une ouvre un «bloc» l'autre le ferme. Mais certaines sont seules et on les dit «orphelines».

Les principales balises sont :

`<html></html>`
→ Début et fin du fichier HTML

`<title></title>`
→ Titre affiché dans l’onglet

`<head></head>`
→ En-tête avec les informations utiles

`<body></body>`
→ Début et fin du corps de votre page web.

Ainsi, je vous invite à créer un répertoire (sur votre bureau, par exemple), dans le quel vous allez apprendre à coder. Dans celui-ci, vous pouvez créer un fichier appelé **index.html** et l’ouvrir avec Sublime Text puis, y rentrer le code suivant :

```html
<html>
  <head>
    <title>Ma page</title>
  </head>
  <body>
    <p>Hello world !</p>
  </body>
</html>
```

**Félicitations !** Vous venez de créer votre première page web ! Vous pouvez enregistrer le fichier avec `CTRL+S` puis, retourner dans l'explorateur de fichiers, faire un clic drooit sur votre fichier et, cliquer sur Ouvrir avec puis, choisissez votre navigateur internet.
