# Proyecto 1: Reconocimiento de declaraciones

## Integrantes: 

* Larissa
* Nadya
* José
* Francisco
* Bernardo

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
Particularmente en el último punto, mencionado anteriormente, para el número total de variables declaradas se utilizan if's y el programa revisa si hay arrays de tipo int, float, byte, entre otras y para el número de variables usadas de las obtenidas busca si hay alguna otra coincidencia. 


## Utilización

Se corre el programa, donde en la tercer linea se cambia "Ejemplo.txt" por el documento que se desee analizar.


