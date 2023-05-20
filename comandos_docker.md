| Comando | Descripción |
|---------|-------------|
| `docker --version` | Ver la versión de Docker |
| `docker run 'nombre_del_contenedor'` | Ejecutar un contenedor |
| `docker run --name 'nombre_del_contenedor'` | Ejecutar un contenedor y asignarle un nombre personalizado |
| `docker run -it 'contenedor'` | Activar el modo interactivo de Docker |
| `docker run --name 'nombre_de_contenedor' -d ubuntu` | Iniciar un contenedor de Ubuntu y evitar que se cierre |
| `docker run -d --name 'nombre_de_contenedor' -p numeroPuertoLocal:numeroDePuertoContenedor 'nombre_de_contenedor_online'` | Crear un contenedor que escuche un puerto local y en el contenedor |
| `docker logs "nombre_del_contenedor"` | Ver los logs de un contenedor |
| `docker exec -it 'nombre_de_contenedor' bash` | Ejecutar otro proceso dentro del contenedor |
| `docker stop 'CONTAINER_ID || NAMES'` | Detener un contenedor |
| `docker volume ls` | Ver los volúmenes creados por Docker |
| `docker volume create 'nombre_volumen'` | Crear un volumen |
| `docker cp 'ruta_de_archivo_o_carpeta' 'nombre_de_contenedor':'ruta_dentro_del_contenedor'` | Copiar archivos desde la PC al contenedor |
| `docker pull 'nombre_de_la_imagen':'version_de_la_imagen'` | Descargar una imagen de Docker Hub |
| `docker build -t 'nombre_de_la_imagen':'nombre_del_tag' 'directorio_con_dockerfile'` | Construir una imagen a partir de un archivo Dockerfile |
| `docker login` | Iniciar sesión en Docker Hub |
| `docker tag 'nombre_de_imagen':'tag_de_imagen' 'nombre_de_usuario_docker_hub/nombre_de_imagen':'tag_de_imagen'` | Cambiar el nombre de una imagen |
| `docker push 'nombre_de_repositorio'` | Subir una imagen a un repositorio de Docker Hub |
| `docker history 'nombre_de_imagen':'nombre_de_tag'` | Ver el historial de capas de una imagen |
| `docker rename 'nombre_de_contenedor_actual' 'nuevo_nombre_de_contenedor'` | Cambiar el nombre de un contenedor |
| `docker rm 'CONTAINER_ID || NAMES'` | Eliminar un contenedor |
| `docker network ls` | Ver las redes de Docker creadas |
| `docker network create --attachable nombre_red` | Crear una red en Docker |
| `docker network inspect nombre_red` | Ver información de una red |
| `docker network connect nombre_red nombre_contenedor` | Conectar un contenedor a una red |
| `docker-compose up` | Ejecutar las configuraciones definidas en el archivo docker-compose.yml |
| `docker-compose ps` | Ver los contenedores creados por Docker Compose |
| `docker-compose logs` | Ver los logs de todos los servicios |
| `docker-compose logs nombre_servicio` | Ver los logs de un servicio específico |
| `docker-compose exec app bash` | Ejecutar un proceso dentro de un contenedor |
| `docker-compose build` | Construir una imagen (en caso de ser necesario) |
| `docker-compose down` | Eliminar todo lo creado por Docker Compose |
