### Récap commandes Git

1.	Configuration minimale : nom, prénom et adresse e-mail
`git config –global user.name ‘Glodie Tshimini’`
`git config –global user.name ‘contact@tshimini.fr’`
2.	Initialiser un dépôt git ou cloner un dépôt distant en local
- `git init`
- `git remote add origin [url_du_depot_distant]`
Ou 
- `git clone [url_du_depot_distant]`
3. Premier commit
`git commit -m ‘initial commit’`
4. Renommer une branche
Pattern (motif, modèle) : `git branch -m oldname newname`
Exemple pour le renommage de la branche master en main : `git branch -m master main`
5. Créer une branche (on ne peut pas créer une nouvelle branche tant qu'il n'y a pas au moins un commit sur le dépôt)
`git branch -b newBranch`
6. Se déplacer dans une branche pour y travailler sur une nouvelle version de son projet
`git checkout newBranche`
7. Créer et se déplacer dans la branche pour y travailler sur une nouvelle version du projet
`git checkout -b newBranch`
8. Ajouter un fichier dans l’index
Git add fichier.txt
9. Ajouter un commit
`git commit -m ‘add new file’`
10.	Envoyer les modifications en ligne (local vers GitHub)
`git push origin main`
11.	Récupérer les modifications depuis le dépôt distant (GitHub vers local)
`git pull origin main`
12.	Récupérer les modifications sans fusionner (par exemple récupérer les branches crées sur Github)
`git fetch`
13.	Fusionner 2 branches A et B (ci-après B est la branche source et A la branche de reception, toujours se positionner d'abord dans la branche de réception avant de faire la fusion)
- `git checkout A`
- `Git merge B`
14.	Voir l’état du dépôt
`git status`
15.	 Voir l’historique des commits
`git log`

16. Différence entre 2 commits
`git diff idCommmit1 idCommit2`
