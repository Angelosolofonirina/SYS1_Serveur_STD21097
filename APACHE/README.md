# Création d'un serveur apache sur Linux.

## installion:
<p>$ sudo apt update</p>
<p>$ sudo apt install apache2</p>

## verification :
<p>$ whereis apache2</p>
<p>cette commande retourne le chemin vers l'installation d'apache2</p>
<img src="../assets/apache2.png">

## Lancement du serveur:
$ sudo systemctl start apache2

## verification du serveur : 
$ sudo systemctl status apache2

<img src="../assets/apache_status.png">

Ouvrer votre navigateur, sur la barre d'adresse taper: localhost:80




