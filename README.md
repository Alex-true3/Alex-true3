Proyecto de PSeint

// EJERCICIO 1 Mayor de cinco números: Solicita tres números y determina cuál es el mayor de ellos.
Funcion mayor_1
	Definir num1, num2, num3, mayor Como Real
	// Solicitar al usuario que ingrese tres números
    Escribir "Ingrese el primer número:"
    Leer num1
    Escribir "Ingrese el segundo número:"
    Leer num2
    Escribir "Ingrese el tercer número:"
    Leer num3
	// Si decimos que el primer número es el mayor inicialmente
    mayor = num1
	
    // Comparar el segundo número con el mayor actual
    Si num2 > mayor Entonces
        mayor = num2
    FinSi
	
    // Comparar el tercer número con el mayor actual
    Si num3 > mayor Entonces
        mayor = num3
    FinSi
	
    // Mostrar el resultado
    Escribir "El mayor de los tres números es:", mayor 
FinFuncion
