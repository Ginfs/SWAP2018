# Practica 2

## 2. Crear un tar con ficheros locales en un equipo remoto
Creamos el fichero tar con ssh en la otra maquina.
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica2/img/t2_1.jpg)

Y vemos que se a creado el fichero
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica2/img/t2_2.jpg)

## 3. Rsync
Desde la maquina2 vamos a clonar la carpeta /var/www/html de la maquina1 en /var/www/html de la maquina2  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica2/img/t3_1.jpg)

Y vemos que se ha pasado  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica2/img/t3_2.jpg)

## 4. Acceso sin contraseña por ssh
En primer lugar, generamos la clave  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica2/img/t4_1.jpg)

Copiamos la clave existente en la otra maquina  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica2/img/t4_2.jpg)

Ahora probamos a conectarnos sin contraseña  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica2/img/t4_3.jpg)

Una prueba de la ejecucion de un comando pro ssh  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica2/img/t4_4.jpg)

## 5. 