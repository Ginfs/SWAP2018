# Practica 5

## 3 Crear una BD e insertar datos
Creamos nuestra base de datos con la tabla y algunos datos.  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica5/img/t3_1.JPG)

## 4 Replicar una BD MySQL con mysqldump

#### Maquina 1
Primero vamos hacer nuestra copia en local con mysqldump.  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica5/img/t4_1.JPG)

#### Maquina 2
Primero copiamos el fichero .sql en nuestra maquina.  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica5/img/t4_2.JPG)

Una vez que lo tenemos creamos la base de datos e importamos la base de datos.  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica5/img/t4_3.JPG)

Vemos que se ha importado correctamente.  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica5/img/t4_4.JPG)

## 5 Replicacion de BD mediante una configuracion maestro-esclavo
Primero configuramos las dos maquinas con la configuracion indicada, reiniciamos el servicio  
y si no da ningun erro es que todo está correcto.

Ahora realizamos la configuracion del maestro.  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica5/img/t5_1.JPG)

Realizamos la cofiguracion en el esclavo.  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica5/img/t5_2.JPG)

Vemos que el estado del esclavo es correcto.  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica5/img/t5_3.JPG)

Ahora vamos a ver que todo funciona correctamente.  
Insertamos una tupla en la tabla del maestro.  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica5/img/t5_4.JPG)

Y vemos como se refleja el cambio en el esclavo.  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica5/img/t5_5.JPG)