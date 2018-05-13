# Practica 4

## 2 Instalar un certificado SSL autofirmado para configurar el acceso por HTTPS
Despues de habilitar el SSL en nuestro Ubuntu Server y realizar la tarea de creación
del certificado.  
Editamos el archivo de configuracion añadiendo las lineas necesarias  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica4/img/t2_1.JPG)

Activamos el sitio y reiniciamos el apache  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica4/img/t2_2.JPG)

Probamos el acceso al sitio con https  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica4/img/t2_3.JPG)
Vemos que la maquina donde está el certificado y https habilitado acepta la petición mientras
que la otra maquina no.

Ahora vamos a activar https en las otras maquinas.  
Para la otra maquina basta con copiar los certificados, activar ssl y configurar el archivo como en la maquina 1.
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica4/img/t2_4.JPG)  
Añadimos las lineas de configuracion de SSL a larchivo dafault-ssl.  
Activamos los servicios con el maquina 1 y reiniciamos apache.  
Y vemos como ya tenemos las dos maquinas contestando en https.  
![imagen](https://github.com/Ginfs/SWAP2018/blob/master/Practica4/img/t2_4.JPG)  
