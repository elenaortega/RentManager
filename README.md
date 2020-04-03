# RentManager
## ProjetJAVA

jdk8 ainsi que Maven doivent être installés dans l'environnement de travail pour pouvoir lancer le site web.
Ensuite, pour lancer l'application web il suffit d'ouvrir un terminal sur le dossier du projet et écrire la ligne de commande "mvn clean install tomcat7:run".

Ensuite ouvrez un navigateur et accédez à localhost:8080/RentManager/home



Plein d'erreurs (liées aux Servlets) sont détectées par Eclipse sur les fichiers .jsp mais je ne réussis toujours pas à les régler.

Je suis consciente des suivants bugs:
 - Sur l'application Web:
	--> il n'est pas possible de modifier les données
	--> la section "Voitures" est inaccessible
	--> il n'est pas possible d'ajouter une réservation

 - Sur le CLI:
	--> il n'est pas possible d'afficher un client avec son ID
	--> il y a un problème avec la table VEHICULE, il n'est donc pas possible d'ajouter une voiture, en supprimer ou juste les afficher
	--> il n'est pas possible de faire de réservation, ni de les afficher ou supprimer.


Malgré tous ces "bugs", j'ai créé les fichiers qui devraient réaliser la plupart de ces fonctionnalités.
