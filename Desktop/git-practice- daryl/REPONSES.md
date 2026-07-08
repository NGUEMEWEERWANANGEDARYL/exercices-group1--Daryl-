ETAPE 1.1
la commande git init transforme un dossier a un projet. elle cree un dossier cache nomme .git ce dossier stock tout l'historic et les sauvegarde. ces l'outile de base
apres avoir tape la commande git init , ca affiche les differents astuce tel que git config , et git branch
ETAPE 1.2
git ne consider pas README.md comme un fichier par ce que rien n'a ete ajoute au commit
ETAPE 1.3
-la commande git add prepare vos fichiers modifie et les mait dans une zone d'attente
git commit prend tous les fichiers de cette zone d'attente et crée une sauvegarde définitive dans l'historique de votre projet
- git separe git add et git commit pour laisse le choix de ceux que tu veut sauvegarde
ETAPE 1.4
-La commande git log permet d'afficher l'historique des modifications du projet. Elle liste tous les commits  du plus récent au plus ancien.  elle indique l'auteur, la date et le message de chaque sauvegarde
-avant un commit,git diff ne montre rien
ETAPE 2.1
un depot local et un dossier de votre projet dans votre ordinateur ou vous pouvais acceede sans connection internet . 
un depot distant et une version de ce meme projet hebergee sur un serveur en ligne tel que git hub
git push envoie les modification de votre code de votre ordinateur a votre compte github
ci je pert mon n'ordinateur avant de tape la commande git push mon code ne serai pas dans mon compte github
ETAPE 2.2
-Le fichier .env contient vos mots de passe secrets et cles d'API. Le versionner expose ces donnees au public
-Le dossier node_modules est trop lourd
quand je les commit les operation git push devient tres lents
ETAPE 3.1
Travailler directement sur la branche main est risque. Si ton  code contient une erreur, le projet principal sera casse. Une branche est un espace de travail isolé. Elle permet de tester de nouvelles idees sans modifier le code officiel du depot
une branche et comme un chemin parallel ou un brouillon elle part du dépôt principal et garde une copie exacte du code à un instant précis.
ETAPE 3.2
Le fichier about.html ne s'affiche pas 
non la branche main na pas change

ETAPE 4.1






