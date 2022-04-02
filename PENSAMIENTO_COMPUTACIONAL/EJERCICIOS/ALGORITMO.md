# REALIZA UN ALGORITMO SOBRE ALGUNA ACTIVIDAD EN TU VIDA COTIDIANA.

Lavarse las manos.

Tener jabon, lavabo con acceso a agua.

Abrir el lavabo

Cerrar el grifo

Mojarse las manos

untar jabon en las manos, con movimientos circulares sobre toda la superficie de las manos.

Abrir el lavabo

Enjuagar las manos hasta que ya no tengas jabon en las manos

Cerrar el lavabo

Listo titnes tus manos limpias


# DESARROLLA UN ALGORITMO QUE CALCULE LA EDAD DE UNA PERSONA CON BASE A LA OBTENCION DE SU FECHA DE NACIMIENTO.


Algoritmo EdadActual

Escribir "Ingresa el dia actual"
Leer diaActual
Escribir "Ingresa el mes actual"
Leer mesActual
Escribir "Ingresa el año actual"
Leer añoActual


Escribir "Ingresa el dia de nacimiento"
Leer diaNacimiento
Escribir "Ingresa el mes de nacimiento"
Leer mesNacimiento
Escribir "Ingresa el añode nacimiento"
Leer añoNacimiento



edad = añoActual - añoNacimiento
si mesNacimiento > mesActual Entonces
	edad = edad - 1
	
SiNo
	si mesNacimiento == mesActual Entonces
		si diaNacimiento > diaActual Entonces
			edad = edad - 1
		FinSi
		
	FinSi
FinSi
Escribir "Tu edad actual es ", edad, " años" FinAlgoritmo
