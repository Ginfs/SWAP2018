# Practica 3

## 3 Balanceo de carga usando nginx
Creamos el fichero /etc/nginx/conf.d/default.conf  
Escribirmos el codigo necesario para indicar las maquinas
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica3/img/t3.2_1.JPG)

Despues comentamos la linea que hace que el balanceador funciones como servidor web y reiniciamos nginx
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica3/img/t3.2_2.JPG)

Ahora vemos como ya está funcionando como balanceador
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica3/img/t3.2_3.JPG)


## 4 Balanceo de carga con haproxy
Instalamos haproxy y modificamos el fichero de configuracion
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica3/img/t4_1.JPG)

Vemos que el balanceador funciona alternando las maquinas
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica3/img/t4_2.JPG)

## 5 Someter a una alta carga el servidor de balanceo
Vamos a utilizar Apache Benchmark con cada uno de los diferentes balanceadores 
que hemos probado.  
Resultado nginx.
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica3/img/t5_1.JPG)

Resultado haproxy.
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica3/img/t5_2.JPG)

Las puebas se hacen con 5000 peticiones y con el balanceador recien reiniciado para cada prueba,
para evitar que se quede cargado el servidor. Como vemos nginx es bastante más rapido tratandose 
de una carga relativamente baja.