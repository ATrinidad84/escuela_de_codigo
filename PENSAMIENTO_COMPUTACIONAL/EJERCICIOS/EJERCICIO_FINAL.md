Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.


Ingresa al siguiente link para el resumen final

https://docs.google.com/presentation/d/17LildSvlBpnu-FRpMW1ITRiO21_f3Z0cF9q1Zrs6K5U/edit?usp=sharing

Algoritmo adivina

	intentos=10
  
	num_adivinar = azar(100)+1
    
    
    Escribir "Adivine el numero:"
    
    Leer num_ingresado
    
    Mientras num_adivinar<>num_ingresado & intentos > 1 Hacer
    
        Si num_adivinar>num_ingresado Entonces
            Escribir "Es mayor"
        Sino 
            Escribir "Es menor"
        FinSi
        intentos=intentos-1
        Escribir "Quedan ",intentos," intentos:"
        Leer num_ingresado
    FinMientras
    
    Si num_adivinar=num_ingresado Entonces
		inten_reales=10-intentos
        Escribir "Usted adivino en ",inten_reales," intentos."
    Sino
        Escribir "El numero era: ",num_adivinar
    FinSi
    
FinAlgoritmo


![image](https://user-images.githubusercontent.com/102439544/161396356-5ee3d376-e5b9-4d0f-bc90-d276deb2f650.png)
