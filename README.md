# Código el ahorcado
 Como se hizo?
 Creamos una función que permita al usuario colocar una palabra, sea la que el elija.
 
 Luego Creamos una función que nos permita generar la palabra incompleta
 En esta función lo que estamos logrando es crear la base donde irá la palabra.
 Mediante los comandos logramos que en la base de la palabra tenga al comienzo la primera palabra y al final la ultima palabra.
 
     for i in palabraJuegoCompleta:
        palabraIncompleta.append ("_")
    palabraIncompleta [0]= palabraJuegoCompleta [0]
    palabraIncompleta [len (palabraIncompleta)-1]= palabraJuegoCompleta [len (palabraJuegoCompleta)-1]
    
    
Esto logrará que la palabra que nosotros elegimos se vuelva incompleta y solo aparezca el primer y ultima letra de la palabra.
    
Luego creamos una función que nos permita saber si la letra que ponemos existe.
Definimos que si la letra esta en la palabra lo reemplaze.

Para poder reemplazar la letra creamos una función que reemplaze la palabra tanto completa como incompleta

y para esto definimos la función que las letras que no pertenecen a las palabras vayan al [] , y se coloquen ahí.

Luego creamos el menú de inicio que consta de 
Juego del ahorcado!
Ingrese la palabra con la que jugará: 

Usamos las variables para poder reemplazar las palabras.
Sean las correctas o las no correctas.

De igual manera si ganamos que salga !GANO EL JUEGO! y si pierdes pues te quedaste sin vidas.

EJEMPLO:
¡JUEGO DEL AHORCADO!
Ingrese la palabra con la que jugara: 
PROGRAMACION
P_________________N
P___O___A__A____O_N
PROGRAMACIÓN
¡Gano el juego! la palabra era:  ['P', 'R', 'O', 'G', 'R', 'A', 'M', 'A', 'C', 'I', 'O', 'N']
    
