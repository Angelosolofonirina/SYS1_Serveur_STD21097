# Création d'un serveur vsftpd sur Linux.

## installion:
<p>$ sudo apt update</p>
<p>$ sudo apt install vsftpd</p>

## verification :
<p>$ whereis vsftpd</p>
<p>cette commande retourne le chemin vers l'installation de vsftpd</p>
<img src="../assets/vsftpd.png">

## Lancement du serveur:
$ sudo systemctl start nginx

## verification du serveur : 
$ sudo systemctl status vsftpd

<img src="../assets/vsftpd_status.png">

## Connection aux sevreur vsftpd

$ ftp "votre address ip"

puit entre votre nom d'utilisateur et votre mot de passe local.

<img src="../assets/ftp_connection.png">