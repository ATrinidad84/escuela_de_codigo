# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

* Programa que pida un número y diga si es positivo o negativo
* 
Algoritmo Numero_positivo_negativo

	Escribir "El siguiente algoritmo determina si un número es positivo o negativo"
  
	Escribir "Por favor escriba un número", num
  
	Leer num
  
	Si num>0 Entonces
  
		Escribir "El numero " num " es positivo"
    
	SiNo
  
		Escribir "El número " num " es negativo"
    
	Fin Si
  
FinAlgoritmo

![image](https://user-images.githubusercontent.com/102439544/161349824-5959bfe6-cef9-45bc-9ecc-1e6832f9bed4.png)


* Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.


Algoritmo caracter_sn
	
	Definir letra Como Caracter
	
	Repetir
  
		Escribir "caracter invalido"
    
		Leer letra
    
	Hasta Que letra="s" O letra="n"
		
	
FinAlgoritmo


* Un programa que pida una letra y detecte si es una vocal. 

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

![image](https://user-images.githubusercontent.com/102439544/161350201-bda3ecd9-0ba4-432d-8b2e-da8ab63144a7.png)


* Programa que pida 3 números y los muestre en pantalla de menor a mayor.  

Algoritmo numeroMenor_a_mayor

	Escribir "ingrese el primer numero"
	
	Leer a
	
	Escribir "ingrese el segundo numero"
	
	Leer b
	
	Escribir "ingrese el tercer numero"
	
	Leer c

	
	Si a<b Entonces
		Si a<c Entonces
			Si b<c Entonces
				Escribir "Los valores ordenados de menor a mayor son",a , b, c
			SiNo
				Escribir "Los valores ordenados de menor a mayor son",a , c, b
			Fin Si
		SiNo
			Escribir "Los valores ordenados de menor a mayor son",c , a, b
		Fin Si
	SiNo
		Si a<c Entonces
			Escribir "Los valores ordenados de menor a mayor son",b,a,c
		SiNo
			Si c<b Entonces
				Escribir "Los valores ordenados de menor a mayor son",c,b,a
			SiNo
				Escribir "Los valores ordenados de menor a mayor son",b,c,a
			Fin Si
		Fin Si
	Fin Si
	
FinAlgoritmo


* De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.

Algoritmo Mes_correspondiente_al_numero

	Escribir "Por favor, introduzca un número del 1 al 12",num
  
	Leer num
  
		Segun num Hacer
    
			1:
      
				Escribir "El numero  ",num," corresponde al mes de enero"
        
			2:
      
				Escribir "El numero  ",num," corresponde al mes de febrero"
        
			3:
      
				Escribir "El numero  ",num," corresponde al mes de marzo"
        
			4:
      
				Escribir "El numero  ",num," corresponde al mes de abril"
        
			5:
      
				Escribir "El numero  ",num, " corresponde al mes de mayo"
        
			6:
      
				Escribir "El numero  ",num, " corresponde al mes de junio"
        
			7:
      
				Escribir "El numero  ",num, " corresponde al mes de julio"
        
			8:
      
				Escribir "El numero  ",num, " corresponde al mes de agosto"
        
			9: 
      
				Escribir "El numero  ",num, " corresponde al mes de septiembre"
        
			10:
      
				Escribir "El numero  ",num, " corresponde al mes de octubre"
        
			11:
      
				Escribir "El numero  ",num, " corresponde al mes de noviembre"
        
			12: 
      
				Escribir "El numero  ",num, " corresponde al mes de diciembre"
        
			De Otro Modo:
      
				Escribir "El numero introducido es incorrecto"
        
		Fin Segun
    
	FinAlgoritmo
  
  ![image](https://user-images.githubusercontent.com/102439544/161353407-2dec21c1-f35a-4b37-b93a-efe63afcec44.png)


  
* De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.

Algoritmo Candidato

	Escribir "Bienvenido a la votacion, las opciones de candidatos son:"
  
	Escribir "candidato A por el partido rojo"
  
	Escribir "candidato B por el partido verde"
  
	Escribir "candidato C por el partido azul"
	
	Leer voto
  
	Segun voto	 Hacer
  
		"A" o "a":
			Escribir "Usted ha votado por el partido rojo"
      
		"B" o "b":
    
			Escribir "Usted ha votado por el partido verde"
      
		"C" o "c":
    
			Escribir "Usted ha votado por el partido azul"
      
		De Otro Modo:
    
			Escribir "Por favor ingrese una opcion valida"
      
	Fin Segun
	
FinAlgoritmo

* Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.

Algoritmo correo_contrasena

	correo1="atrnidad84@gmail.com"
  
	contraseña1="angel365"
  
	Escribir "Bienvenido por favor ingrese su correo"
  
	Leer correo
  
	Escribir "Por favor ingrese su contraseña"
  
	Leer cont
  
	Si correo==correo1 Y cont==contraseña1 Entonces
  
		Escribir "Bienvenido"
    
	SiNo
  
		Escribir "Lo siento, solicitud invalida por favor revisa tu correo o contraseña"
    
	Fin Si
  
FinAlgoritmo
