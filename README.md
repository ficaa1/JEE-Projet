# JEE-Projet
Projet JEE pour DevRep par Mamiche AIT HAMMOU et Filip BILJIC

# Pré-requis
Pour installer ce projet, il faut vérifier qu'on a un Java Runtime Environment (JRE) 1.8 et un serveur Apache Tomcat v8.5 ainsi que MySQL pour lancer la requete SQL qui va creer la base de données nécessaire

# Installation
Vous pouvez  :
 - soit importer le projet dans Eclipse EE et deployer sur Tomcat 8.5 avec Run As -> Run on Server et cliquer sur le serveur Tomcat 8.5
 - soit copier le fichier banque.war dans {repertoire d'installation}/apache-tomcat-8.5.72/webapps et ensuite lancer le serveur tomcat depuis /apache-tomcat-8.5.72/bin/startup.sh(ou bat sur windows)
Il faut ensuite lancer la requete SQL (banque.sql) sur votre serveur MySQL pour initialiser la base de donnée (username : root, password : root)

# Comment acceder et utiliser le site

Pour acceder au site, cliquez sur ce lien http://localhost:8080/banque/index
Pour commencer, entrez en tant qu'administrateur : email = admin@admin
                                                   password = admin
                                                   
Ensuite, créez votre premier compte en cliquant sur Créer un compte
Le débit maximal signifie la quantité maximum qu'on peut retirer d'un coup.
Le decouvert maximal signifie combien on peut s'endetter (valeur négative du coup)

Côté utilisateur, 
Pour créditer un compte, entrez le numéro de compte qui est affiché sur la page d'acceuil et le montant
De même pour effectuer un retrait.
Pour effectuer un virement, entrez le numéro de compte qui envoie l'argent et celui qui reçoit ainsi que le montant
