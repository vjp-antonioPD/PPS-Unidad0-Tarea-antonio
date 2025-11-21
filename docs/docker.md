# Creación de un contenedor de servicios NGINX con Docker

Creamos un archivo llamado Dockerfile en la raíz de tu repositorio con el siguiente contenido mínimo.

![Creación de dockerfile](Imagenes/dockerfile.png)


Construimos la imagen.

![Construir imagen](Imagenes/construir_imagen_dockerfile.png)


Ejecutamos el contenedor utilizando la imagen que acabamos de crear. 
Aquí es donde especificamos el nombre del contenedor, el puerto redirigido y el **bind-mount** de la carpeta del repositorio.

![Bindmount](Imagenes/bindmount_puerto.png)


Verificamos que el contenedor está activo.

![Verificación de contenedor activo](Imagenes/dockerps.png)


Creamos un archivo **index.html** para que nginx no muestre el contenido de los md con el siguiente contenido.

![Index de Nginx](Imagenes/nginx_index.png)


Acceder al repositorio a través del navegador web.

![Navegador Web](Imagenes/navegador_web.png)


Información sobre el contenedor con docker inspect.

![Docker inspect](Imagenes/docker_inspect.png)

