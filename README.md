1. Création de l’application Flask en local
Installez Python en exécutant sudo apt update suivi de sudo apt install python3
Installez Flask dans l'environnement virtuel avec pip install Flask
Suivez le code Flask que nous avons développé, ainsi que les dépendances nécessaires au bon fonctionnement du projet.

2. Création des différents conteneurs
Créez un Dockerfile à la racine de votre projet Flask pour construire l'image Docker. Utilisez l'image de Python comme base.
Assurez-vous d'avoir Docker installé (vous pouvez suivre les instructions officielles de Docker)
Vous pouvez construire votre image avec la commande docker build -t nom_image

Reprenez les Dockerfile que nous avons créé pour chaque application (app-python, prometheus, grafana)

3. Création du Docker Compose
Installez Docker Compose en faisant sudo apt install docker-compose
Créez un fichier docker-compose.yml à la racine de votre projet avec la configuration des services. Utilisez votre image Docker pour l'application Flask.

4. Exécution et tests du Docker Compose
Exécutez docker-compose up pour construire les images et lancer les conteneurs, vérifier que vous êtes bien à la racine du projet.
Vérifiez les logs pour vous assurer que les conteneurs ont démarré correctement.
Testez l'application Flask en allant sur http://localhost:5000/ dans un navigateur.
Effectuez des tests pour valider le bon fonctionnement de votre application.
