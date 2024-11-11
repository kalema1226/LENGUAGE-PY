
# 1. Clona el repositorio.

# Navega al directorio LENGUAJE-PYTHON en el terminal

# 2. Construye la imagen Docker ejecutando el siguiente comando:

docker build -t python-docker .


# 3.Ejecuta el contenedor:

docker run -p 8083:8083 python-docker

# Nota: La aplicación estará accesible en http://localhost:8083


