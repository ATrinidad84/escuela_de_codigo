Realizar el algoritmo y diagrama de flujo de un programa para obtener la suma de diez cantidades, iniciando en 1, mediante la utilización de un ciclo “Mientras”

Algoritmo Sumarcantidades

	i=1
  
	Mientras i<11 Hacer
  
		Escribir "ingresa la cantidad ", i
    
		Leer cantidad
    
		total=total+cantidad
    
		i=i+1
    
	Fin Mientras

	Escribir "la suma es", total
  
FinAlgoritmo


![image](https://user-images.githubusercontent.com/102439544/161397060-b3bf5986-0b1a-4e60-82b5-50da79eb65c8.png)


Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.

Algoritmo suma_positivos
	
	Repetir
  
		Escribir "ingrese un numero"
		
		Leer num
		
		Si num>0 Entonces
			
			suma=suma+num
			
		SiNo
		
			
		Fin Si
		
	Hasta Que num<0
	
	Escribir "la suma de tus montos es ", suma
	
FinAlgoritmo


![image](https://user-images.githubusercontent.com/102439544/161397148-66acf4f3-ba51-42a4-97a1-9de9d50db154.png)
