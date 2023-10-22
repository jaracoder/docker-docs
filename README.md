# Documentación de Docker

### Comandos Básicos de Docker

- **`docker --version`**: Verificar la versión de Docker instalada.

- **`docker run <imagen>`**: Ejecutar un contenedor a partir de una imagen.

- **`docker pull <imagen>`**: Descargar una imagen desde Docker Hub u otro registro.

- **`docker ps`**: Listar contenedores en ejecución.

- **`docker ps -a`**: Listar todos los contenedores (incluso los detenidos).

- **`docker stop <contenedor>`**: Detener un contenedor en ejecución.

- **`docker start <contenedor>`**: Iniciar un contenedor detenido.

- **`docker restart <contenedor>`**: Reiniciar un contenedor.

- **`docker logs <contenedor>`**: Ver los registros (logs) de un contenedor.

- **`docker exec -it <contenedor> <comando>`**: Ejecutar un comando dentro de un contenedor en ejecución.

- **`docker build -t <nombre>:<etiqueta> <ruta>`**: Construir una imagen a partir de un archivo Dockerfile.

- **`docker images`**: Listar las imágenes disponibles en el sistema.

- **`docker rmi <imagen>`**: Eliminar una imagen.

- **`docker rm <contenedor>`**: Eliminar un contenedor.

- **`docker network ls`**: Listar las redes de Docker.

- **`docker volume ls`**: Listar los volúmenes de Docker.

- **`docker-compose up`**: Iniciar servicios definidos en un archivo `docker-compose.yml`.

- **`docker-compose down`**: Detener y eliminar servicios definidos en un archivo `docker-compose.yml`.

- **`docker system prune`**: Eliminar recursos no utilizados (contenedores, imágenes, volúmenes, redes, etc.).

- **`docker info`**: Mostrar información detallada del sistema Docker.

- **`docker --help`**: Obtener ayuda y ver todos los comandos disponibles.
