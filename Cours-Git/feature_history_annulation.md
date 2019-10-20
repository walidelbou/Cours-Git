# Historique
## Ceci est un pense-bete de commandes GIT de ce chapitre :
•git log -p test.txt : visualiser les changement effectues sur ce fichier<br/>
•git log --stat test.txt : visualiser les statistiques des
modifications des fichiers, pratique pour savoir combien de ligne de code ont été
modifiées ou ajoutées sur ce fichier "test.txt"<br/>
•git log -E -i --grep='Pizza' : rechercher des logs (messages des commits) :
E expression pour rechercher les/l’occurence(s) et i pour insensible à la casse
(majuscule/minuscule)<br/>
•git diff : visualiser les modifications avant d'indexer le fichier<br/>
•git diff HEAD~1 : voir les modifications un commit en arrière<br/>
•git diff HEAD~3 HEAD : visualiser entre deux positions du HEAD<br/>
•git log f5541d6 b058c4f : Visualiser les modifications entre ces deux commits <br/>