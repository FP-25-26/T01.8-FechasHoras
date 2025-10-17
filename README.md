# T01.7-FechasHoras
El objetivo de este proyecto es trabajar con los tipos python para fechas, horas e intervalos temporales.

1. Escribe un programa que solicite a un usuario su fecha de nacimiento y devuelva el día de la semana en el que nació. Descompon el programa en tres funciones: '
   * `lee_persona`, que se encarga de solicitar los datos de una persona por teclado y devuelve una tupla con el nombre y la fecha de nacimiento de la persona.
   * `calcula_dia_nacimiento, que, dada una fecha, devuelve el día de la semana de esa fecha.
   * `muestra_saludo`, que toma una tupla con el nombre y la fecha de nacimiento de una persona, y muestra por consola el saludo que se indica en el ejemplo de uso. 

Ejemplo de uso:
```
>>> Introduzca su nombre:
>>> Jane
>>> Introduzca su día de nacimiento (un entero):
>>> 23
>>> Introduzca su mes de nacimiento (un entero):
>>> 3
>>> Introduzca su año de nacimiento (un entero con 4 dígitos):
>>> 2001
>>> Hola, Jane, buenos días! Tu fecha de nacimiento fue Viernes
```
2. Modifique la función muestra_saludo para que muestre por la consola un saludo terminado en buenos días, buenas tardes o buenas noches, dependiendo de la hora del día a la que se ejecute la función. Para hacer la modificación cree una función auxiliar `msg_saludo` que devuelva una cadena que sea buenos_dias, buenas_tardes o buenas_noches, dependiendo de la hora del día. Se considera buenos días si es antes de las 12 de mediodía, buenas tardes entre las 12 y las 9 de la noche y buenas noches en el resto de los casos.
 
Ejemplo de uso:
```
>>> Introduzca su nombre:
>>> Jane
>>> Introduzca su día de nacimiento (un entero):
>>> 23
>>> Introduzca su mes de nacimiento (un entero):
>>> 3
>>> Introduzca su año de nacimiento (un entero con 4 dígitos):
>>> 2001
>>> Hola, Jane, buenas tardes! Tu fecha de nacimiento fue Viernes
```
4. Implemente una función `calcula_edad` que, dada la fecha de nacimiento de una persona, devuelva la edad que tiene.

5. Modifica la `namedtuple` definida en el proyecto T01.6-Ejer-listas-tuplas [https://github.com/FP-24-25/T01.6-Ejer-listas-tuplas]  para añadir un último campo de tipo fecha que represente la fecha de nacimiento de la persona.

```python
Persona = namedtuple ("Persona", "nombre, peso, estatura, fecha_nacimiento")
```
6. Modifica la función de lectura de ficheros para poder leer datos de personas con fechas de nacimiento. Prueba la lectura con el archivo `personas_fechas.csv` que se proporciona en la carpeta data

7. Añade una funcion `son_mayores_edad` que dada una lista de tuplas de tipo Persona, devuelva cierto si todas las personas de la lista son mayores de edad, y falso en caso contrario.


