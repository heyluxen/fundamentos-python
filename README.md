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

Código implementado:
print("Ejercicio 1:", 5 + 3 * 2)
print("Ejercicio 2:", 8 / 2 + 4 * 3)
print("Ejercicio 3:", (7 + 3) * 2 - 5)
print("Ejercicio 4:", 10 - 4 + 2 * 3)
print("Ejercicio 5:", (10 / 2) * (3 + 2) - 4)
print("Ejercicio 6:", 2 + 3 * (4 - 1))
print("Ejercicio 7:", 5 * 2 ** 3)
print("Ejercicio 8:", 6 + 4 / 2 ** 2)
print("Ejercicio 9:", 10 % 3 + 2 * 5)
print("Ejercicio 10:", (8 + 2) * 3 ** 2)
print("Ejercicio 11:", 7 + 2 * (3 + 5) / 4)
print("Ejercicio 12:", 2 ** 3 * 4 / 2)
print("Ejercicio 13:", 9 - 6 + 3 ** 2)
print("Ejercicio 14:", (7 - 2) * 5 + 3 ** 2)
print("Ejercicio 15:", 4 * 2 ** 3 / 8 + 1)

Resultados obtenidos:
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