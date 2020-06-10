# *Práctica 2*

Para la presentación de los trabajos se establecererá el día y la hora máxima de fecha de entrega, para el efecto se creará un foro en el cual los estudiantes participarán con un mensaje indicando sus nombres completos, el tipo de actividad, el tema y el link del repositorio.

Para la calificación cada grupo debe generar una hoja de cálculo con las matrices de calificación y debe compartir el documento con doalulema@espe.edu.ec

## *PLANTEAMIENTO DEL PROBLEMA*


Formular correctamente un problema consiste básicamente, en reducirlo a sus aspectos y relaciones esenciales. Debe ser formulado con precisión, en una o varias preguntas concretas donde se relacionen las variables implicadas, por ejemplo: ¿qué efecto?, ¿en qué condiciones...?, ¿cuál es la probabilidad de...?, ¿cómo se relaciona... con...?, etc. Algunas condiciones que debe cumplir son:

Especificar lo que ha de determinarse o resolverse
Restringir el campo de estudio en un interrogante concreto
Enunciarse de una forma clara y unívoca, de modo que la respuesta sólo admita respuestas precisas
Susceptible de verificación empírica. No debe plantear juicios de valor sobre lo que es mejor o peor, sobre cómo debería ser idealmente la realidad, sino sobre cómo es realmente.
Su formulación debe responder a tres criterios básicos:

Claridad. Cualquier persona que lea el problema debe entender a qué cuestiones se pretende responder con la investigación
Concisión.
Operatividad. El planteamiento operacional consiste en especificar no sólo el fenómeno, sino también en qué unidades va a ser medidos cada uno de estos efectos.

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


![alt text](https://github.com/Kevi7k/Practica/blob/master/Img/Circuito.png)


Mida cada una de las corrientes de malla y anote los resultados en la tabla 2.1, simule en el software Multisim, Proteus, o cualquier otro simulador .El circuito de la figura 2.1, obteniendo los valores de las corrientes de malla en la tabla 2.1. Anote los resultados en la siguiente tabla.

| MALLA | Resultados análiticos |Resultados simulados |
|----|--------|-------------|
|    1 |   11,4mA    |        |
|   2  |   2,8mA   |    |
|   3   |   0,441mA    |      |

## *DIAGRAMA*

![alt text](https://github.com/Kevi7k/Practica/blob/master/Img/Diagrama.png)

![alt text](https://github.com/Kevi7k/Practica/blob/master/Img/Corrientes.png)

## *ECUACIONES*


V = I * R 


Donde: V es el voltaje


	R es la resistencia
	
	
	I es la corriente
	
	
V1+V2+V3+…+Vn=0


## *EXPLICACIÓN DEL CIRCUITO*

En este punto se debe explicar cómo funcionan la implementación del programa, explicando los valores que requiere y los valores que devuelve.


## *CONCLUSIONES*

-Los datos calculados que se obtuvo durante la practica simulada son similares a los obtenidos teoricamente.


-La malla con mayor intensidad de corriente es la que contiene el voltaje de 18v


-La malla con menor intensidad de corriente es la que contiene el voltaje de 5v


-Al final se pudo comprobar la ley de Kirchoff que nos dice que las corrientes que entran en un nodo son igual a las que salen.


-En todo este circuito se encontraron 5 corrientes. 


## *RECOMENDACIONES*

Se recomienda utilizar de manera correcta cualquier simulador para obtener los resultados correctos


## *CRONOGRAMA*

El estudiante detalla cada una de las tareas y actividades que va a ejecutar durante el desarrollo de su trabajo. Este cronograma debe representarse gráficamente mediante un “DIAGRAMA DE GANTT”, el cual de ser desarrollado con MICROSOFT PROJECT.


## *BIBLIOGRAFÍA*

Emplear normas APA para el informe e IEEE para el artículo

## *ANEXOS*
![alt text](https://github.com/Kevi7k/Practica/blob/master/Img/Procedimiento%20circuito.jpg)

15.2 HOJAS TÉCNICAS
