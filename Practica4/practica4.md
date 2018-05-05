# Practica 4

## 2 Instalar un certificado SSL autofirmado para configurar el acceso por HTTPS
Despues de habilitar el SSL en nuestro Ubuntu Server y realizar la tarea de creación
del certificado.  
Editamos el archivo de configuracion añadiendo las lineas necesarias
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica4/img/t1_1.JPG)

Activamos el sitio y reiniciamos el apache
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica4/img/t1_2.JPG)

Probamos el acceso al sitio con https
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica4/img/t1_3.JPG)
Vemos que la maquina donde está el certificado y https habilitado acepta la petición mientras
que la otra maquina no.