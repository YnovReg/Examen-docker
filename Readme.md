# Examen Final Docker. 

![enter image description here](https://www.docker.com/wp-content/uploads/2022/03/horizontal-logo-monochromatic-white.png)

#### Membres du groupe n°4 :
Mouaya Anouk
Gapotih Regis
Thangarajah Tharsegan
Issaga


# Conteneurisation de l'application Web

Extrait du DockerFile :

    nano Dockerfile

![DockerFile](https://media.discordapp.net/attachments/1041632175163981887/1042023323812499517/image.png)

Docker Build

    Docker build f- Dockerfile -t ic-webapp:1.0 .

![Docker Build](https://media.discordapp.net/attachments/1041632175163981887/1042025542561583174/image.png)

Docker Run

    docker run -d --name ic-webapp -p 8080:8080 ic-webapp:1.0

![enter image description here](https://media.discordapp.net/attachments/1041632175163981887/1042026389139894303/image.png)

Docker Tag

    docker tag ic-webapp:1.0 dockreg95/ic-webapp:1.0

![enter image description here](https://media.discordapp.net/attachments/1041632175163981887/1042026723992150088/image.png)

Docker Push

    docker push dockreg95/test-ic-webapp:1.0

![enter image description here](https://media.discordapp.net/attachments/1041632175163981887/1042027798149222421/image.png)

Resultat DockerHub
![enter image description here](https://media.discordapp.net/attachments/1041632175163981887/1042028195169447936/image.png)



# Docker Registry




# Docker Compose
