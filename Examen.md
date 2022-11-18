## Ejercicio 2 ##
Accedemos al ordenador de "usuario" mediante ssh con el comando:
```
sudo ssh usuario@192.168.0.168
```
tras introducir su contraseña nos dirigimos al directorio deseado
```
cd /var/www

![This is a alt text.](/Escritorio/examen.png "This is a sample image.")
## Ejercicio 3 ##
Entramos dentro de la carpeta que acabamos de crear dentro del ordenador remoto en "usuario"
```
cd /var/www/diegoj
```
Y descargamos la imagen de la url mediante el comando "wget"
```
/var/www$ sudo wget https://iesalandalus.org/ciclos/semipresencial/daw-sp/daw.png 
```

con esto ya tendríamos la imagen descargada en la carpeta.
