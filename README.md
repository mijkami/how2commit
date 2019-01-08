___________________

# update applications  
	$ sudo get-apt update

___________________

# git copier repo github spécifique  
	$ git clone https://github.com/nom_user/nom_de_repo/

___________________


# exemple github kikoo :
#* créer dossier /kikoo, explorer fichier actuel, entrer dans /kikoo  
	$ mkdir kikoo  
	$ ls  
	$ cd kikoo
	


#* créer fichier kikoo.txt  
#* ouvrir kikoo.txt dans éditeur de texte  
	touch kikoo.txt  
	xdg-open kikoo.txt

#* ou : ouvrir kikoo.txt dans sublime (éditeur amélioré),  
#* et créer le fichier si il n'existe pas  
	$ subl kikoo.txt

#* Vérifier statut git et comparaison fichiers récents vs git local  
	$ git status

#* ajouter/mettre à jour version de kikoo.txt  
	$ git add kikoo.txt

#* re-vérifier si besoin le statut pour vérifier la modification  
	$ git status

#* si besoin vérifier l'historique des modifications  
	$ git log

#* faire un "commit" prennant en compte tous les ajouts récents d'un bloc,  
#* avec -m "commentaire décrivant le commit"  
	$ git commit -m "Ajout de kikoo.txt"

#* push le tout en ligne  
	$ git push origin master

___________________
