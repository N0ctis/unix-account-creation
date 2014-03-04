unix-account-creation
=====================

Here is some script I've made for creating users/groups/computer in unix.

account-creation
=====================
Exemple de script permettant d'ajouter un utilisateur, groupe, poste de travail sur Unix & Samba et d'ajouter une entrée DNS de la machine grâce aux deux derniers chiffres du nom de poste.
Le script va lire un fichier de type .csv contenant le Nom, Prenom, Groupe et PC de l'utilisateur.
Le login sera sous la forme suivante : Première lettre du nom - prénom - nombre aléatoire (0-99).
Le mot de passe est similaire au login.

Il faudra veiller à modifier la variable v_csv indiquant le chemin du fichier contenant les comptes utilisateurs à créer.

manual-account-creation
======================
Script de création d'utilisateur et groupe manuel.
