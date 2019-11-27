http://vibitas.eu.pythonanywhere.com/timeline

## PythonAnywhere.com
PythonAnywhere est un service qui permet de faire tourner des programmes en Python sur des serveurs "dans le cloud"
Il propose d'héberger les applications Pythons avec leurs extensions et composants inclus. Il utilise les infrastructures d'Amazon EC2. Le site supporte la majorité des modules Python & offre des consoles de commande et éditeur de code intégrée à même l'interface Web.
Pour les bases de données, il supporte DB MySql - PostgreSql - sqlite3

## Flask
Flask est un micro-framework crée en Python.
Il propose une application basique, avec des routes et des moteurs de templates.
Complètement personnalisable pour créer des applications web avec plusieurs extensions.
Ne met pas en place de base de données par défaut
Flask permet de gérer les cookies, sessions et met en place un serveur de développement et des controlleurs.

*Sites utilisant Flask :*
http://www.dota2protracker.com/
https://skylines.aero/
https://flaskbb.org/
https://www.linkedin.com/
http://le-test-ultime.hello-birds.com/

## Quelles étapes avez-vous suivi ?
j'ai essayé d'uploader le repo sur le serveur PythonAnywhere depuis le bash PythonAnywhere & depuis ma console

## Quelles difficultés avez-vous rencontré ?
Hébergement de mon repo sur PythonAnywhere
j'ai essayé depuis le bash pythonanywhere & depuis mon terminal, mais je n'ai pas réussi.

## Quels sont, selon vous, les aspects techniques limitants du projet FLGAZ dans l'état initial ?
Le projet initial manipule les données recueillis à la volée, ne stocke pas catégoriquement les informations.

## Quelles sont, selon vous, les menaces auxquelles un tel projet peut être soumis ?
Sur le long terme, ça ne sera pas propre et on cours le risque de perdre ou de désordonner les informations.
Prise en main facile des données par un individu externe

###### (Explication du code)
Définition de 3 routes :
  - / : racine
affichage message “Bienvenue”

  - /gaz : formulaire d’entrée
Prend en paramètre nom & message
clic sur envoyer
ajoute le contenu dans le fichier gazouilles.csv

  - /timeline : affichage du contenu de gazouilles.csv
stockage du fichier csv dans un tableau
  -> définit de mettre sur la premiere ligne, le pseudo & sur la deuxieme ligne, le message

Moteurs de templates :
  - formulaire
  - tableau récupérant les données cvs et les nouvelles données
