Para iniciar el contenedor, ejecutar el comando:
	$docker-compose up -d

El contenedor utiliza el puerto 80 interno y el 8080 en la computadora host.

La imagen en nginx del contenedor tiene dos volumenes:

	-1: Se utiliza como carpeta compartida:
		carpeta local: ./src
		carpeta host: /usr/share/nginx/html

	-2: Un volumen que se crea como volumen en si:
		data-volume = /app/data 

Para cancelar el contenedor utilizar:
	$docker-compose down


GRUPO:
	Jano Melul
	Alvaro De La Peña
	Bruno Diterlizi
	Franco Ligorria

