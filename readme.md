![task 1](image-1.png)
mkdir learn_git  # Cette commande crée un nouveau dossier nommé " learn_git "

![task 2](image-2.png)
cd learn_git   # cd = change directory → permet d’entrer dans le dossier "learn_git"

![task 3](image-3.png)
touch third.tx  # Crée un nouveau fichier vide nommé "third.tx"

![task 4](image-4.png)
git init   # Initialise un nouveau dépôt Git vide dans le dossier courant

![task 5](image-5.png)
 
git add third.txt   # Ajoute le fichier third.txt à la staging area

![task 6](image-6.png)
git commit -m "adding third.txt"   # Crée un commit avec le message "adding third.txt"

![task 7](image-7.png)
git log   # Affiche l’historique des commits, dont votre dernier commit

![task 8](image-8.png)
touch fourth.txt # Crée un nouveau fichier vide nommé "fourth.txt"

![task 9](image-9.png)
git add fourth.txt   # Ajoute le fichier fourth.txt à la staging area

![task 10](image-10.png)
git commit -m "adding fourth.txt"   # Crée un commit avec le message "adding fourth.txt"

![task 11](image-11.png)
git rm third.txt   # Supprime le fichier third.txt et l’ajoute à la staging area pour suppression

![task 12](image-12.png)
git add .   # Ajoute toutes les modifications (fichiers ajoutés, modifiés ou supprimés) à la staging area

![task 13](image-13.png)
git commit -m "adding fourth.txt"   # Crée un commit avec le message  "adding fourth.txt"

![task 14](image-14.png)
git log   # Affiche l’historique des commits, dont votre dernier commit

![task 15](image-15.png)
git config --global core.pager cat   # Configure Git pour afficher toute la sortie sans pagination

![task 16](image-16.png)
git config --global --list   # Affiche toutes les configurations Git globales de l’utilisateur





