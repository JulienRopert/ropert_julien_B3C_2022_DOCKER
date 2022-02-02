# ropert_julien_B3C_2022_DOCKER
Projet docker 3ème année

Ce fichier explique comment utiliser le repository suivant: 
https://github.com/JulienRopert/ropert_julien_B3C_2022_DOCKER.git


## Exigences

- Installer Docker Desktop en vous rendant ici : https://www.docker.com/products/docker-desktop
- Disposer d'une connexion Internet au moment de la création de l'image.
- Créer un compte si vous n'en possedez pas sur DockerHub : https://hub.docker.com/

### Mise en place et lancement de l'application

- Ouvrir un terminal (CMD, Powershell, ou autre)
- Vérifier que vous possédez Docker Compose en effectuant la commande suivante: docker-compose -v
- Vous rendre dans le dossier contenant le fichier Docker-compose.yml
ex " cd .\Desktop\projetdocker\nom_prenom_B3C_2022_docker "
- Effectuer la commande suivante afin de monter et lancer le conteneur : docker-compose up
- Pour éteindre votre conteneur vous pouvez effectuer un CTRL-C
- Si vous avez plusieurs conteneurs a build à la suite vous pouvez faire "docker-compose up -d" en mode détaché cela vous permez de 
pouvoir build un second conteneur une fois le premier installé
- Une fois le conteneur lancé sans erreur vous rendre sur: http://localhost:3000
- Par la suite si vous n'avez pas modifier la configuration, pour lancer le conteneur vous pouvez faire un "docker-compose start"
- Pour l'arreter "docker-compose stop"
- Pour le supprimer faire "docker-compose down"   # ropert_julien_B3C_2022_DOCKER
