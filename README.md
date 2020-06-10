# *Práctica 2*


## *PLANTEAMIENTO DEL PROBLEMA*

¿El método de cálculo de corriente en mallas, es un método efectivo que nos dé garantías al momento de realizar nuestros cálculos, el cual se cumple en todos los casos sin excepción, y es conveniente realizarlo para obtener un proceso menos laborioso con respecto a otros estudiados en la materia?

## *OBJETIVO:*

Verificar el método de análisis de un circuito por mallas mediante la simulación del mismo y la aplicación de las Leyes de Kirchhoff.

## *LISTA DE MATERIALES:*

| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Fuente de voltaje de C.D |
| 2  | Multímetro digital  |
|  1 | Resistor de 1k  |
|  2 | Resistores de 2,2K  |
| 1 | Resistor de 1,8k  |
| 1  | Resistor de 3,9k  |
| 1  | Protoboard          |

## *MARCO TEÓRICO*


Para resolver circuitos eléctricos mediante análisis de mallas debemos tener claros algunos conceptos fundamentales, entre ellos está la corriente, el voltaje y la resistencia. Además, también debemos tener con conocimiento previo de las leyes que describen comportamientos de estos fenómenos en cada elemento del circuito como es la Ley de Ohm y las Leyes de voltaje de Kirchhoff. 


Para comenzar tenemos a la corriente que es el flujo de carga eléctrica que atraviesa un material conductor durante un periodo de tiempo determinado. Se expresa en C/s, culombios por segundo en el Sistema Internacional de Unidades, y la unidad se conoce como Amperio. Luego tenemos al voltaje que corresponde a la diferencia de potencia o tensión eléctrica entre 2 puntos, también se le conoce como la cantidad de voltios que se usan en un sistema eléctrico. Por último, tenemos a la resistencia que se define como una magnitud, que mide la dificultad con la que un conductor conduce la corriente, o bien a un elemento de un circuito (una pieza física que forma parte del mismo), este valor depende del material por el que se compone, la temperatura, su longitud y su sección.


La ley de ohm es usada para determinar la relación entre tensión, corriente y resistencia en un circuito eléctrico, esta ley es fundamental dentro de nuestro estudio. Se representa mejor de la siguiente manera:


![LeydeOhm]( https://github.com/Kevi7k/Practica/blob/master/Img/ley-de-ohm.png)


Un método para resolver problemas dentro de circuitos eléctricos es el análisis de mallas mediante la Ley de Tensión de Kirchhoff, tal como menciona Antonio J. Salazar: “En el análisis de mallas se parte de la aplicación de LTK a un conjunto mínimo de lazos para encontrar al final todas las corrientes de lazo. A partir de las corrientes de lazo es posible encontrar todas las corrientes de rama. El número de lazos que se pueden plantear en un circuito puede ser muy grande, pero lo importante es que el sistema de ecuaciones represente un conjunto mínimo de lazos independientes. Este conjunto mínimo es cualquiera en el cual todos los elementos (ramas) hayan sido tenidos en cuenta en al menos una malla. Las otras posibles mallas serán entonces redundantes Aquí también el número de incógnitas (corrientes de lazo) debe ser igual al número de ecuaciones, una por malla del conjunto mínimo.”(Análisis por nodos y mallas, pp 36-37).


![Analisis,Mallas]( https://github.com/Kevi7k/Practica/blob/master/Img/Ley-Voltaje-Kirchoff.png)



## *PROCEDIMIENTO:*

Armar el siguiente circuito


! [texto alternativo] ( https://github.com/Kevi7k/Practica/blob/master/Img/Circuito.png )


Mida cada una de las corrientes de malla y anote los resultados en la tabla 2.1, simule en el software Multisim, Proteus, o cualquier otro simulador .El circuito de la figura 2.1, obteniendo los valores de las corrientes de malla en la tabla 2.1. Anote los resultados en la siguiente tabla.

| MALLA | Resultados análiticos |Resultados simulados |
|----|--------|-------------|
|    1 |   11,46mA | 11,5mA |
|   2  |   2,85mA | 2,85mA |
|   3   |   -0,490mA | -0,488mA |

## *DIAGRAMA*

![alt text](https://github.com/Kevi7k/Practica/blob/master/Img/Diagrama.png)

![alt text](https://github.com/Kevi7k/Practica/blob/master/Img/TinkerCad.png)

## *ECUACIONES*


V = I * R 


Donde: 

	 V es el voltaje


	R es la resistencia
	
	
	I es la corriente
	
	
V1+V2+V3+…+Vn=0


## *EXPLICACIÓN DEL CIRCUITO*

Como ya lo hemos detallado, implementaremos nuestro circuito para hacer nuestro cálculo de corrientes por mallas. Nuestro circuito constara de dos fuentes de voltaje, y cinco resistencias.
Nuestro primer elemento será nuestra fuente de voltaje de 18V, el cual, estará conectado en serie con nuestra primera resistencia, que será de 820 ohmios. En dicha resistencia podremos calcular nuestra primera corriente ya que no existe otra corriente que actúe en ella. De dicha resistencia se dividen dos resistencias, es decir que existirá una división de corriente, en una resistencia de mil ohmios, que se conectara a los polos negativos de las fuentes de voltaje, y donde actuara nuestra corriente 1 y 2. Nuestra otra resistencia que salió de la resistencia de 820 ohmios, es nuestra resistencia de 1200 ohmios, donde podremos medir nuestra corriente 2, ya que es la única corriente que fluye por dicha resistencia. De esta resistencia tenemos nuevamente una división de corriente, teniendo resistencias de 2200 ohmios, y otra de 390 ohmios. De nuestra resistencia de 2200 ohmios vemos que actúan dos corrientes, que son las corrientes 3 y 4, y dicha resistencia está conectada en el otro extremo con nuestros polos negativos de las fuentes de voltaje. Y nuestra última resistencia de 390 ohmios, tiene un flujo de corriente de nuestra corriente 3, por lo cual podremos medir en dicha resistencia nuestro valor de corriente, dicha resistencia está unida en el otro extremo a nuestro polo positivo de nuestra fuente de voltaje de 5 volteos, y esta fuente conectando su polo negativo con el polo negativo de nuestra primera fuente, cerrando así nuestro circuito.


## *CONCLUSIONES*

-Los datos calculados que se obtuvo durante la practica simulada son similares a los obtenidos teoricamente.


-La malla con mayor intensidad de corriente es la que contiene el voltaje de 18v


-La malla con menor intensidad de corriente es la que contiene el voltaje de 5v


-Al final se pudo comprobar la ley de Kirchoff que nos dice que las corrientes que entran en un nodo son igual a las que salen.


-En todo este circuito se encontraron 5 corrientes. 


## *RECOMENDACIONES*

Se recomienda utilizar de manera correcta cualquier simulador para obtener los resultados correctos


## *CRONOGRAMA*

![alt text](https://github.com/Kevi7k/Practica/blob/master/Cronograma/Cronograma.jpeg)

## *BIBLIOGRAFÍA*

Emplear normas APA para el informe e IEEE para el artículo

## *ANEXOS*
![alt text](https://github.com/Kevi7k/Practica/blob/master/Img/Mallas.jpeg)

![alt text](https://github.com/Kevi7k/Practica/blob/master/Img/Corrientes.png)


15.2 HOJAS TÉCNICAS
