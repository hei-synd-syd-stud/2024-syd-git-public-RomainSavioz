# Answers of Romain Savioz github-RomainSavioz

## Basics

### Task 1

Il y a un fichier .md qui est le document sur lequel on écrit actuellement. Il y a dans ce document une image répertoriée dans le dossier img et pour finir dans le dossier .git. Il s'agit du répertoire ou l'on va retrouver l'historique des commits, branches et tags,...

### Task 2

Dans Sublime Merge il y a un nouvel onglet qui s'appelle Untracked Files (1) cela signifie qu'il a été detecté mais pour l'instant on ne l'a pas encore indiqué comme important alors il prend ce nom la de base
Le log--online nous donne le dernier commit qui a était fait.

### Task 3

Maintenant le ficher README a été stage et il est donc affiché comme tel et on peut maintenant avoir accès aux modifications. Il est en attente d'être commit

### Task 4

Toutes les modifications du fichier README a été commit donc il est sauvegardé

### Task 5

Pour la chaine de charactère, ill s'agit de  l'identifiant unique pour identifier de manière précise le commit. Il s'agit du dernier commit effectué.
HEAD me dit sur quel commit vous êtes "branché" actuellement.

MAIN correspond au nom de la branche sur laquelle je me trouve actuellement.

Pour ce qui vient après : `ADD: README file.`. Cela représente le **message de commit** que j'ai fourni lorsque j'ai effectué ce commit. Le message de commit décrit les modifications apportées dans ce commit...

### Task 6

Lorsqu'on réouvre le dossier le fichier README a disparu car je suis revenu au dossier de base. Lorsque je viens au dernier commit, si je réouvre le dossier je retrouve à nouveau mon fichier README

## Gitgraph

### Task 7

1) develop correspond à une autre branche du Master(Main)

2) C'est le hash du commit. Il est utilisé comme identifiant.

3)  Cela indique que feature-auth a été fusionné avec la branche develop

4)  Cela représente l'auteur du commit

5)  Cela montre la version actuel du main

6) Cela merge de feature-auth depuis main

7) checkout de feature depuis main

8) merge de develop depuis main

9) checkout de develop depuis main

10) état du repostory avant modification (initial commit)

![Gitgraph](img/gitgraph.svg)