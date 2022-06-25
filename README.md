<style>.cent {  display: block;  margin-left: auto;  margin-right: auto;}</style>

Ce document a pour objectif d'expliquer le fonctionnement de Git pour les ateliers du CREPP.<br>
Un répertoire Git a été créé pour centraliser les supports des ateliers ainsi que les codes et projets produits depuis la création du CREPP en 2012.<br>
Il est donc en perpétuelle amélioration.<br>
<h3>Localisation</h3>
Le répertoire est disponible à l'adresse suivante : <a class="alert-link">https://github.com/CREPP-PLOEMEUR</a> ou bien en passant sur
 le site du CREPP, dans la section <b>Ressources GIT</b>
 
<figure id=''><div class='cent' style='text-align:center;'><img src='localisation.png' style='max-width:50%;'><figcaption>Figure 1 - Accès aux ressources GIT</figcaption></div></figure>

<h3>Menu principal</h3>

Une fois le lien cliqué, vous tombez directement sur cette interface <br>

<figure id=''><div class='cent' style='text-align:center;'><img src='git_home.png' style='max-width:35%;'><figcaption>Figure 2 - La page principale du répertoire Git</figcaption></div></figure>

Les répertoires facilement accessibles sont :<br>
<ul>
    <li> Le répertoire <b>Supports PDF</b> regroupe les supports PDf utilisés pour les Ateliers Arduino et Microcontrôleurs.</li>
    <li> Le répertoire <b>Codes Arduino</b> est une compilation des codes Arduino utilisés lors des ateliers.</li>
    <li> Le répertoire <b>Codes ESP12</b> est une compilation des codes ESP12 des ateliers.</li>
</ul>
Sous ces trois répertoires, vous avez accès à l'ensemble des répertoires du CREPP. Pour afficher tous les répertoires, vous pouvez cliquer <br>
sur <b>View all repositories</b> en bas de la page.

<figure id=''><div class='cent' style='text-align:center;'><img src='view.png' style='max-width:45%;'><figcaption>Figure 3 - Afficher l'ensemble des répertoires</figcaption></div></figure>
Il est possible de classer les répertoires en cliquant sur <b>Sort</b> et de les classer en fonction de :
<ul>
    <li> Les dates de modifications<br></li>
    <li> Les noms<br></li>
</ul>
<figure id=''><div class='cent' style='text-align:center;'><img src='sort.png' style='max-width:45%;'><figcaption>Figure 4 - Trier les répertoires</figcaption></div></figure>
Actuellement, voici les répertoires : <br>
<ul>
<li> codes Arduino<br></li>
<li> Codes ESP12<br></li>
<li> Codes Pico<br></li>
<li> Projets Ateliers\_Jeunes<br></li>
<li> Projet Capteur pollution\_atmospherique<br></li>
<li> Projet Cocci-Bot<br></li>
<li> Projet Crepp-Rap<br></li>
<li> Projet Fauteuil roulant<br></li>
<li> Projet MySensors<br></li>
<li> Projet Pot Qui pense<br></li>
<li> Projet Raspi-Bot<br></li>
<li> Projet SimpleCDBot<br></li>
<li> Projet Ventilateur<br></li>
<li> Supports PDF <br></li>
</ul>
<h3>Exploration d'un répertoire</h3>
<h4>L'arborescence</h4>
En cliquant sur un répertoire, l'arborescence de ce dernier apparaît avec le premier rang des dossiers et les fichiers sur le même niveau.<br>
En cliquant sur les noms des dossiers, on peut parcourir l'arborescence du répertoire complet.<br>
<figure id=''><div class='cent' style='text-align:center;'><img src='main.png' style='max-width:30%;'><figcaption>Figure 5 - L'arborescence du répertoire</figcaption></div></figure>


Une description du répertoire est disponible avec un fichier README.md. (ici le répertoire Codes Arduino)<br>

<figure id=''><div class='cent' style='text-align:center;'><img src='readme.png' style='max-width:35%;'><figcaption>Figure 6 - Une description du répertoire</figcaption></div></figure>
Les principaux langages utilisés dans le répertoires sont indiqués à droite de la section <b>README</b>.
<h4>Récupération d'un fichier</h4>
<h4>Un fichier contenant du code</h4>
Pour récupérer le contenu  d'un fichier particulier, il faut parcourir l'arborescence pour le trouver.<br>
Une fois le fichier localisé, il faut cliquer sur le fichier afin de voir son contenu : <br>
<figure id=''><div class='cent' style='text-align:center;'><img src='content.png' style='max-width:35%;'><figcaption>Figure 7 - Un contenu de fichier</figcaption></div></figure>
Enfin, il ne reste plus qu'à cliquer sur <b>Copy raw contents</b>
pour copier tout le texte du fichier dans le presse-papier.<br>
<figure id=''><div class='cent' style='text-align:center;'><img src='raw.png' style='max-width:60%;'><figcaption>Figure 8 - Copier le contenu d'un fichier</figcaption></div></figure>
<h4>Un fichier PDF</h4>
Pour récupérer le fichier PDF, après l'avoir localisé, il suffit de cliquer sur le bouton <b>Download</b>.
<figure id=''><div class='cent' style='text-align:center;'><img src='download_pdf.png' style='max-width:35%;'><figcaption>Figure 9 - Téléchargement d'un fichier PDF</figcaption></div></figure>
<div class='alert alert-warning' ><h4>Remarque</h4>Cette méthode est contraignante quand nous sommes ammenés à manipuler plusieurs fichiers au sein d'un même répertoire. La méthode suivante va vous expliquer comment télécharger directement tout un répertoire pour travailler par la suite en local.</div>
<h3>Téléchargement d'un répertoire</h3>
Pour télécharger un répertoire dans son intégralité, il faut tout d'abord se placer à la racine de celui-ci en cliquant sur le <br>
nom du répertoire (Codes\_Arduino):<br>
<figure id=''><div class='cent' style='text-align:center;'><img src='name.png' style='max-width:35%;'><figcaption>Figure 10 - Déplacement à la racine du répertoire</figcaption></div></figure>
Ensuite, il faut cliquer sur le bouton vert <span class='badge badge-light'>Code</span> pour dérouler un petit menu puis cliquer sur <b>Download ZIP</b>
<figure id=''><div class='cent' style='text-align:center;'><img src='zip.png' style='max-width:50%;'><figcaption>Figure 11 - Téléchargement du répertoire</figcaption></div></figure>
Le répertoire va se télécharger au format ZIP dans vos téléchargements avec le suffixe <b>-master</b>. 
Par exemple, le répertoire <b>Codes Arduino</b> sera téléchargé sous le nom <b>Codes Arduino-master.zip</b>.
Il ne vous reste plus qu'à extraire le fichier pour explorer le répertoire.<br>

</body></html>
