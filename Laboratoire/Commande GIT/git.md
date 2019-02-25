### GIT - command

-	renevir à la branch master : 
		git checkout master

-	faire retourner un fichier dans l'état du dernier commit (annuler une modification d'un fichier :
		git checkout /CHEMIN/monFichier.xml

-	Récupérer les commits qui sont sur le upstream
		git fetch upstream

-	appliquer les modifications à sa branch
		git pull upstream master

-	Créer & Changer de branche
		git checkout -b <NOM_DE_LA_NOUVELLE_BRANCHE>

Une fois le code terminer et que les tests passent !

-	ajouter le code au prochain commit
		git add <. /src monFichier ...>

-	envoyer le commit avec un message
		git commit -m "Mon message"

-	push le commit de la branch sur le repo origin github
		git push origin <NOM_DE_LA_BRANCHE>
