# TheContainers
# Proyecto final Telemática
este es el proyecto final de Telemática, realizado en el lenguaje Python, realizado en el sistema operativo ubuntu


## como crear la pagina web

tenemos que clonar el repositoriode github 
-git clone https://github.com/Gregori04/TheContainers.git
-cd TheContainers

## A tener en cuenta

para poder modificar el programa y pueda correr, debe modificar el archivo web.py y cambiar la dirección localhost a su dirección IP pública
- En la linea 68: return  redirect('http://localhost:5600/?password=040405')
(se modifica localhost)

- En el aws modificar el security group habilitando el puerto 80 y el puerto 5600

## Ejecutar la pagina
se debe actualizar el repositorio de paquetes e instalar el docker-compose junto con dos imágenes, mysql y ubuntu, finalmente, ejecutará el archivo docker-compose.yml, que creará tres contenedores.


## Final

Ingresar la IP publica con el puerto :80 y le aparecerá la pagina, cuando ingrese un usuario lo redireccionara a la pagina de https://siata.gov.co/siata_nuevo/ de lo contrario lo redireccionara a la pagina de la upb


