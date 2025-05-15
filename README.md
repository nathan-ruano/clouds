# clouds-rusben
## **Crear maquina virtual**

EL primer paso para instalar nuestras clouds es crear la maquina virtual, para ello  entramos en el isardvdi i darle a escritorio nuevo

![Foto](0.1.PNG)

Despues le pondremos el nombre i la descripcion que nosotros queramos a la maquina.

![Foto](0.2.PNG)

Elegimos es sitema operativo que vallamos a utilizar i le damos a crear

![Foto](0.3.PNG)

![Foto](0.4.PNG)

# Descargar nextcloud

El primer pàso es entrar en la terminal i actualizar. utilizando el comando sudo apt update.

![Foto](1.png)

Luego usamos sudo apt update.

![Foto](2.png)

Despues tendremos que descargar apache2 usando el comando sudo apt insatall -y apache2.

![Foto](3.png)

Despues instalaremos el servidor de la base de datos.

![Foto](4.png)

Isntalaremos unas cuantas librerias de php.

![Foto](5.png)

![Foto](6.png)

I reiniciaremos el sistema.

![Foto](7.png)

Despues configuraremos el MySQL.

![Foto](8.png)

I crearemos la base de datos.

![Foto](9.png)

Creamos un usuario.

![Foto](10.png)

Le damos privilegios.

![Foto](11.png)

Salimos i provamos la conexion para ver si lo hemos echo bien.

![Foto](12.png)

luego descargamos los .zip de la cloud desde una de estos enlaces i copiaremos el zip en el directorio /var/www/html

![Foto](14.png)

https://download.nextcloud.com/server/releases/latest.zip

Una vez echo esto entraremos aldirectorio.

![Foto](13.png)

I descomprimimos el zip.

![Foto](15.png)

Borramos el archivo index.html del apache2.

![Foto](16.png)

Una vez descimprimido aplicamos los siguientes permisos.

![Foto](17.png)

I entramos a la direccion http://localhost i nos aparecera lo siguiente.

# Configuracion


![Foto](20.png)

Rellenamos los datos i pasamos las vetanas emergentes que nos aparecen.

![Foto](21.png)

Hasta llegar al menu.

![Foto](23.png)

## **subir archivos i crear carpetas**

Para crear una carpeta tendremos que darle a la carpeta de arriba a la derecha i nos llevara a un menu donde tendremos que darle a new folder.

![Foto](24.png)

I elgimos el nombre de la carpeta.

![Foto](24.1.png)

Una vez creada la carpeta para subir archivos le damos a upload files i elegimos el archivo.

![Foto](26.png)

![Foto](27.png)

## **compartir**
Para compartir un archivo tendres que darle a los tres puntos al lado del nombre del archivo/carpeta i darel a sharing, tendremos dos opciones o crear un enlace o poner el correo de la parsona a la que se lo queremos compartir.

![Foto](28.png)

## **usuarios i grupos**

Para crear un usuario tendremos que darle a nuestro perfil i darle al boton agregar lo cual nos llevara a al siguiente pantalla en la cual tendremos que darle a nueva cuenta para agregar un usuario.

![Foto](30.png)

Rellenamos los datos i listo.

![Foto](31.png)

![Foto](32.png)

I repetimos para crear mas.

![Foto](33.png)

Para crear un grupo es parecido, simplemente le damso a el + i elegimos el nombre del grupo.

![Foto](34.png)

## **roles**

Para los roes tendremos que crear diversos grupos i ir añadiendo los usuarios.

![Foto](35.png)


## **organizar**

Para organizar archivo tendremos que darle a los tres puntos que se ven en la imagen i darle a mover o copiar.

![Foto](36.png)

Una vez echo nos aparecera la siguiente pantalla en la cual podremos organizar los archivos como queramos.

![Foto](37.png)

## **Enlaces**

para configurar un enlace tendremos que meternos en el apartado sharing i tendremos que darle a I darle a creata public link.

![Foto](28.png)

nos aparecera lo siguiente. 

![Foto](38.png)

I tendremos que darle a personalizar enlace i nos aparecera un menu en el que podremos modificar el enlace.

# Descargar owncloud

El primer pàso es Entrar a la terminal i actualizar utilizando el comando sudo apt update.

![Foto](1.png)

Luego usamos sudo apt update.

![Foto](2.png)

Despues tendremos que descargar apache2 usando el comando sudo apt insatall -y apache2.

![Foto](3.png)

Despues instalaremos el servidor de la base de datos.

![Foto](4.png)

Instalaremos los requisitos previos de PPA.

![Foto](1.2.png)

Despues instalaremos las herramientas que necesitamos para trabajar con los paquetes PPA.

![Foto](1.3.png)

Actualizamos el repositorio.

![Foto](1.4.png)

Despues descargaremos las librerias PHP version 7.4

![Foto](1.5.png)

![Foto](1.6.png)

![Foto](1.7.png)

Despues tendremos que elegir la version de PHP que queremos utilizar para ello ponemos el siguiente comando el cual nos enseñara todos los PHP que tenemos i un numero al lado, buscamos la version 7.4 i ponemos el numero   que nos salga en mi caso es 1.

![Foto](1.8.png)

![Foto](PHP.png)

Despues activaremos los modulos necesarios.

![Foto](1.9.png)

![Foto](1.10.png)

I reiniciaremos el sistema.

![Foto](7.png)

Despues configuraremos el MySQL.

![Foto](8.png)

I crearemos la base de datos.

![Foto](9.png)

Creamos un usuario.

![Foto](10.png)

Le damos privilegios.

![Foto](11.png)

Salimos i provamos la conexion para ver si lo hemos echo bien.

![Foto](12.png)

luego descargamos los .zip de la cloud desde una de estos enlaces i copiaremos el zip en el directorio /var/www/html

![Foto](14.png)

[https://download.nextcloud.com/server/releases/latest.zip](https://download.owncloud.com/server/stable/owncloud-complete-20240724.zip)

Una vez echo esto entraremos aldirectorio.

![Foto](13.png)

I descomprimimos el zip.

![Foto](15.png)

Borramos el archivo index.html del apache2.

![Foto](16.png)

Una vez descimprimido aplicamos los siguientes permisos.

![Foto](17.png)

I entramos a la direccion http://localhost i nos aparecera lo siguiente.

![Foto](o1.png)


## **subir archivos i crear carpetas**

Para crear una carpeta tendremos que darle aal simbolo mas i darle folder escribir el nombre i darle a create

![Foto](mas.PNG)


Una vez creada la carpeta para subir archivos le damos otra vez al mas pero esta vez le damos a upload i elegimos el archivo.

![Foto](mas.PNG)

![Foto](o2.png)

![Foto](03.png)

## **compartir**
Para compartir un archivo tendres que darle a los tres al simbolo que se muestra en la foto i escribir a quien se lo queremos mandar.

![Foto](o4.png)

![Foto](o5.png)


## **usuarios i grupos**

Para crear un usuario tendremos que darle a nuestro perfil, darle a users la cual nos llevara a una pantalla en la que para agregar a un usuario tendremos que esccribir su nombre i correo electronico i darle  a create.

![Foto](o6.png)

![Foto](o7.png)

![Foto](o8.png)

![Foto](o9.png)

![Foto](o10.png)

Para crear grupos le damos a add group ponemos el nombre que queramos.

![Foto](o11.png)

![Foto](o12.png)

![Foto](o13.png)

Para añadir un usuario a un grupo le damos a no group i elegimos el grupo.

![Foto](o14.png)

![Foto](o15.png)

## **roles**

Para los roles tendremos que crear diversos grupos e ir añadiendo los usuarios.

![Foto](o16.png)



























