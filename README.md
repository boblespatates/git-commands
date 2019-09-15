# Git commands

## Usefull git commands

Download and install :

 * Git (https://git-scm.com/)
 * Node JS (https://nodejs.org/en/)
 * Mongo DB (https://www.mongodb.com/)

Enlever les changements non commités:
```
git checkout --.
```
Créer une branche en local:
```
git checkout -b feature/nom-de-ma-branche
```
Pousser la branche sur un dépot existant:
```
git push origin feature/nom-de-ma-branche
```
Obtenir le sha1 du commit commun entre 2 branches :
```
git merge-base [nom branche 1] [nom branche 2]
```
Squash des commits : git rebase -i [sha1 du commit commun entre les 2 branches]
```
Remplacer les mots clef "pick" par des "s" sauf pour les commits que l'on que l'on ne veut pas squasher
```
Pousser sur le dépot git :
```
git push
```
Se déplacer sur la branche sur laquelle on veut merge :
```
git checkout [ma branche]
```
Se mettre à jour :
```
git pull
```
Revenir sur la branche développée :
```
git checkout [ma branche]
```
Faire une merge request et attendre qu'elle soit validée.
Rejouter les commits sur la branche que l'on veut pousser
```
git rebase [sha1 du commit le plus récent de la branche sur laquelle on veut merge
```
Pousser le code
```
git push -f
```
