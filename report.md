
1.a) git clone url
Permet de cloner le dépôt git avec l'url fournit sur la page.

1.b) git config --global  user.name "AbdrahamaneTogora"
   git config --global user.email "abdrahamanetogora450@gmail.com"
 Ces deux commandes permettent de configurer mon répos avec mon nom d'utilisateur et mon email.

2.a) git checkout -b "feature"
     git checkout feature
La première commande créée une branche nommée "feature" et la seconde me permet de basculer sur cette branche.

2.b) Fichier index.html crée
2.c) En faisant "git checkout feature" vers la branche feature j'ai eu comme erreur "error: Your local changes to the following files would be overwritten by checkout:
        report.md
Please commit your changes or stash them before you switch branches.
Aborting", pour résoudre le problème j'ai d'abord fait un "git stash" pour sauvegarder temporairement mes modifications, ensuite j'ai pu basculer vers ma branche feature.

2.d) Commentaire ajouter dans le fichier README.md

2.e) git add .
    git commit -m "Envoie des dernières modifications sur le dépôt en étant sur la brache feature"
    Ces deux commandes me permettent d'envoyer les dernières modifications sur le dépôt en étant sur la brache feature.