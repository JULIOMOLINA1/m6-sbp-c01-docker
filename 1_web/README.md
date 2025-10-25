

Ver imagenes
```
docker images
```
Crear una imagen

```
docker pull nginx:latest
```
Ejecutar un contenedor

```
docker run -d -p 8010:80 --name web  nginx
```

Ver logs

```
docker logs web
docker logs -f web
```

Entrar al contenedor ( para salir con exit)

```
docker exec -it web /bin/bash
```

Detener contenedor

```
docker stop web
```

Elminar un contenedor, para le ejemplo el contenedor es 'web'
```
docker rm web
```