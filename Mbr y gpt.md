#MBR Y GPT
## Reglas de las particiones
### MBR
las reglas de las particiones de mbr son las siguientes: 
Solo pueden tener cuatro particiones primarias. 
Cada particion puede tener un m�ximo de 2TB (Haciendo que el m�ximo de capacidad aprovechable en un disco MBR sea de 8TB, puesto que el espacio sobrante se perder�a)
Puedes usar una de esas particiones primarias para convertirla en extended, y tener as� N logicas 
### GPT
Puedes tener N particiones primarias
A diferencia del MBR, supera el l�mite de 2TB por partici�n, y hasta el momento, no hace falta pensar en el l�mite, porque a�n queda tiempo para ello. 