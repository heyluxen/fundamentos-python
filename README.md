# fundamentos-python

Sesión 1: Introducción a Python y print()

Descripción:

Este repositorio contiene la solución de los laboratorios correspondientes a la Sesión 1, donde se introducen los conceptos básicos de Python utilizando la función print().

En esta primera sesión se trabaja con:

Impresión en pantalla
Uso de cadenas de texto
Formato de salida
Argumentos de la función print()
Lógica utilizada

La lógica en esta sesión se basa en el uso de la función:

print()

Esta función permite mostrar información en consola. Se aplicaron los siguientes conceptos:

Uso de cadenas entre comillas
Separación de argumentos con comas
Uso de parámetros:
sep → define el separador
end → define el final de la línea
Uso de caracteres especiales como \n para saltos de línea
Multiplicación de cadenas para repetir patrones


Laboratorio 1: Trabajando con la función print()
Código
print("¡Hola, Mundo!")
print("Valentina")

Explicación:

Se utilizó la función print() para mostrar mensajes en pantalla.
También se identificaron errores comunes al modificar la sintaxis.

Ejemplo de salida:
¡Hola, Mundo!
Valentina

Laboratorio 2: La función print() y sus argumentos

Código:
print("Programming", "Essentials", "in", sep="***", end="...")
print("Python")

Explicación:

Se utilizaron argumentos de palabra clave para modificar el formato de salida:

sep="***" → separa palabras
end="..." → evita salto de línea

Ejemplo de salida:
Programming***Essentials***in...Python

Laboratorio 3: Dando formato a la salida

Código:

print("    *    "*2)
print("   * *   "*2)
print("  *   *  "*2)
print(" *     * "*2)
print("***   ***"*2)
print("  *   *  "*2)
print("  *   *  "*2)
print("  *****  "*2)

Explicación:

Se trabajó con:

Formato visual en consola
Uso de multiplicación de cadenas (*)
Organización del texto para generar figuras

Ejemplo de salida:

    *        *    
   * *      * *   
  *   *    *   *  
 *     *  *     * 
***   ******   ***
  *   *    *   *  
  *   *    *   *  
  *****    *****  

Sección 2 - Literales de python - Cadenas

Descripción:

En esta sesión se trabajó con los literales de Python, los cuales representan valores fijos que se escriben directamente en el código.

Se estudiaron los principales tipos de datos:

Números enteros (int)
Números flotantes (float)
Cadenas de texto (str)
Valores booleanos (bool)

Lógica utilizada:

La lógica principal consiste en entender que los literales permiten representar datos directamente en el programa sin necesidad de cálculos previos.

Laboratorio: Literales de Python – Cadenas

Código:
print("\"Estoy\"\"\"aprendiendo\"\"\"\"\"Python\"\"\"")

Explicación:

En este laboratorio se utilizó una sola instrucción print() para generar una salida específica que incluye múltiples comillas

Para lograrlo se emplearon:

Caracteres de escape (\") para imprimir comillas dentro de la cadena
Una estructura de cadena cuidadosamente construida para respetar el formato solicitado

Ejemplo de salida:
"Estoy"""aprendiendo"""""Python"""

Sección 3 - Operadores - herramientas de manipulación de datos

Descripción

En esta sección se trabajó con operadores matemáticos en Python, utilizando el lenguaje como una herramienta para evaluar expresiones aritméticas. Se resolvieron ejercicios aplicando la jerarquía de operadores y posteriormente se verificaron los resultados con código.

Lógica utilizada

Se aplicó la jerarquía de operaciones en Python:

Potencias **
Multiplicación, división, división entera y módulo * / // %
Suma y resta + -

También se utilizaron paréntesis para controlar el orden de ejecución.

Ejercicios: 

Ejercicio 1:

Expresión:
5 + 3 * 2

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación:

Multiplicación primero:
3 * 2 = 6
Suma:
5 + 6 = 11

Resultado final:
11

Ejercicio 2:

Expresión:
8 / 2 + 4 * 3

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación:
8 / 2 = 4.0
4 * 3 = 12
4.0 + 12 = 16.0

Resultado:
16.0

Ejercicio 3:

Expresión:
(7 + 3) * 2 - 5

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación:
7 + 3 = 10
10 * 2 = 20
20 - 5 = 15

Resultado:
15

Ejercicio 4:

Expresión:
10 - 4 + 2 * 3

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación:
2 * 3 = 6
10 - 4 = 6
6 + 6 = 12

Resultado:
12

Ejercicio 5:

Expresión:
(10 / 2) * (3 + 2) - 4

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación:
10 / 2 = 5.0
3 + 2 = 5
5.0 * 5 = 25.0
25.0 - 4 = 21.0

Resultado:
21.0

Ejercicio 6:

Expresión:
2 + 3 * (4 - 1)

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación:
4 - 1 = 3
3 * 3 = 9
2 + 9 = 11

Resultado:
11

Ejercicio 7:

Expresión:
5 * 2 ** 3

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación:
2 ** 3 = 8
5 * 8 = 40

Resultado:
40

Ejercicio 8:

Expresión:
6 + 4 / 2 ** 2

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación:
2 ** 2 = 4
4 / 4 = 1.0
6 + 1.0 = 7.0

Resultado:
7.0

Ejercicio 9:

Expresión:
10 % 3 + 2 * 5

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación
10 % 3 = 1
2 * 5 = 10
1 + 10 = 11

Resultado:
11

Ejercicio 10:

Expresión:
(8 + 2) * 3 ** 2

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación
8 + 2 = 10
3 ** 2 = 9
10 * 9 = 90

Resultado:
90

Ejercicio 11:

Expresión:
7 + 2 * (3 + 5) / 4

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación
3 + 5 = 8
2 * 8 = 16
16 / 4 = 4.0
7 + 4.0 = 11.0

Resultado:
11.0

Ejercicio 12:

Expresión:
2 ** 3 * 4 / 2

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación:
2 ** 3 = 8
8 * 4 = 32
32 / 2 = 16.0

Resultado:
16.0

Ejercicio 13:

Expresión:
9 - 6 + 3 ** 2

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación
3 ** 2 = 9
9 - 6 = 3
3 + 9 = 12

Resultado:
12

Ejercicio 14:

Expresión:
(7 - 2) * 5 + 3 ** 2

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación:
7 - 2 = 5
3 ** 2 = 9
5 * 5 = 25
25 + 9 = 34

Resultado:
34

Ejercicio 15:

Expresión:
4 * 2 ** 3 / 8 + 1

Pregunta: ¿Cuál es el resultado? ¿Por qué?

Solución y Explicación:
2 ** 3 = 8
4 * 8 = 32
32 / 8 = 4.0
4.0 + 1 = 5.0

Resultado:
5.0

Salida de consola:
Ejercicio 1: 11
Ejercicio 2: 16.0
Ejercicio 3: 15
Ejercicio 4: 12
Ejercicio 5: 21.0
Ejercicio 6: 11
Ejercicio 7: 40
Ejercicio 8: 7.0
Ejercicio 9: 11
Ejercicio 10: 90
Ejercicio 11: 11.0
Ejercicio 12: 16.0
Ejercicio 13: 12
Ejercicio 14: 34
Ejercicio 15: 5.0

Sección 4 - Variables

Descripción:

En esta sección se introduce el concepto de variables en Python, las cuales funcionan como “cajas” que permiten almacenar datos para ser utilizados posteriormente en un programa.

Las variables son fundamentales en la programación, ya que permiten guardar resultados intermedios, reutilizar información y construir lógica más compleja.

Laboratorio 1 - Variables: un convertidor simple

Descripción:

En este laboratorio se desarrolla un programa en Python que permite convertir unidades de distancia entre millas y kilómetros.

Se utiliza la relación:

1 milla ≈ 1.61 kilómetros

El objetivo es practicar el uso de variables, operadores aritméticos y la función print() para mostrar resultados.

Objetivos:
Comprender cómo usar variables.
Aplicar operaciones matemáticas básicas.
Aprender a mostrar resultados con print().
Utilizar la función round() para redondear valores.

Lógica del programa:

Se definen dos variables:
miles
kilometers

Se realizan las conversiones:

Millas a kilómetros → miles * 1.61
Kilómetros a millas → kilometers / 1.61

Se imprimen los resultados redondeados a 2 decimales.

Código:
kilometers = 12.25
miles = 7.38

miles_to_kilometers = miles * 1.61
kilometers_to_miles = kilometers / 1.61

print(miles, "millas son", round(miles_to_kilometers, 2), "kilómetros")
print(kilometers, "kilómetros son", round(kilometers_to_miles, 2), "millas")

Salida:
7.38 millas son 11.88 kilómetros
12.25 kilómetros son 7.61 millas

Laboratorio 2 – Operadores y expresiones

Descripción:

En este laboratorio se desarrolla un programa en Python que evalúa una expresión matemática algebraica, utilizando variables y operadores.

La expresión a resolver es:

3x3−2x2+3x−1

El objetivo es practicar el uso de operadores aritméticos, variables y el manejo de datos tipo float.

Lógica del programa:
Se define una variable x.
Se convierte a tipo float.
Se traduce la expresión matemática a Python usando:
* para multiplicación
** para potencias
Se calcula el resultado y se guarda en y.
Se imprime el resultado.

Código:

x = 1 
x = float(x)

y = 3 * x**3 - 2 * x**2 + 3 * x - 1

print("y =", y)

Salida:

y = 3.0

Explicación:
La expresión algebraica se escribe en Python respetando el orden de operaciones:

Primero potencias (**)
Luego multiplicaciones (*)
Finalmente sumas y restas (+, -)

Python evalúa la expresión y guarda el resultado en la variable y.

Laboratorio 3 - Ejercicios de algoritmos

Descripción:
En este laboratorio se desarrollan 15 ejercicios aplicando operadores matemáticos en Python dentro de un contexto de videojuego (gameplay).

Cada ejercicio utiliza variables y operaciones para resolver problemas como puntajes, tiempos, porcentajes y promedios.

Ejercicios: 

1. Puntaje total
nivel1 = 100
nivel2 = 200
nivel3 = 150

total = nivel1 + nivel2 + nivel3
print("Puntaje total:", total)

Salida:
Puntaje total: 450

Lógica: Se suman los puntos de los tres niveles.

2. Tiempo total en segundos
horas = 1
minutos = 30
segundos = 20

total_segundos = horas * 3600 + minutos * 60 + segundos
print("Tiempo total:", total_segundos)

Salida:
Tiempo total: 5420

Lógica: Se convierten horas y minutos a segundos y luego se suman.

3. Daño total
ataque1 = 50
ataque2 = 70
ataque3 = 30

danio_total = ataque1 + ataque2 + ataque3
print("Daño total:", danio_total)

Salida:
Daño total: 150

Lógica: Se suman los daños de los ataques.

4. Experiencia total
mision1 = 100
mision2 = 200
mision3 = 150

experiencia = mision1 + mision2 + mision3
print("Experiencia total:", experiencia)

Salida:
Experiencia total: 450

Lógica: Se suman las recompensas de experiencia.

5. Porcentaje de vida
vida_max = 100
vida_actual = 75

porcentaje = (vida_actual / vida_max) * 100
print("Vida restante:", porcentaje, "%")

Salida:
Vida restante: 75.0 %

Lógica: Se calcula el porcentaje de vida actual respecto a la máxima.

6. Oro total
oro1 = 50
oro2 = 75
oro3 = 25

total_oro = oro1 + oro2 + oro3
print("Oro total:", total_oro)

Salida:
Oro total: 150

Lógica: Se suman las cantidades de oro.

7. Velocidad promedio
distancia = 100
tiempo = 2

velocidad = distancia / tiempo
print("Velocidad promedio:", velocidad)

Salida:
Velocidad promedio: 50.0

Lógica: Se divide la distancia entre el tiempo.

8. Costo total de mejoras
mejora1 = 200
mejora2 = 300
mejora3 = 150

costo_total = mejora1 + mejora2 + mejora3
print("Costo total:", costo_total)

Salida:
Costo total: 650

Lógica: Se suman los costos de las mejoras.

9. Tiempo restante
tiempo_total = 120
tiempo_transcurrido = 45

restante = tiempo_total - tiempo_transcurrido
print("Tiempo restante:", restante)

Salida:
Tiempo restante: 75

Lógica: Se resta el tiempo transcurrido al total.

10.  Nivel promedio
jugador1 = 10
jugador2 = 20
jugador3 = 30

promedio = (jugador1 + jugador2 + jugador3) / 3
print("Nivel promedio:", promedio)

Salida:
Nivel promedio: 20.0

Lógica: Se calcula el promedio sumando y dividiendo entre 3.

11.  Daño crítico
danio_base = 100
multiplicador = 2

danio_critico = danio_base * multiplicador
print("Daño crítico:", danio_critico)

Salida:
Daño crítico: 200

Lógica: Se multiplica el daño base por el multiplicador.

12. Tiempo en horas y minutos
minutos_totales = 130

horas = minutos_totales // 60
minutos = minutos_totales % 60

print("Tiempo:", horas, "horas y", minutos, "minutos")

Salida:
Tiempo: 2 horas y 10 minutos

Lógica: Se divide en horas y se obtiene el residuo en minutos.

13. Porcentaje de misiones
total_misiones = 50
completadas = 25

porcentaje = (completadas / total_misiones) * 100
print("Misiones completadas:", porcentaje, "%")

Salida:
Misiones completadas: 50.0 %

Lógica: Se calcula el porcentaje completado.

14. Costo total de objetos
obj1 = 100
obj2 = 200
obj3 = 50

total = obj1 + obj2 + obj3
print("Costo total:", total)

Salida:
Costo total: 350

Lógica: Se suman los costos.

15. Tiempo promedio de partidas
partida1 = 30
partida2 = 45
partida3 = 60

promedio = (partida1 + partida2 + partida3) / 3
print("Tiempo promedio:", promedio)

Salida:
Tiempo promedio: 45.0

Lógica: Se calcula el promedio de tiempos.

16. Tiempo promedio de partidas
partida1 = 30
partida2 = 45
partida3 = 60

promedio = (partida1 + partida2 + partida3) / 3
print("Tiempo promedio:", promedio)

Salida:
Tiempo promedio: 45.0

Laboratorio 4 - Variables 

Descripción:
En este laboratorio se practica el uso de variables en Python mediante una historia sencilla donde se almacenan y manipulan datos numéricos.

Se utilizan variables para representar la cantidad de manzanas que tienen diferentes personas y luego se realizan operaciones con esos valores.

Lógica utilizada:

Se crean tres variables:
john
mary
adam

Se asignan valores según la historia:

John → 3 manzanas
Mary → 5 manzanas
Adam → 6 manzanas

Se imprimen los valores en una sola línea.
Se crea una nueva variable total_apples que almacena la suma.
Se imprime el total de manzanas.

Código:
john = 3
mary = 5
adam = 6

print(john, mary, adam)

total_apples = john + mary + adam

print("Número total de manzanas:", total_apples)

Salida:
3 5 6
Número total de manzanas: 14