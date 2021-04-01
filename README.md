# Proyecto 1: Reconocimiento de declaraciones

## Integrantes: 


* José David Barranco 
* Francisco González
* Bernardo Paniagua
* Larissa Trasviña
* Nadya Soto

## Programa desarrollado

El programa utiliza el paquete de expresiones regulares en Python para reconocer todas las posibles declaraciones de variables del leguaje Java (versión 8). 

Además, regresa las estadísticas del archivo analizado:

* Número total de variables declaradas
* Número total de tipos utilizados en las declaraciones encontradas
* Número total de variables declaradas de cada tipo
* Numero total de variables inicializadas
* Número total de variables de tipo arreglo
* Clasificación de todos los nombres de variables por tipo declarado

## Descripción
El programa recorre la lista ResTipo1 que contiene los tipos de variables Java como son byte, float, int, boolean, entre otros. Para cada elemento de está lista revisa si existen coincidencias en el texto enviado. 
Uno de los puntos interesantes es que se sustituyeron los espacios por comas debido a que se puede extender el programa agregándole espacio y coma. 
Se tomó en cuenta los arreglos como un tipo de variable, en lugar de considerarlos por separado, por ejemplo, si hay un arreglo de enteros no se toma como tipo entero, sino como arreglo
Particularmente en el último punto, mencionado anteriormente, para el número total de variables declaradas se utilizan if's y el programa revisa si hay arrays de tipo int, float, byte, entre otras y para el número de variables usadas de las obtenidas busca si hay alguna otra coincidencia. 


## Utilización

Se corre el programa y este mismo pregunta por el archivo de texto que se desea leer. 



