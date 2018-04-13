Comment lancer l'application Java ProxiBanqueSI_V2

Pré-requis:
	    - Installer le JDK 8 (ou superieur) sur la machine cible.

            - Installer Wampserver 3.0.6 sur la machine cible.
		
			(Téléchargé depuis: http://www.wampserver.com/).

	    - Installer Tomcat 9 sur la machine cible, 

		    (Téléchargé depuis: https://tomcat.apache.org/download-90.cgil).

		    (Téléchargé depuis: http://www.oracle.com/technetwork/java/javase/downloads/index.html).

	    - Machine cible dote d'un systeme d'exploitation Windows.
		
		- installer la base de donnés grace au script du fichier database.sql

Execution :
		- lancer le fichier startup.bat dans apache-tomcat-9.0.6\apache-tomcat-9.0.6\bin
		
	    - Copier le fichier .WAR  dans le repertoire : apache-tomcat-9.0.6\apache-tomcat-9.0.6\webapps

Consulter la documentation: 
	    - Double-cliquer sur le fichier index.html se trouvant dans le repertoire doc de l'application


Utilisation de l'application:
		- au lancement une page d'accueil
		- si mauvais mot de passe et ou login => page erreur
		- pour ce connecter il faut 
			=> login : toto
			=> password : 123
		- connection et direction la liste de ce conseiller
		- il est possible de créer, modifer et supprimer une client
		- il est possible de créer des comptes en allant la liste de compte du client

