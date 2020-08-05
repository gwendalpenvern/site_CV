# Site web de présentation professionnel

Site web de présentation de mon profil professionnel.

Basé sur un template de ...
Hébergé avec une Raspberry PI.
En cours de création.


base de travail pour la prise en main de git : https://www.hostinger.fr/tutoriels/commandes-git/

mise en place d'un serveur web sur une raspberry : https://raspberry-pi.fr/installer-serveur-web-raspberry-lamp/

## coté site

récupération du template et modification de celui-ci : https://webthemez.com/demo/neu-free-web-designer-profile-responsive-web-template/

## coté raspberry

````Bash
sudo apt update && sudo apt upgrade -y && sudo apt dist-upgrade -y && sudo apt autoremove -y
sudo apt install apache2
sudo chown -R pi:www-data /var/www/html/
sudo chmod -R 770 /var/www/html/
````
