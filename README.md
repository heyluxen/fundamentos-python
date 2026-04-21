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

En este laboratorio se utilizó una sola instrucción print() para generar una salida específica que incluye múltiples comillas.

Para lograrlo se emplearon:

Caracteres de escape (\") para imprimir comillas dentro de la cadena
Una estructura de cadena cuidadosamente construida para respetar el formato solicitado

Ejemplo de salida:
"Estoy"""aprendiendo"""""Python"""