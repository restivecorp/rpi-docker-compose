# rpi-docker-compose

Ficheros docker-compose para levantar mis actuales servicios en la RaspberryPI.


## Arranque de los servicios

Nos situamos en el directorio donde se encuentra el fichero _docker-compose.yml_ y ejecutamos los siguientes comandos, función del servicio deseado.

*File Browser*
```
	pi@raspberry:~ $ docker compose-up
```

*Heimdall*
```
	pi@raspberry:~ $ docker volume create heimdall_data
	pi@raspberry:~ $ docker compose-up
```

*Home Assistant*
```
	docker volume create home-assistant_data
	pi@raspberry:~ $ docker compose-up
```

*MiniDLNA*
```
	pi@raspberry:~ $ docker compose-up
```

*Portainer*
```
	pi@raspberry:~ $ docker volume create portainer_data
	pi@raspberry:~ $ docker compose-up
```

*RPI Monitor*
```
	pi@raspberry:~ $ docker compose-up
```

*Transmission*
```
	pi@raspberry:~ $ docker compose-up
```
Posteriormente configuraremos el fichero _settings.json_ del contenedor para optimizar y configurar en base a nuestras necesidades.


