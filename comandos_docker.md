| Número | Comando | Ejemplo | Descripción |
| --- | --- | --- | --- |
| 1 | `docker run` | `docker run -d nginx` | Ejecuta un contenedor a partir de una imagen |
| 1.2 | `docker run` | `docker run -d myimage` | Ejecuta un contenedor en segundo plano |
| 1.3 | `docker run` | `docker run -it myimage` | Proporciona una interfaz interactiva con el contenedor |
| 1.4 | `docker run` | `docker run -p 8080:80 myimage` | Publica el puerto 80 del contenedor en el puerto 8080 del host |
| 1.5 | `docker run` | `docker run --name mycontainer myimage` | Asigna un nombre al contenedor |
| 1.6 | `docker run` | `docker run --rm myimage` | Elimina automáticamente el contenedor después de su ejecución |
| 1.7 | `docker run` | `docker run -e VAR=value myimage` | Establece una variable de entorno dentro del contenedor |
| 1.8 | `docker run` | `docker run -v /host/path:/container/path myimage` | Monta un volumen o ruta del host en el contenedor |
| 1.9 | `docker run` | `docker run --network mynetwork myimage` | Conecta el contenedor a una red específica |
| 1.10 | `docker run` | `docker run --link mycontainer:alias myimage` | Conecta el contenedor a otro contenedor y le asigna un alias |
| 2 | `docker ps` | `docker ps -a` | Muestra los contenedores en ejecución |
| 3 | `docker images` | `docker images -a` | Muestra las imágenes descargadas |
| 4 | `docker build` | `docker build -t myimage .` | Construye una imagen a partir de un Dockerfile |
| 5 | `docker start` | `docker start mycontainer` | Inicia un contenedor detenido |
| 6 | `docker stop` | `docker stop mycontainer` | Detiene un contenedor en ejecución |
| 7 | `docker rm` | `docker rm mycontainer` | Elimina un contenedor |
| 8 | `docker rmi` | `docker rmi myimage` | Elimina una imagen |
| 9 | `docker exec` | `docker exec -it mycontainer bash` | Ejecuta un comando en un contenedor en ejecución |
| 10 | `docker logs` | `docker logs mycontainer` | Muestra los registros de un contenedor |
| 11 | `docker pull` | `docker pull ubuntu` | Descarga una imagen desde un repositorio |
| 12 | `docker push` | `docker push myimage` | Sube una imagen a un repositorio |
| 13 | `docker network create` | `docker network create mynetwork` | Crea una red de contenedores |
| 14 | `docker network ls` | `docker network ls` | Muestra las redes de contenedores |
| 15 | `docker network connect` | `docker network connect mynetwork mycontainer` | Conecta un contenedor a una red |
| 16 | `docker network disconnect` | `docker network disconnect mynetwork mycontainer` | Desconecta un contenedor de una red |
| 17 | `docker volume create` | `docker volume create myvolume` | Crea un volumen para persistencia de datos |
| 18 | `docker volume ls` | `docker volume ls` | Muestra los volúmenes creados |
| 19 | `docker volume inspect` | `docker volume inspect myvolume` | Muestra información detallada de un volumen |
| 20 | `docker volume rm` | `docker volume rm myvolume` | Elimina un volumen |
| 21 | `docker-compose up` | `docker-compose up -d` | Levanta los servicios definidos en un archivo docker-compose.yml |
| 22 | `docker-compose down` | `docker-compose down` | Detiene y elimina los servicios definidos en un archivo docker-compose.yml |
| 23 | `docker-compose logs` | `docker-compose logs` | Muestra los registros de los servicios definidos en un archivo docker-compose.yml |
| 24 | `docker-compose build` | `docker-compose build` | Construye las imágenes definidas en un archivo docker-compose.yml |
| 25 | `docker-compose exec` | `docker-compose exec service_name command` | Ejecuta un comando en un servicio definido en un archivo docker-compose.yml |
| 26 | `docker inspect` | `docker inspect mycontainer` | Muestra información detallada de un contenedor |
| 27 | `docker rename` | `docker rename mycontainer newname` | Cambia el nombre de un contenedor |
| 28 | `docker update` | `docker update --cpus 2 mycontainer` | Actualiza la configuración de un contenedor en ejecución |
| 29 | `docker attach` | `docker attach mycontainer` | Adjunta una sesión al terminal de un contenedor en ejecución |
| 30 | `docker cp` | `docker cp file.txt mycontainer:/path/file.txt` | Copia archivos entre el host y un contenedor |
| 31 | `docker save` | `docker save -o myimage.tar myimage` | Guarda una imagen en un archivo tar |
| 32 | `docker load` | `docker load -i myimage.tar` | Carga una imagen desde un archivo tar |
| 33 | `docker export` | `docker export mycontainer > mycontainer.tar` | Exporta el sistema de archivos de un contenedor a un archivo tar |
| 34 | `docker import` | `docker import mycontainer.tar myimage` | Importa un sistema de archivos de un archivo tar como una nueva imagen |
| 35 | `docker top` | `docker top mycontainer` | Muestra los procesos en ejecución en un contenedor |
| 36 | `docker stats` | `docker stats` | Muestra las estadísticas de uso de recursos de los contenedores |
| 37 | `docker prune` | `docker prune` | Elimina los recursos no utilizados, como contenedores, imágenes y volúmenes |
| 38 | `docker version` | `docker version` | Muestra la versión de Docker instalada |
| 39 | `docker info` | `docker info` | Muestra información sobre la configuración de Docker y el sistema |
| 40 | `docker login` | `docker login -u username -p password` | Inicia sesión en un registro de Docker |
| 41 | `docker logout` | `docker logout` | Cierra la sesión en un registro de Docker |
| 42 | `docker attach` | `docker attach mycontainer` | Adjunta una sesión al terminal de un contenedor en ejecución |
| 43 | `docker pause` | `docker pause mycontainer` | Pausa la ejecución de un contenedor |
| 44 | `docker unpause` | `docker unpause mycontainer` | Reanuda la ejecución de un contenedor pausado |
| 45 | `docker kill` | `docker kill mycontainer` | Detiene abruptamente un contenedor en ejecución |
| 46 | `docker restart` | `docker restart mycontainer` | Reinicia un contenedor en ejecución |
| 47 | `docker logs` | `docker logs mycontainer --tail 100` | Muestra los últimos 100 registros de un contenedor |
| 48 | `docker history` | `docker history myimage` | Muestra el historial de capas de una imagen |
| 49 | `docker commit` | `docker commit mycontainer myimage` | Crea una nueva imagen a partir de los cambios realizados en un contenedor |
| 50 | `docker search` | `docker search mysql` | Busca una imagen en el registro de Docker |
| 51 | `docker system` | `docker system df` | Muestra el uso de espacio en disco de Docker |
| 52 | `docker system prune` | `docker system prune` | Limpia los recursos no utilizados, incluyendo contenedores, imágenes y volúmenes |
| 53 | `docker plugin` | `docker plugin install myplugin` | Administra complementos de Docker |
| 54 | `docker service` | `docker service create --replicas 3 myservice` | Administra servicios en Docker Swarm |
| 55 | `docker stack` | `docker stack deploy -c docker-compose.yml mystack` | Administra pilas de servicios en Docker Swarm |
| 56 | `docker swarm` | `docker swarm init` | Administra y configura un clúster de Docker Swarm |
| 57 | `docker node` | `docker node ls` | Administra nodos en Docker Swarm |
| 58 | `docker secret` | `docker secret create mysecret secret.txt` | Administra secretos en Docker Swarm |
| 59 | `docker config` | `docker config create myconfig config.txt` | Administra configuraciones en Docker Swarm |
| 60 | `docker network inspect` | `docker network inspect mynetwork` | Muestra información detallada de una red de contenedores |

