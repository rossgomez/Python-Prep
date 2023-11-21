## Variables

1) Crear una variable que contenga un elemento del conjunto de números enteros y luego imprimir por pantalla

a=12
print (a)

2) Imprimir el tipo de dato de la constante 8.5

type(8.5)

3) Imprimir el tipo de dato de la variable creada en el punto 1

type (a)

4) Crear una variable que contenga tu nombre

x = 'Rosa Gomez'
print(x)

5) Crear una variable que contenga un número complejo

n_complejo = 8 + 5j

6) Mostrar el tipo de dato de la variable crada en el punto 5

type(n_complejo)

7) Crear una variable que contenga el valor del número Pi redondeado a 4 decimales
pi = 3.1416

8) Crear una variable que contenga el valor 'True' y otra que contenga el valor True. ¿Se trata de lo mismo?
a = 'True'
b = True

9) Imprimir el tipo de dato correspondientes a las variables creadas en el punto 8
print('La variable 1 es de tipo ', type(a), ' y la variable 2 es de tipo ', type(b))

10) Asignar a una variable, la suma de un número entero y otro decimal

a = 8 + 5.3

11) Realizar una operación de suma de números complejos

a = 5 + 10j
b = 8 + 5j
print (a+b)

12) Realizar una operación de suma de un número real y otro complejo
a = b + 3.15
print (a)

13) Realizar una operación de multiplicación
print (3*5)

14) Mostrar el resultado de elevar 2 a la octava potencia
print(2**8)

15) Obtener el cociente de la división de 27 entre 4 en una variable y luego mostrarla
a = 27/4
print (a)

16) De la división anterior solamente mostrar la parte entera
print (27//4)

17) De la división de 27 entre 4 mostrar solamente el resto
27 % 4

18) Utilizando como operandos el número 4 y los resultados obtenidos en los puntos 16 y 17. Obtener 27 como resultado
6*4 + 3

19) Utilizar el operador "+" en una operación donde intervengan solo variables alfanuméricas
a = 'hola '
b = 'mundo'
print(a+b)

20) Evaluar si "2" es igual a 2. ¿Por qué ocurre eso?

5 == '5'

21) Utilizar las funciones de cambio de tipo de dato, para que la validación del punto 20 resulte verdadera
5 == int('5')

22) ¿Por qué arroja error el siguiente cambio de tipo de datos? a = float('3,8')
a = float ('3,8')

23) Crear una variable con el valor 3, y utilizar el operador '-=' para modificar su contenido
a = 3
a -= 1
print (a)

24) Realizar la operacion 1 << 2 ¿Por qué da ese resultado? ¿Qué es el sistema de numeración binario?
1<< 2
- ¿Por qué da ese resultado?
La operación 1 << 2 da como resultado 4 debido a cómo funciona el desplazamiento a la izquierda en el sistema binario y su relación con el sistema decimal.
- ¿Qué es el sistema de numeración binario?
El sistema de numeración binario es un sistema numérico que utiliza solo dos dígitos, 0 y 1. 


25) Realizar la operación 2 + '2' ¿Por qué no está permitido? ¿Si los dos operandos serían del mismo tipo, siempre arrojaría el mismo resultado?
2 + '2'
- ¿Por qué no está permitido?
no está permitida en muchos lenguajes de programación debido a que involucra tipos de datos diferentes.
- ¿Si los dos operandos serían del mismo tipo, siempre arrojaría el mismo resultado?
Sí, si los dos operandos son del mismo tipo, la operación de suma (+) generalmente arrojará el mismo resultado, manteniendo el tipo de datos.

26) Realizar una operación válida entre valores de tipo entero y string

a = 'valor repetido, '
b = 3
print (a * b + str(b) + ' veces')
