# Formation_Git_OpenclassRoom

# accéder à un dépôt distant
Il va falloir tout d’abord récupérer l’URL du dépôt distant, et là cela se passe sur GitHub !
"git remote add GHM https://github.com/GHANINE/Formation_Git_OpenclassRoom.git"
GHM représente le nom court que vous utiliserez ensuite pour appeler votre dépôt.
# Clonez le dépôt en local
Maintenant que notre dépôt local pointe sur le dépôt distant, nous allons cloner son contenu et le dupliquer en local. Afin de réaliser le clonage, nous allons utiliser la commande :
"git clone  https://github.com/GHANINE/Formation_Git_OpenclassRoom.git"

# Pour connaître les branches présentes dans notre projet, il faut taper la ligne de commande :
 "git branch"

# pour créer une nouvelle branche
"git branch NomDeLaNouvelleBranche"

# changer de branche
"git checkout nomDeLaBranche"

# Realiser un commit
"git commit -m “Réalisation de la partie cagnotte côté front end”  "

# Supprimer une branche 
" git branch -d nomDeLaBranch "
pour forcer la supperssion # git branch -D brancheTest

# modifier le message d'un commit
" git commit --amend -m "Votre nouveau message de commit" "

# Pour modifier le contenu d'un commit
git add fichieroublier
git commit --amend --no-edit : permet d'ajouter le fichieroublier au dernier commit
# Corrigez vos erreurs en local et à distance
La commande  git reset  est un outil complexe et polyvalent pour annuler les changements. Elle peut être appelée de trois façons différentes, qui correspondent aux arguments de ligne de commande --soft, --mixed et --hard.

# Logs
"Git log" : énumère en ordre chronologique inversé les commits réalisés
"git reflog" :va loguer les commits, mais aussi toutes les autres actions que vous avez pu faire en local
"git blame fichier.jsp" :ermet d’examiner le contenu d’un fichier ligne par ligne et de déterminer la date à laquelle chaque ligne a été modifiée, et le nom de l’auteur des modifications.:lol:

# Cherry-pick
cette commande va dupliquer des commits existants. Il sera préférable, si possible, de réaliser un merge.
"git cherry-pick d356940 de966d4"

# Git Stash
Maintenant que je suis sur ma Branch1, nous allons ajouter un fichier "File2.txt".

Finalement, je ne veux plus ajouter mon fichier sur cette branche mais sur une nouvelle branche, "BranchFile". Que dois-je faire ?

git status
git stash
git branch BranchFile
git checkout BranchFile
git status apply

# 