## El modelo cliente - servidor

![ClienteServidor1](https://user-images.githubusercontent.com/61668265/81129634-561f4400-8f1b-11ea-93da-2f6c84ab8e56.png)

PROTOCOLO: Tanto el cliente como el servidor son programados para entender y usar un conjunto particular de reglas. Es similar a dos personas de diferentes paises aceptan hablar un mismo lenguaje.


![ClienteServidor2](https://user-images.githubusercontent.com/61668265/81129656-6d5e3180-8f1b-11ea-88ad-20b4623dd4b6.png)

Se tiende una liena entre el cliente y el servidor, lo que se conoce como socket, donde la información es transferida usando uno de los siguiente protocolos: http, ftp, smtp.

Como se envía la información? 
La forma en la cual se transmite es usando el protocolo TCP (Transmision Control Protocol) el cual divide la información en piezas que viajan a travez de los socket, estas piezas se llaman paquetes.

En Node, tenemos las herramientas para implementar este modelo. Tipicamente en Node se contruye un servidor web.

![clientservidor3](https://user-images.githubusercontent.com/61668265/81132074-89fe6780-8f23-11ea-85ed-52436224cf24.png)

PORT: Cuando un programa recibe un paquete en un puerto particular, se dice que el programa esta escuchando el puerto


HTTP: HyperText Transfer Protocol, es el formato en el cual esta definido los datos para ser transferidos via TCP/IP. HTTP en resumen son las reglas que debe cumplir la informacion para ser transferida por TCP/IP

### Ejemplo de Response
![clientservidor4](https://user-images.githubusercontent.com/61668265/81131879-0e9cb600-8f23-11ea-84c1-ac92c2deee1a.png)



