# Projet Serveur Web HTTPS - Groupe 6

## Description
Ce projet consiste à installer et configurer un serveur web **Apache sécurisé avec TLS (HTTPS)** dans un environnement Windows à l'aide de **XAMPP**. 
Un site web de test a été déployé pour vérifier le fonctionnement complet du serveur et l’affichage correct des pages via HTTPS. 
Le projet illustre la mise en place d’un serveur web sécurisé, l’activation du chiffrement TLS et le déploiement d’un site HTML avec Bootstrap.

##Veillez extraire le fichier projetSE.zip contenant tout les dossiers et fichiers nécessaires à la suite

## Membres du groupe
1.  BAMPEMBE ITUKU GABRIEL ( Auteur )
2.  NZOLO MONGA-NZOLO BENJAMIN 
3.  BAKOKO IYA ERICK 
4.  MBO GRADY 
5.  BONCOUER NAMEGABE SAFARI 
6.  SONIA 
7.  YANDOLETE YAKA BENIE 
8.  MUBWA MISOTO ALEX 
9.  MUNGUFENI ANDAMA MARC 
10. MULANGU MULANGU 

## Environnement de travail
- **Système d’exploitation** : Windows 
- **Serveur web** : Apache via XAMPP 
- **Navigateur utilisé** : Google Chrome / Microsoft Edge 
- **Framework CSS** : Bootstrap (localement)
- **Framework js** : Bootstrap (localement)
- **Dossier racine serveur** : `C:\xampp\htdocs` de XAMPP 

## Exécution
1. Copier le dossier `ProjetSE` dans `C:\xampp\htdocs` 
2. Ouvrir le **Panneau de contrôle XAMPP** 
3. Démarrer **Apache** 
4. Accéder au site via le navigateur :

https://localhost/projetSE

5. Accepter le certificat **auto-signé** si le navigateur affiche un avertissement 

## Fichiers importants
- `index.html` : page principale du site
- `css/style.css` : feille de style css du site
- `rapport.pdf` : rapport complet du projet 
- `Diapo de projet SE n°34.ppt` : présentation pour la défense
- `css/bootstrap.min.css` : fichier Bootstrap css du site
- `js/bootstrap.bundle.min.js` : fichier Bootstrap js du site
## Dossier importants
- `projetSE/` : dossier principal du site
- `projetSE/captures/` : captures d’écran d’Apache, HTTPS et du site
- `projetSE/css/` : Dossier contenat le fichier Framework bootstrap css
- `projetSE/js/` : Dossier contenat le fichier Framework bootstrap js

## Problèmes connus
- Le certificat TLS est **auto-signé**, ce qui peut générer un avertissement dans le navigateur. 
- Hors du serveur : le site etant en localhost le Framework Bootstrap devait être installer localement dans le dossier projetSE/ 

## Références
- [Apache Documentation](https://httpd.apache.org/docs/) ;
- [XAMPP Documentation](https://www.apachefriends.org/docs/) ;
- [Bootstrap Documentation](https://getbootstrap.com/) ;
- RFC 8446 - TLS 1.3 
- Kurose, J. F., Ross, K. W., *Computer Networking: A Top-Down Approach*, Pearson Education