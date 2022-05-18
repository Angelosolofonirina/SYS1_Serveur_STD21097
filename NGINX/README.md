# Création d'un serveur nginx sur Linux.

## installion:
<p>$ sudo apt update</p>
<p>$ sudo apt install nginx</p>

## verification :
<p>$ whereis nginx</p>
<p>cette commande retourne le chemin vers l'installation d'nginx</p>
<img src="../assets/nginx.png">

## Lancement du serveur:
$ sudo systemctl start nginx

## verification du serveur : 
$ sudo systemctl status nginx

<img src="../assets/nginx_status.png">

## Configurer un nouveau server

Copier le parametre suivant dans votre fichier default qui se trouve dans le dossier:
/etc/nginx/sites-enabled/

<img src="../assets/config_nginx.png">

redemarer le serveur en tapant : 
<p>$ sudo systemctl restart nginx</p>

Ouvrer votre navigateur, sur la barre d'adresse taper: localhost:8800

<img src="../assets/demo_nginx.png">