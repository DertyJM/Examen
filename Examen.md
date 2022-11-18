# Examen Primer Trimestre #
## Introducción ##

En el día de hoy vamos a realizar una série de prácticas utilizando **ssh** y **comandos de linux** para tratar de aprobar el examen planteado por el profesor.
### Ejercicio 2 ###
Accedemos al ordenador de "usuario" mediante ssh con el comando:
```
sudo ssh usuario@192.168.0.168
```
tras introducir su contraseña nos dirigimos al directorio deseado
```
cd /var/www
```
Una vez dentro procedemos a crear la carpeta "diegoj"
```
 sudo mkdir /var/www/diegoj
 ```

Con el comando *touch* creamos el archivo ejercicio2.txt dentro del directorio /diegoj:
```
$ sudo touch/var/www/diegoj/ejercicio2.txt
```
![Imagen de la terminal.](/examen3.png "Imagen de la creación del archivo en diegoj.")
### Ejercicio 3 ###
Entramos dentro de la carpeta que acabamos de crear dentro del ordenador remoto en "usuario"
```
cd /var/www/diegoj
```
Y descargamos la imagen de la url mediante el comando *wget*
```
/var/www$ sudo wget https://iesalandalus.org/ciclos/semipresencial/daw-sp/daw.png 
```

con esto ya tendríamos la imagen descargada en la carpeta.
## Webgrafía ##
* [Sysamit](https://www.sysadmit.com/2015/12/linux-buscar-ficheros-directorios-con-find.html)
* [Techlandia](https://techlandia.com/crear-nuevo-archivo-terminal-ubuntu-como_44119/)
