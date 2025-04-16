# Création site vitrine

## Pourquoi

## Comment

## Problèmes rencontrés

- Le fait d'utiliser Git et GitHub permet de "synchroniser" le fichier de config.json de VSCode, utile et pratique, mais surprenant quand on le découvre.

- Commit Git problématique. Une mauvaise manipulation à entrainer la création d'une branche secondaire poussant une version dépassée du projet en dernière version utilisable. Résolution plutot flou en testant des lignes de commandes, mais le problème fût finalement corrigé grâce à l'interface graphique de GitLens et GitGraph. Ces outils permettent vraiment de mieux se rendre compte du fonctionnement de git.

- Certaines animations brisent le layout de la page, je n'ai pas encore déterminer exactement laquelle, ou si c'est l'interaction de plusieurs intéractions en même temps qui sont la cause. WiP.

    - Les bordures faisant parti de son parent, elle prend de la place. Elle peut donc pousser le contenu si elle possède une taille variable. L'utilisation de outline semble recommandé, sans pour autant surcharger un document avec.

    - La meilleure solution est de contrebalancer cette bordure variable en créant directement une bordure invisible à la taille voulue. Dans le cas présent malheureusement l'élément parent possède déja des bordures il est donc requis de tricher avec une outline invisible.

## Ressources utilisées

*Syntaxe MarkDown* :

1. <https://www.markdownguide.org/cheat-sheet/>

2. <https://www.markdownguide.org/basic-syntax/>

3. <https://www.markdownguide.org/extended-syntax/>

*Idées animations* :

1. <https://prismic.io/blog/css-background-effects>

2. <https://freefrontend.com/css-animated-backgrounds/>

3. <https://www.sliderrevolution.com/resources/css-animated-background/>

*Shooting stars animation* : <https://codepen.io/nefejames/pen/PwYMqoE>

*Animations Wave CSS* : <https://codepen.io/baarbaracrr/pen/KKovmGb>

*Rotating Border Animation* : <https://codepen.io/RitikaAgrawal08/pen/qBYmYdN>

*Librairie CSS font aweomse* : <https://cdnjs.com/libraries/font-awesome>

*Fonts* :

- Akony : <https://unblast.com/download/54314/>
- Neuropol : <https://www.1001fonts.com/neuropol-font.html>

*Notions* :

Trois articles à propos des fonctions min(), max() et clamp() pour le responsive.

- <https://web.dev/articles/min-max-clamp?hl=fr>
- <https://www.lambdatest.com/blog/css-min-max-clamp-functions/>
- <https://www.marcbacon.com/understanding-clamp/>

*Flowchart quand utiliser X unités* : <https://whatunit.com/>

*Calculateur clamp* : <https://www.marcbacon.com/tools/clamp-calculator/>
