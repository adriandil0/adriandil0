Ejercicios de Algoritmia (Analisis)

1. REALIZAR UN ALGORITMO QUE PERMITA LEER 3 NUMEROS ENTEROS
POSITIVO E IMPRIMA CUAL ES MAYOR Y CUAL ES EL MENOR.

Problema    : leer 3 numeros enteros postivos y mostrar el mayor y el menor.
Variables   : number1, number2, number3
Operaciones : solicitar al usuario 3 numeros como entero

descartar numeros < 0... continuar con el algoritmo hasta que el usuario ingrese 3 numeros positivos.Con ciclo mientras

comparar n1 con n2 y n3 para validar si ese valor es mayor que los otros dos o menor, si es verdadero imprimirlo.
comparar n2 con n1 y n3 para validar si ese valor es mayor que los otros dos o menor, si es verdadero imprimirlo.
comparar n3 con n1 y n2 para validar si ese valor es mayor que los otros dos o menor, si es verdadero imprimirlo.


Algoritmo leerTresNumeros
	
	Definir n1, n2, n3 como entero
	
	//descartar numeros negativos en el primer valor
	Escribir "Ingresar el 1er numero: "
	leer n1
	mientras (n1 < 0 ) hacer	
		Escribir "Ingresa un numero positivo "
		Leer n1
	Fin mientras
	
	//descartar numeros negativos en el segundo valor
	Escribir "Ingresar el 2do numero: "
	leer n2
	mientras (n2 < 0 ) hacer	
		Escribir "Ingresa un numero positivo "
		Leer n2
	Fin mientras
	
	//descartar numeros negativos en el tercer valor
	Escribir "ingresar el 3er numero: "
	leer n3
	mientras (n3 < 0 ) hacer	
		Escribir "Ingresa un numero positivo "
		Leer n3
	Fin mientras
	Limpiar Pantalla
	
	//definir mayor y menor del primer valor
	Si n1>n2 y n1>n3 Entonces
		Escribir "MAYOR PRIMER VALOR: ", n1
	Fin Si
	si n1<n2 y n1<n3 Entonces
		Escribir "MENOR PRIMER VALOR: ", n1  
	FinSi
	
	//definir mayor y menor del segundo valor
	Si n2>n1 y n2>n3 Entonces
		Escribir "MAYOR SEGUNDO VALOR: ", n2
					
	Fin Si
	si n2<n1 y n2<n3 Entonces
		Escribir "MENOR SEGUNDO VALOR: ", n2  
	FinSi
	
	//definir mayor y menor del tercer valor
	Si n3>n1 y n3>n2 Entonces
		Escribir "MAYOR TERCER VALOR: ", n3
	Fin Si
	si n3<n1 y n3<n2 Entonces
		Escribir "MENOR TERCER VALOR: ", n3  
	FinSi
	

FinAlgoritmo
