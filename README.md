## Objetivo
Aprender Symfony

## Descripción
Aplicación en la que cada usuario puede agregar vídeos 
favoritos de YouTube, ver, modificarlos y borrarlos.
Además el usuario puede editar su perfil.

## Despliegue en producción
0. Si no tienes Docker Compose instálalo.
1. Crea los contenedores `docker-compose up -d --build`
2. Ejecuta las migraciones `docker-compose exec php php bin/console doctrine:migrations:migrate`
y pulsa la tecla Y.
3. En el navegador pon `http://localhost:8082`

## Licencia
MIT
