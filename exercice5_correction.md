![capture](./image/Exercice_5.png) 

- mkdir -p projet_scolaire/maths projet_scolaire/sciences : j ai creer 2 dossier dans le dossier parent d'ou l’arborescence .
- cd projet_scolaire/maths : se deplacer dans le sous dossier (maths).
- echo "x^2 + y^2 = z^2" > equations.txt : echo permet d'afficher "x^2 + y^2 = z^2" dans le nouveau fichier , creer par ">" .
- cd : direction vers le repertoire personnel.
- cd projet_scolaire/sciences : se deplacer dans le sous dossier (sciences).
- echo "eau + huile = séparation" > experiences.txt : echo permet d'afficher "eau + huile = séparation" dans le nouveau fichier , creer par ">".
- cd .. : retornez dans le dossier precedent.
- cd maths : se deplacer vers le dossier. 
- mv equations.txt geometrie.txt : j ai modifier le fichier experiences.txt par le fichier geometrie.txt .
- cd .. : retornez dans le dossier precedent.
- cd sciences : se deplacer vers le dossier.
- mv experiences.txt ../maths : j ai deplacer le fichier dans le dossier maths avec un remonte ../ .
- cd : direction vers le repertoire personnel.
- rmdir projet_scolaire/sciences : jai Supprimez le dossier sciences car il est vide avec la commande rmdir.
-  ls projet_scolaire/ : pour lister les elments du dossier projet_scolaire .