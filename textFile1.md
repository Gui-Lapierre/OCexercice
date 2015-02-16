#Open Classroom exercice: Git & GitHub - Partie 3 Activité

Expliquez les points suivants : 
1. Qu'est-ce qu'un commit?
2. À quoi sert la commande git log?
3. Qu'est-ce qu'une branche?


### 1) Qu'est-ce qu'un commit?

Lorsqu'on travaille sur une application dont le versionning est géré par GIT, chaque fichier a un *état* de commit :
- en cours de modification et non commité
- commité

Lorsqu'on fait une modification du code, elle n'est pas commité, elle est à l'état *brouillon*.
Lorsque la modification est corretement codée et est prête à être homologuée dans l'application, on fait un *commit*. Ceci revient à dire à GIT que la modification est terminée et qu'il peut l'intégrer à la version finale de l'application.
Un commit s'accompagne toujours d'un commentaire, pour simplifier l'historique des modifications.


### 2) À quoi sert la commande git log?

Cette commande permet de consulter tous l'historique des commit effectués sur un fichier donné.
Pour chaque commit, la commande log nous montre:
- la date
- l'auteur
- les modificatinos effectuées


### 3) Qu'est-ce qu'une branche?

Une branche est un ensemble de code dans une version donnée.
Cela veut dire que le code d'une branche est **cohérent**, que toutes ses modifications fonctionnent correctement ensemble.
Pour une application donnée, il peut exister plusieurs branches. Chacune contiendra des différences.
Par convention, on créé une nouvelle branche par nouveau besoin fonctionnel, dans le cas où on ne veut pas travailler directement sur la branche principale.
Le but de la création d'une nouvelle branche est d'organiser le code durant les développement. Cela permet de simplifier la gestion des différents développements en cours. Mais ça permet également de pouvoir modifier rapidement l'application principale.

A terme, le code d'une application finie ne devrait comporter qu'une seule branche.
