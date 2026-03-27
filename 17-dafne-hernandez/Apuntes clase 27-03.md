Anttes de ponerse a codificar se ponen a hacer diagrama de flujo

Rep grafica de un algoritmo o de los pasos de un proceso. En programacion se utiliza como una herramienta de planificacion para visualizar la logica de un programa antes de escribir una sola linea de codigo

Se usan componentes estandar, simbologia, para que cualquier programador pueda entenderlo.

Ej: La lampara no funciona -> preguntas: De si o no  
Si no -> Respuesta
Si si -> otra pregunta -> respuesta
Si no -> Respuesta
Van desde arriba hacia abajo, y siempre tendra la misma simbologia.  

Lenguajes de programacion:  
- Proposito general: Python, java, c++, c#

El lenguaje de programacion utiliza principalmente el lenguaje de JavaScript

p5 no es un leng. nuevo desde cero, si no una biblioteca de JavaScript.

Funciones maestras
Setup: se ejecuta una sola vez al principio para crear el lienzo

Su proposito: COnfigurar el enterno inicial
Que sucede: Defines el tamaño del lienzo (Createcanva) cargas ima

Draw: Se ejecuta en un bucle inifinito, (NOrmalmente 60 v por segundo) LO que permite crear animaciones
Proposito: Crear movimiento y responder a la interaccion real


CreateCanvas es la linea de codigo que se utiliza para crear el lienzo.
(createCanvas) Siempre asi
Luego viene el ancho por el alto y el render del canvas
el render configura el programa en 2D predeterminado (Si es que no se configura) pero si es que se quiere cambiar a 3D, se debe activar WEBGL, es indispensable para funciones como box,sphere, luces o texturas complejas  
Canvas: es el parametro oculto menos utolizado pero util si es que eres desarrollador Web.

Background: sintaxis -Background(v1,v2,v3,[a]); : v1,v2,v3 son los valores de RGB
El background sirve para designar el color de nuestro lienzo

4to parametro es el [a] es eñ canal alpha, si es que yo quiero que mi color sea transparente o semi transparente
