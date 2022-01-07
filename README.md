# BAREL_HENRY_ZOUACHE_projet-tuteuré-

Technologies utilisées : HTML/CSS, PHP, javascript et le web socket socket.io

 	
Bilan : Projet PHP entièrement fonctionnel, projet tuteuré incomplet, ils nous manquent la gestion de l'affichage pour le host (tout le monde peut répondre aux questions, sans distinctions entre les joueurs),il y a un manque de sécurité (les informations s'affichent dans l'url).

différentes taches effectuées : 
<br />Antoine : _Page admin (Nombre d'utlisateur et Nombre de question)
<br />_Gestion des questions/réponses (Supprimer/modifier/afficher)
<br />Gestion des Utilisateurs (Supprimer/modifier/afficher)
<br />_Envoie de mail (par sendmail)
<br />_Gestion des utilisateurs (Websocket)
<br />Julian : _Creation fichier sql
<br />_système de connexion
<br />_Ajout option Role_User ou bien Role_Admin dans modifier utilisateur
<br />_Ajout choix entre unequestion à 1 réponse ou 4 réponses dans modifier la question
<br />_Choisir une question par niveau 
<br />_Afficher/gestion des question et réponses
<br />Selim : _Système d'inscription et de connexion
<br />_Partie graphique du projet 
<br />_Afficher les règles du jeu 
<br />_Système de déconnexion 
<br />_Affichage grille de jeu(en fonction du nombre de joueur) 
<br />_gestion des couleurs


manuel d'installation : le sendmail est déjà réglé pour l'envoie de mail par une adresse gmail, pour modifier l'envoie de l'adresse(si l'on envoie par adresse hotmail ou outlook par exemple, il faut modifier la valeur de smtp_server, pour changer l'adresse mail qui envoie les urls, il faut modifier auth_username et auth_password. 
<br />Sur le serveur wamp, dans bin\apache\apache2.4.51\bin dans le fichier php.ini il faut mettre en commentaire à partir de [mail function] jusqu'à sendmail_path où il faut mettre : "\"C:\wamp64\sendmail\sendmail.exe\" -t"(on vous transmet le fichier php.ini à la racine du projet si besoin).
Si le mail qui reçoit l'url est un gmail, il faudra activé l'accès moins sécurisé des applications qui se trouve dans sécurité dans paramètres. 

information de connexion pour le compte admin :
<br />nom d'utilisateur : admin 
<br />mot de passe : admin 
<br />nom du virtualhost : projet 
