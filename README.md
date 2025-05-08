# Algoritmo en PSeInt: Identificación de Números Positivos o Negativos

## Descripción

Este algoritmo está diseñado para recibir un número ingresado por el usuario y determinar si ese número es positivo, negativo o si es igual a cero. El algoritmo realiza una simple comparación con el valor cero para tomar la decisión correspondiente.

## Objetivo

El objetivo principal de este algoritmo es mostrar cómo usar condicionales en PSeInt para realizar una tarea básica de clasificación de números. Este tipo de algoritmo es útil para aprender a manejar estructuras de control como `SI` (condicional) y `SINO`.

## Flujo del Algoritmo

1. El programa solicita al usuario ingresar un número.
2. Compara el número con cero:
   - Si el número es mayor que cero, se imprime que el número es positivo.
   - Si el número es menor que cero, se imprime que el número es negativo.
   - Si el número es igual a cero, se imprime que el número es cero.
   
## Pseudocódigo en PSeInt

Algoritmo Positivo_Negativo_0
	Definir num1 Como Real
	Escribir "Ingrese el número"
	Leer num1
	Si num1 > 0 Entonces
		Escribir "El número es positivo"
	SiNo
		Si Num1 = 0 Entonces
			Escribir "El número es igual a 0"
		SiNo
			Si num1 < 0 Entonces
				Escribir "El número es negativo"
			FinSi
		FinSi
	FinSi
FinAlgoritmo

## Explicación del Pseudocódigo
## Definir numero Como Real 
Se declara la variable numero para almacenar el número que el usuario ingresa. Se define como tipo Real para permitir valores decimales.

## Escribir "Ingresa un número:
": Muestra un mensaje pidiendo al usuario que ingrese un número.

## Leer numero:
Lee el número ingresado por el usuario y lo guarda en la variable numero.

## Condicionales (SI / SINO):

Se compara si el número es mayor que cero. Si es cierto, el número es positivo.

Si el número es menor que cero, se concluye que el número es negativo.

Si ninguna de las dos condiciones anteriores es verdadera, se asume que el número es igual a cero.

## Ejemplos de Ejecución
## Ejemplo 1:

Entrada: 5

Salida: "El número es positivo."

## Ejemplo 2:

Entrada: -3

Salida: "El número es negativo."

## Ejemplo 3:

Entrada: 0

Salida: "El número es cero."

## Conclusión
Este algoritmo es una forma sencilla de ilustrar el uso de estructuras de control condicional en PSeInt. Puedes modificar este algoritmo para agregar más condiciones o realizar otras operaciones, como verificar si el número es par o impar.
