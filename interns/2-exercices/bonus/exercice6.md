### Exercice 6

**PS : Avec le jargon technique**

#### Partie 1

1. Créer un nouveau dossier
2. Initialisez un dépôt git
3. Ajoutez le lien de votre dépôt distant Github
4. Créez un fichier .gitignore dont le contenu doit exclure le sous-dossiers img (sera crée ci-après)
5. Faites votre premier commit
6. Renommez le nom de la branche master en main 
7. Créez et (dé)placez-vous dans une branche nommée ex6/part1-3
8. Créez un sous-dossier img
9. Ajouter le fichier .gitkeep dans img
10. Commitez

### Partie 2

1. Créez le fichier README.md dont le contenu correspond à l’énoncé de cet exercice de la partie 1 à la 3
2. Faites une capture d’écran de l’état de votre dépôt et enregistrez le fichier dans le sous-dossier img
3. Commitez votre travail en respectant les bonnes pratiques de commit [voir l'annexe partie commits](./../annexe.md) 
4. Faites à nouveau une capture d’écran de votre dépôt et enregistrez le fichier dans le sous-dossier img
5. Retirez la ligne contenant img dans le .gitignore

### Partie 3

1. Commitez votre travail sans écrire un nouveau message de commit ou en modifiant le message du commit précédent

##### Aide

1. commiter sans modifier le dernier message de commit : `git commit --amend --no-edit`
2. Commiter en modifiant le dernier message de commit (sans en créer un nouveau) : `git commit --amend`
- Votre éditeur (celui configuré à l'installation) s'ouvre et vous pouvez éditer votre message puis enregistrer
###### Cas particulier éditeur VIM

1. Tapez la lettre `i` pour passer en mode édition, tapez la lettre `i`
2. Modifier votre message de commit
3. Tapez sur le bouton `Echap` pour quitter le mode d'édition
4. Tapez sur `:x` pour enregistrer les modification et quitter l'éditeur

#### Partie 4

1. Fusionnez la branche ex6/part1-3 dans la branche main
2. Créez une nouvelle branche ex6/part4 à partir de la branche main
3. Modifiez le fichier README.md en ajoutant le contenu de l’énoncé actuel (Partie 4)
4. Commitez votre travail en respectant les bonnes pratiques
5. Fusionnez la branche ex6/part1-4 dans la branche main
6. Envoyez toutes vos modifications (branches ex6/part1-3, ex6/part4 et main) vers votre dépôt distant Github


### Partie 5

Depuis votre compte GitHub, à partir du dépôt où vous avez envoyé précédemment votre travail
1. Créez une nouvelle branche ex6/part5 à partir de la branche main
2. Modifiez le fichier README.md en ajoutant le contenu de l’énoncé actuel (Partie 5)
3. Commitez votre travail en respectant les bonnes pratiques

En local

4. Récupérez les modifications du dépôt distant (aide commande à effectuer `git checkout -b ex6/part5 --track orgin/ex6/part5`)
5. Fusionnez la branche ex6/part5 dans la branche main

### Partie 6

1. Créez une nouvelle branche nommée ex6/part6 à partir de la branche main
2. Modifiez le fichier README.md en ajoutant l’énoncé actuel (Partie 6)
3. Mettez votre travail de côté (aide commande à effectuer `git stash`)

### Partie 7

1. Créez une nouvelle branche nommée ex6/part7 à partir de votre branche main
2. Modifiez le fichier README.md en ajoutez l’énoncé actuel (Partie 7)
3. Commitez votre travail en respectant les bonnes pratiques
4. Basculez sur la branche ex6/part6
5. Récupérez le travail mis de côté (`git stash apply`) et commitez
6. Fusionnez la branche ex6/part6 dans votre branche ex6/part7
7. Résolvez le conflit
8. Fusionnez la branche ex6/part7 dans la branche main
9. Ajoutez une version(tag) au dernier commit (`git tag v1.0.0`)
10. Analisez l'état de votre dépot à l'aide de la commande `git log`
11. Envoyez vers votre dépôt distant Github toutes vos branches locales
12. En local, supprimez toutes les branches sauf la branche main (pour supprimer une branche `git branch -d nom_de_la_branche_a_supprimer`)


