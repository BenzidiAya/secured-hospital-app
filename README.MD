#hospital-app
<h1>Compte rendu de Spring Security</h1>
<h4>L'ajout de la dépendance Spring Security dans le fichier Pom.xml</h4>

<img src="Images/4-0.png">
<p>Spring Security exige par la suite une authentification pour toutes les requêttes du serveur</p>
<h4>Spring affiche un formulaire par defaut</h4>

<p>On doit s'authentifer dans un premier lieu avec un compte par defaut en utilisant user comme login et un mot de passe générer automatiquement par Spring </p>
<img src="Images/login.png">

<h4>Interface utilisateur</h4>
<img src="Images/4-1.png">

<h4>Personnalisation de la configuration</h4>
<img src="Images/config.png">
<p>Dans cette methode(Filter) on a interdit toutes les opérations, et on a exigé l'authentification</p>

<h4>Spécification des utilisateurs qui ont le droit d'accèder à l'application</h4>
<img src="Images/useracces.png">
<p>Ici on a definit quelques utilisateurs avec des mots de passe encoder</p>

<h4>l'Ajout de Logout</h4>
<img src="Images/logout.png">

<h4>Personnalisation du formulaire d'authentification</h4>
<img src="images/checkboxlogin.png">

<h4>La gestion des autorisations</h4>
<p>Dans cette partir on a retiré aux utilisateurs normaux les droits de gestion des patient</p>
<img src="Images/4-2.png">

<h4>L'ajout de la page NotAuthorized</h4>
<img src="Images/4-3.png">

