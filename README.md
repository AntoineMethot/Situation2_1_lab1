Partie 1: Collaboration sur un repository

1. Crée un repository sur GitHub
2. git clone pour avoir le repo localement
3. cd pour rentrer dans le repo
4. mkdir pour créer un dossier
5. echo pour créer un fichier txt avec du contenu
6. git add . pour ajouter tous les fichiers au repo
7. git commit -m pour commit les changements avec un commentaire
8. git push origin main pour synchroniser le repo local avec le repo distant sur branche main
9. git branch pour créer une nouvelle branch
10. Sur GitHub ajouter un collaborateur pour permettre Membre B de collaborer sur le repo
11. git clone pour copy le repo localement
12. git checkout pour aller dans la branch
13. mkdir pour creer un dossier
14. echo pour creer fichier text
15. Modifier le fichier text avec le navigateur
16. git add .
17. git commit -m pour  commit les changements
18. git push origin <nom_branch> pour push a la branche
19. git checkout main pour aller a branch main
20. git merge <nom_branch> pour merge les changements

capture d'écran des commit: https://imgur.com/twgWqSr 


Partie 2: Situations problématiques

Situation 1:

1. Localise le dossier existant
2. Crée un repository sur github
3. dans commandline navigue dans le dossier a l'utilisation de cd
4. une fois dans le dossier fait la commande git init
5. git add .
6. git commit "INIT REPO SITUATION 1"
7. git remote add origin https://github.com/AntoineMethot/Situation2_1_lab1.git
8. git push -u origin main
9. ajouter collaborateur Membre B au repo

Situation 2:

1. Crée un repo sur GitHub
2. git clone <URL> pour clone le repo localement
3. cd pour rentrer dans le rpo
4. mkdir pour creer dossier
5. echo pour creer fichier text
6. git add. + git commit -m + git push origin main
7. ajout collaborateur pour membre B
8. membre B git clone
9. mkdir pour creer dossier
10. echo pour creer fichier text
11. git add. + git commit -m
12. avec navigateur modifie fichier textA
13. git add. + git commit -m
14. avec navigateur modifie fichier textB
15. git add. + git commit -, + git push origin <nom_branch>
16. dans github, navige a la page issues et creer un issue avec le code du commit
17. navigue historique de version et trouve le # du commit avant que lerreur soit injectée
18. git reset --hard "#commit"
19. git push --force origin <nom_branch> pour push à la branch le dernier commit fonctionnel.

GIT CHEAT-SHEET:

- git clone [URL REPO] --- Clone la repo pour l'avoir local
- mkdir [nom dossier] --- Créer un dossier
- cd [nom dir] --- naviguer dans un dossier
- echo [text] >> [Nom fichier] --- créer un fichier
- git branch --- liste les branches du repo
- git branch [branch] --- crée une branche avec un nom
- git checkout [nom branch] --- entre dans une branche
- git add .--- ajoute les nouveau fichiers/fichiers modifié
- git commit -m --- commit les fichiers ajoutés
- git push origin [branch] --- push le commit à la repo distante
- git pull --- pull les fichiers du repo distant localement
- git merge [branch] --- merge une branche avec la branche actuelle
- git reset --hard [commit #] --- reset une branche à un commit
- git push --force origin [branch] --- force un push


ISSUES:

Une description d'un issue doit contenir le # du commit problématique et le numéro de la dernière version qui marche.




