# Test + des commandes de base 

ajout de fichier : git add Fichier... (+ git commit)

supprimer fichier : git rm Fichier... (+git commit)

deplacer ou renommer fichier : git mv source... destination (+git commit)
NB: en réalité enregistrer comme ajout suivi d'une supression

voir les renommage ::
	git bg --sommary
	git log --summary -M

fichier .gitignore = Parfois on a des fichiers qu'on ne souhaite pas enregistrer
ex :    *.class
	*.o
	*~
	fichier-secret
--> On peut les lister dans un fichier nommé .gitignore
NB::Le .gitignore est lui normalement enregistrer

Mettre du travail de coté : 
ex gros bug sa mere faut le corriger a tout pris et laisser béton le taf actuel
git stash
pour revoir se qu'on a mi : git stash show
pour repondre : git stash pop
pour supprimer : git stash drop
git stash list