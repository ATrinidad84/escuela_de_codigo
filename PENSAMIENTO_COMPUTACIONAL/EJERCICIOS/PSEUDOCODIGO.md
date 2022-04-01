
Convierte los siguientes ejercicios realizado durante el taller a pseudocodigo.

1. Realizar un algoritmo y diagrama de flujo de un programa que solicite un número y lo multiplique por 9, mostrando su resultado.

Algoritmo_para_multiplicar_un_numero_por_9

	Escribir "Escriba un numero" num
  
	Leer num
  
	Escribir "El numero " num " por 9 da " num*9
  
FinAlgoritmo

![image](https://user-images.githubusercontent.com/102439544/160260002-fb8c57d6-3a65-4b4a-bee0-d987f648a84b.png)

3. Realiza un diagrama de flujo para obtener la suma de diez cantidades, que se soliciten al usuario, mediante la utilización de un ciclo “Mientras”. 

Algoritmo Algoritmo_para_suma_10_cantidades

	j<-0
  
	Mientras j<10 Hacer j=j+1
  
		Escribir "Ingrese cantidad " j
    
		Leer subtotal
    
		suma=suma+subtotal
    
	Fin Mientras
  
Escribir "La suma total es " suma

FinAlgoritmo

![image](https://user-images.githubusercontent.com/102439544/160260809-10ab52a3-bddd-4e7b-902f-1ee7781afaa8.png)

5. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

Algoritmo Algoritmo_para_promedio_felicitacion

	j<-0
  
	Mientras j<4 Hacer j=j+1
  
		Escribir "Ingrese calificacion del periodo " j
    
		Leer calif
    
		sumacalif=sumacalif+calif
    
		prom=sumacalif/4
    
	Fin Mientras
  
	Escribir "El promedio es " prom
  
	Si prom>=6 Entonces
  
		Escribir "Felicidades, sigue triunfando"
    
	SiNo
  
		Escribir "Haz reprobado, tu destino es repartir comidas a domicilio"
    
	Fin Si
  
FinAlgoritmo

![image](https://user-images.githubusercontent.com/102439544/160261090-34777ee9-45a5-4b64-815d-e2eeaf0ea2c5.png)


7. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

Algoritmo Algoritmo_para_numero_par_impar

	Escribir "Escriba un número "
  
	Leer num
  
	x= num MOD 2
  
	Si x=0 Entonces
  
		Escribir "El número es par "
    
	SiNo
  
		Escribir "El número es impar "
    
	Fin Si
  
	FinAlgoritmo

![image](https://user-images.githubusercontent.com/102439544/160261419-0b5f298f-776c-469c-8213-2b4b63fb49d3.png)


9. Un programa que pida una letra y detecte si es una vocal.

Algoritmo Algoritmo_vocal_no_vocal

	Escribir "Escribe una letra ",letra
  
	Leer letra
  
	Segun letra Hacer
  
		"a" o "A":
    
			Escribir "La letra es vocal "
      
		 "e" o "E":
     
			Escribir "La letra es vocal "
      
		"i" o "I":
    
			Escribir "La letra es vocal "
      
		"o" o "O":
    
			Escribir "La letra es vocal "
      
		"u" o "U":
    
			Escribir "La letra es vocal "
			
		De Otro Modo:
    
			Escribir "La letra no es vocal "
      
	Fin Segun
  
	FinAlgoritmo
  
  ![image](https://user-images.githubusercontent.com/102439544/160262281-3c0cdde2-062d-4d63-b53a-a02c669da50e.png)


11. Programa que pida 3 números y los muestre en pantalla de menor a mayor.

Algoritmo sin_titulo

	Escribir "Por favor escriba el primer número", num1
	
	Leer num1
	
	Escribir "Por favor escriba el segundo número", num2
	
	Leer num2
	
	Escribir "Por favor escriba el tercer número", num3
	
	Leer num3
	
	Si num1<num2 Y num1<num3 Entonces
	
		Si num2<num3 Entonces
		
			Escribir num1, num2, num3
			
		SiNo
		
			Escribir num1, num3, num2
			
		Fin Si
		
	SiNo
	
		Si num2<num1 Y num2<num3 Entonces
		
			Si num1<num3 Entonces
			
				Escribir num2, "  " num1, "  " num3
				
			SiNo
			
				Escribir num2, "  " num3, "  " num1
				
			Fin Si
			
		SiNo
		
			Si num3<num1 Entonces
			
				Si num1<num2 Entonces
				
					Escribir num3, "  " num1, "  " num2
					
				SiNo
				
					Escribir num3, "  " num2, "  "  num1
					
				Fin Si
				
			SiNo 
			
				Escribir "Los tres numeros son iguales"
				
				FinSi
				
			Fin Si
			
		Fin Si
		
	FinAlgoritmo
	
	
![image](https://user-images.githubusercontent.com/102439544/161181672-491c009d-7336-4300-91d2-dd0469e2ac78.png)


13. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.

Algoritmo nombre_X_veces

	Escribir "Por favor, escribe tu nombre"
	
	Leer name
	
	Escribir "ingresa un número (entero) de veces que quieres que aparezca tu nombre"
	
	Leer veces
	
	Para i<-1 Hasta veces Con Paso 1 Hacer
	
		Escribir name
		
	Fin Para
	
	FinAlgoritmo
	
	
![image](https://user-images.githubusercontent.com/102439544/161186397-d3f8cbfc-8a51-4a12-b0a5-1c95004594ea.png)


15. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.

Algoritmo suma_numeros_positivos

	Escribir "Por favor, ingresa un número"
	
	Leer num
	
	Mientras num > 0 Hacer
	
		resultado<-resultado + num
		
		Escribir "Por favor, ingresa otro número"
		
		Leer num
		
	Fin Mientras
	
	Escribir "El resultado de los números positivos que has ingresado es ",resultado
	
	FinAlgoritmo
	

![image](https://user-images.githubusercontent.com/102439544/161187918-57ad0cd9-ac95-4dd0-8100-e91036e99846.png)
