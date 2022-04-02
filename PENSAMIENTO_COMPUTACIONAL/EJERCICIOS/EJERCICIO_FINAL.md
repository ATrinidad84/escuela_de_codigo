Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.


Ingresa al siguiente link para el resumen final

https://docs.google.com/presentation/d/17LildSvlBpnu-FRpMW1ITRiO21_f3Z0cF9q1Zrs6K5U/edit?usp=sharing

Algoritmo Adivina_el_numero

	intentos=10
	numadivinar = azar(100)+1
   	Escribir "JUEGO ADIVINA EL NUMERO" 
	Escribir "Por favor ingresa un número:"
    	Leer num
	
	Mientras numadivinar<>num Y intentos > 1 Hacer
		
        Si numadivinar>num Entonces
            Escribir "El número es mayor, intente nuevamente"
        Sino 
            Escribir "El número es menor, intente nuevamente"
   	FinSi
        intentos=intentos-1
        Escribir "Aún te quedan:  ",intentos," intentos:"
        Leer num
    	FinMientras
    
    	Si numadivinar=num Entonces
		intentos_tot=(10-intentos)+1
        Escribir "Bien hecho, has adivinado en ",intentos_tot," intentos."
    	Sino
        Escribir "¡Lástima no has adivinado! El número era:  ",numadivinar
    	FinSi
    
	FinAlgoritmo
	
	
![image](https://user-images.githubusercontent.com/102439544/161402988-6e8e2d59-96bb-4707-afd7-4ad7aba60658.png)




