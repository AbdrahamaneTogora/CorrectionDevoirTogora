
1.a) git clone url
Permet de cloner le dépôt git avec l'url fournit sur la page.

1.b) git config --global  user.name "AbdrahamaneTogora"
   git config --global user.email "abdrahamanetogora450@gmail.com"
<<<<<<< HEAD
Ces deux commandes permettent de configurer mon répos avec mon nom d'utilisateur et mon email.
=======
 Ces deux commandes permettent de configurer mon répos avec mon nom d'utilisateur et mon email.
>>>>>>> feature

2.a) git checkout -b "feature"
     git checkout feature
La première commande créée une branche nommée "feature" et la seconde me permet de basculer sur cette branche.

<<<<<<< HEAD
2.b) J'ai déjà ajouter le fichier README.md en creant le dépôt sur github.
2.c) git add .
     git commit -m "Premier commit de la question 2.c en étant sur la branche feature"
La première commande me permet d'ajouter tous les fichier à mon repos ensuite la deuxième permet de faire le commit c'ets-à-dire d'envoyer les nouvelles modifications opérérées sur le repos.

3.a) git checkout main
=======
2.b) Fichier index.html crée
2.c) En faisant "git checkout feature" vers la branche feature j'ai eu comme erreur "error: Your local changes to the following files would be overwritten by checkout:
        report.md
Please commit your changes or stash them before you switch branches.
Aborting", pour résoudre le problème j'ai d'abord fait un "git stash" pour sauvegarder temporairement mes modifications, ensuite j'ai pu basculer vers ma branche feature.

2.d) Commentaire ajouter dans le fichier README.md

2.e) git add .
    git commit -m "Envoie des dernières modifications sur le dépôt en étant sur la brache feature"
    Ces deux commandes me permettent d'envoyer les dernières modifications sur le dépôt en étant sur la brache feature.
>>>>>>> feature
