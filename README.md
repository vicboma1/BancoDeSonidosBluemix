# Banco de Sonidos Bluemix
Pequeño proyecto que forma parte del starter kit de la hackathon.

### Esquema Node-RED

![](https://github.com/vicboma1/BancoDeSonidosBluemix/blob/master/assets/_bancoDeSonidosBluemix.png)

La solución se basa en un esquema de nodos que representa un banco de sonidos online.

El dispositivo kinect procesa la información y la envía al IoT Watson de Bluemix.

Mediante Node-RED accedemos a esa información y la manipulamos.

El ejemplo consta de un reconocimiento de formas al que se le asocia un sonido.

Para el caso de uso se ha utilizado el movimiento de un látigo con su respectivo audio.


### Kinect Studio Application Windows + Movimientos reales 
#### (Click en la imagen para ver video)

[![](http://img.youtube.com/vi/IXQ_oDFuQiU/0.jpg)](https://www.youtube.com/watch?v=IXQ_oDFuQiU "Banco de sonidos")

### Pasos a seguir 

1.   Copiar la ![Plantilla txt](https://github.com/vicboma1/BancoDeSonidosBluemix/blob/master/assets/_bancoDeSonidosBuemix.txt) con "Control A" + "Control C"

2.   Ir al menú contextual de nuestra aplicación Node-RED

3.   Importar

4.   Clipboard

5.   Import Nodes -> "Control V" para pegar la template

6.   Aceptar pulsando el botón de "Import"

7.   Configura el nodo IBM IoT Input con la Api Key de tu Universidad.

8.   Para renderizar los componentes del dashboard necesitas instalar la dependencia "node-red-dashboard"

9.   Ir al menú contextual de nuestra aplicación Node-Red -> "Manage Palette" -> Install

10.  Escribimos -> "node-red-dashboard" para Web | "node-red-dashboard-es" para mobile


@Author: [Victor Bolinches Marin](https://github.com/vicboma1)  

@Documento Principal [CoEValencia - Hackathon 2017](https://goo.gl/vmuVXH)
