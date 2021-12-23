**“UNIVERSIDAD DE LAS FUERZAS ARMADAS”**

**“ESPE”**

![Logo_ESPE](https://user-images.githubusercontent.com/93800511/140828546-04ee2765-180c-4e68-84cf-8bca73c21c5f.png)

**INTEGRANTES**
* Coello Ismael 
* Paola Morales 
* Andrés Granda
 
**CLASE**
* FUNDAMENTOS DE CIRCUITOS ELECTRICOS **NRC** : 10149

**FECHA DE ENTREGA**
* 22/12/2021
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**1.1 OBJETIVO GENERAL**

Estudiar el concepto del método de superpocición de circuitos y sus implicaciones paractica por medio de un sistema simulado, esquematico y analítico de un curcuito con mas de una fuente y varios componentes pasivos. 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**1.2 OBJETIVOS ESPECIFICOS**

Construir un circuito y medir los voltajes generados al tomar en cuenta una fuente como si esta se encontrase en corto circuito.

Medir tanto voltaje como corriente en los casos necesarios y comparar los resultados tanto analiticos como paracticos de la practica.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**1.3 MARCO TEÓRICO**

![Diagrama en blanco (4)](https://user-images.githubusercontent.com/93800511/147184271-ce008cf3-a28f-4638-9cbf-5f8badd2e48d.png)

* Materiales a utilizar

![45](https://user-images.githubusercontent.com/93800511/147148540-4c625ba5-a153-406e-9326-11f1f0a0effe.png)

* Circuito a desarrollar

![45](https://user-images.githubusercontent.com/93800511/147148692-ce09e4d6-3f21-4443-b846-2572b9353837.png)

* Esquemático del circuito 

![78](https://user-images.githubusercontent.com/93800511/147150848-dee73b58-4653-4076-b92d-3787d8957f14.png)

Circiuito Armado 

![95](https://user-images.githubusercontent.com/93800511/147153300-d8392b79-6747-4af6-a266-dc9b7e05436b.jpg)

Mediciones del circuito

![image](https://user-images.githubusercontent.com/93835587/147166275-387c44a7-804f-443a-80ef-e2cae2a4781c.png)


Mediciones en el circuito cuando el voltaje de V2 es 0

![image](https://user-images.githubusercontent.com/93835587/147160500-345cacff-354b-4c37-a968-74f45de09775.png)

Mediciones del circuito cuando el voltaje de V1 es 0

![image](https://user-images.githubusercontent.com/93835587/147160075-c2be73e0-dedb-478f-bbc8-d3200239bbd6.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**1.4 EXPLICACIÓN DE PROCEDIMIENTO**

1. Arme el circuito que se muestra en la figura 4.1.

2. Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando
tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote
el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

3. Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente
IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se
proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

4. Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente
IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se
proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

5. Verifique el cumplimiento del Teorema de Superposición y compare los
resultados obtenidos prácticamente con los obtenidos analíticamente. Realice sus
conclusiones.


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**1.5 RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR**


Tabla de datos para VA

Tabla 4.1. Medición de voltaje aplicando superposición.

![image](https://user-images.githubusercontent.com/93835587/147247499-14555f12-6727-46cb-9adc-13542fb18ee0.png)

Tabla de datos para Ix

Tabla 4.2. Medición de corriente aplicando superposición.

![image](https://user-images.githubusercontent.com/93835587/147248395-d8d943af-1f84-49b5-80ff-121090397f3e.png)


Procedimiento de analisis analitico

 Primero reemplazamos la fuente de 20v
 
 ![image](https://user-images.githubusercontent.com/93835587/147170994-910734ac-0654-49d8-aed9-f6681c1806bc.png)

Encontramos la resistencia equivalente

<img src="https://latex.codecogs.com/svg.image?~\\\frac{1}{Req}=&space;\frac{\left&space;(&space;1&plus;2.2&space;\right&space;)}{\left&space;(&space;&space;&space;1\times&space;2.2\right&space;)}\\Req=&space;0.68k\mho&space;&space;" title="~\\\frac{1}{Req}= \frac{\left ( 1+2.2 \right )}{\left ( 1\times 2.2\right )}\\Req= 0.68k\mho " />

Obtenemos el siguiente circuito

![image](https://user-images.githubusercontent.com/93835587/147172082-5b068491-8fe2-435c-82f9-423a18daa224.png)


Encontramos las ecuaciones de cada malla 

<img src="https://latex.codecogs.com/svg.image?\\MALLA~1\\12&plus;I_{2}-0.47\left&space;(&space;I_{1}&plus;I_{2}&space;\right&space;)=&space;0\\-0.47I_{1}&space;&plus;0.47I_{2}=&space;-12\begin{pmatrix}&space;Ecuacion~1\end{pmatrix}\\&space;MALLA~2\\-0.82I_{2}&space;-0.68I_{2}-0.47\left&space;(&space;I_{1}-I_{2}&space;\right&space;)=&space;0\\&space;0.47I_{1}-1.97I_{2}=&space;0\begin{pmatrix}Ecuacion~2\end{pmatrix}" title="\\MALLA~1\\12+I_{2}-0.47\left&space;(&space;I_{1}+I_{2}&space;\right&space;)=&space;0\\-0.47I_{1}&space;+0.47I_{2}= -12\begin{pmatrix} Ecuacion~1\end{pmatrix}\\&space;MALLA~2\\-0.82I_{2}&space;-0.68I_{2}-0.47\left&space;(&space;I_{1}-I_{2}&space;\right&space;)=&space;0\\&space;0.47I_{1}-1.97I_{2}=&space;0\begin{pmatrix}Ecuacion~2\end{pmatrix}" />

Obtenemos el siguiente sistema de ecuaciones 

<img src="https://latex.codecogs.com/svg.image?\\\left\{\begin{matrix}-0.47I_{1}&plus;&space;0.47I_{2}=&space;-12\\0.47I_{1}-1.97I_{2}=&space;0\end{matrix}\right." title="\\\left\{\begin{matrix}-0.47I_{1}+ 0.47I_{2}= -12\\0.47I_{1}-1.97I_{2}= 0\end{matrix}\right." />

Encontramos la I1 y la I2

<img src="https://latex.codecogs.com/svg.image?~\\I_{1}=&space;I_{X}=&space;33.53mA\\I_{2}=&space;8mA" title="~\\I_{1}= I_{X}= 33.53mA\\I_{2}= 8mA" />

Encontramos VA mediante la ley de Ohm

<img src="https://latex.codecogs.com/svg.image?~\\I=&space;\frac{V}{R}\\V_{A}&space;=&space;I_{2}\times&space;R_{0.82}=&space;8\left&space;(&space;0.82&space;\right&space;)\\V_{A}&space;=6.56V&space;" title="~\\I= \frac{V}{R}\\V_{A} = I_{2}\times R_{0.82}= 8\left ( 0.82 \right )\\V_{A} =6.56V " />

Realizamos el mismo procedimiento pero en este caso reemplazamos la fuente de voltaje de 12 V 

![image](https://user-images.githubusercontent.com/93835587/147174272-0bf3112a-1c1b-458f-833e-ef1a2afd19d8.png)

Procedemos a resolver el circuito 

Redibujamos el circuito 

![image](https://user-images.githubusercontent.com/93835587/147174508-514c2099-0434-4e80-a424-f49f44527b14.png)
 
 Calculada la resistencia total obtenemos el siguiente circuito
 
 ![image](https://user-images.githubusercontent.com/93835587/147174904-59512170-c8e4-4a59-9ed7-141a05853439.png)



<img src="https://latex.codecogs.com/svg.image?\\Re\left|&space;\right|=&space;R3\left|&space;\right|R2\\RT=&space;\left&space;(&space;\frac{1}{820}&space;&plus;\frac{1}{2200}\right&space;)\\&space;RT=597.35\\Req=&space;R1&plus;RT&space;\\Req=1000&plus;&space;597.35\\Req=159.35&space;\\VA=&space;\frac{RA}{RT}\left&space;(&space;VT&space;\right&space;)&space;\\VA=\left&space;(&space;\frac{597.35}{159.35}&space;\right&space;)\left&space;(&space;20&space;\right&space;)&space;\\VA=7.47&space;" title="\\Re\left| \right|= R3\left| \right|R2\\RT= \left ( \frac{1}{820} +\frac{1}{2200}\right )\\ RT=597.35\\Req= R1+RT \\Req=1000+ 597.35\\Req=159.35 \\VA= \frac{RA}{RT}\left ( VT \right ) \\VA=\left ( \frac{597.35}{159.35} \right )\left ( 20 \right ) \\VA=7.47 " />

<img src="https://latex.codecogs.com/svg.image?\\Ix=\frac{v}{R4}\\Ix=\frac{12}{470}&space;\\Ix=25.53mA&space;" title="\\Ix=\frac{v}{R4}\\Ix=\frac{12}{470} \\Ix=25.53mA " />



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**1.6 VIDEOS**

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**1.7 .CONCLUCIONES**

En conclucion el metodo de superposicion para el análisis de los circuitos es comprobable por medio de esta practica donde la precencia de dos fuentes de poder, así comprobando que el voltaje o corriente dentro de este tipo de circuitos se puede encontrar aislando una de las corrientes y calculando los componentes individualmente con la otra fuente igualada a cero. 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**1.8.BIBLIOGRAFÍA**

Floyd, Thomas.L. (s. f.). Floyd Octava Edición principios de circuitos electricos (8va edición, Vol. 1). Prentice Hall. https://latecnicalf.com.ar/descargas/material/electronicaanalogica/Dispositivos%20Electronicos%208va.edicion-%20Floyd.pdf

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
