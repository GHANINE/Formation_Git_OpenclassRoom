# Formation_Git_OpenclassRoom
Formation_Git_OpenclassRoom

1. accéder à un dépôt distant
 Il va falloir tout d’abord récupérer l’URL du dépôt distant, et là cela se passe sur GitHub !
# git remote add GHM https://github.com/GHANINE/Formation_Git_OpenclassRoom.git
GHM représente le nom court que vous utiliserez ensuite pour appeler votre dépôt.

2. Clonez le dépôt en local
Maintenant que notre dépôt local pointe sur le dépôt distant, nous allons cloner son contenu et le dupliquer en local. Afin de réaliser le clonage, nous allons utiliser la commande :
# git clone  https://github.com/GHANINE/Formation_Git_OpenclassRoom.git

3. Pour connaître les branches présentes dans notre projet, il faut taper la ligne de commande :
# git branch

4. pour créer une nouvelle branche
# git branch NomDeLaNouvelleBranche

5. changer de branche
# git checkout nomDeLaBranche

6. Realiser un commit
# git commit -m “Réalisation de la partie cagnotte côté front end”   

7. supprimer une branche 
# git branch -d nomDeLaBranch
pour forcer la supperssion # git branch -D brancheTest

8. modifier le message d'un commit
# git commit --amend -m "Votre nouveau message de commit"