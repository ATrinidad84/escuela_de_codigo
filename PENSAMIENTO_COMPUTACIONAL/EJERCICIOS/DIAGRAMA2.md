## RETO

1. Realiza un algoritmo y diagrama de flujo de un programa que compare dos números e indique cual es mayor.
Algoritmo mayorr

	Escribir "Ingrese un numero "
  
	Leer num1
  
	Escribir "Ingrese otro numero "
  
	Leer num2
  
	Si num1 <= num2 Entonces
  
		Escribir num2, " Es mayor que ", num1
    
	SiNo
  
		Escribir num1, " Es mayor que ", num1
    
	Fin Si
  
FinAlgoritmo

![image](https://user-images.githubusercontent.com/102439544/161395682-e7b5399e-2f09-43f6-ad79-132c2c089378.png)


2. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

Algoritmo PromedioCalificaciones

i=0

Mientras i<4 Hacer

	i=i+1

	Escribir "ingresa la calificacion", i

	Leer num

	suma=suma + num
	
Fin Mientras

promedio=suma/4

Escribir "el promedio es ",promedio


Si promedio>=6 Entonces

	Escribir "Felicidades aprobaste"

SiNo

	Escribir "Lo siento no aprobaste"

Fin Si

FinAlgoritmo

![image](https://user-images.githubusercontent.com/102439544/161395732-e4fd9192-0b16-4bba-a0da-3014eede53e5.png)



3. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

Algoritmo ParOimpar

Escribir "ingresa un numero"

Leer num

residuo = num MOD 2


Si residuo=0 Entonces
	
	Escribir "el numero es par"
	
SiNo
	
	Escribir "El numero es impar"
	
Fin Si

FinAlgoritmo

![image](https://user-images.githubusercontent.com/102439544/161395756-3ec99dee-894c-45c9-8538-92938b21af56.png)
