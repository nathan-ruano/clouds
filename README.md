# clouds-rusben

El primer paso para descargar nuestra cloud es seguir los pasos de la siguiente guia depiendiendo de si queremos descargar owncloud o nextcloud
[manual ](https://github.com/rusben/smx-m08/blob/main/docs/installacio-clouds.md)

El primer pàso es actualizar. utilizando el comando sudo apt update.

![Foto](1.png)

luego usamos sudo apt update

![Foto](2.png)

Despues tendremos que descargar apache2 usando el comando sudo apt insatall -y apache2.

![Foto](3.png)

Despues instalaremos el servidor de la base de datos.

![Foto](4.png)

Isntalaremos unas cuantas librerias de php.

![Foto](5.png)

![Foto](6.png)

i reiniciaremos el sistema.

![Foto](7.png)

despues configuraremos el MySQL

![Foto](8.png)

i crearemos la base de datos

![Foto](9.png)

Creamos un usuario.

![Foto](10.png)

Le damos privilegios.

![Foto](11.png)

salimos i provamos la conexion para ver si lo hemos echo bien.

![Foto](12.png)

luego descargamos los .zip de la cloud desde una de estos enlaces i copiaremos el zip en el directorio /var/www/html

![Foto](14.png)

https://download.nextcloud.com/server/releases/latest.zip

https://download.owncloud.com/server/stable/owncloud-complete-20240724.zip

una vez echo esto entraremos aldirectorio.

![Foto](13.png)

i descomprimimos el zip

![Foto](15.png)

Borramos el archivo index.html del apache2

![Foto](16.png)

una vez descimprimido aplicamos los siguientes permisos

![Foto](17.png)

i entramos a la direccion http://localhost i nos aparecera lo siguiente

![Foto](20.png)

rellenamos los datos i pasamos las vetanas emergentes que nos aparecen.

![Foto](21.png)

Hasta llegar al menu.

![Foto](23.png)

## **subir archivos i crear carpetas**

Para crear una carpeta tendremos que darle a la carpeta de arriba a la derecha i nos llevara a un menu donde tendremos que darle a new i a upl

















