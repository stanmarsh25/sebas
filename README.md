# código el ahorcado
 He creado funciones para poder definir la palabra que el usuario eligirá.
 usamos los comandos for y in para la palabrajuego
 
 Luego Creamos una función que nos permita generar la palabra incompleta
 En esta función lo que estamos logrando es crear la base donde irá la palabra.
 Mediante los comandos logramos que en la base de la palabra tenga al comienzo la primera palabra y al final la ultima palabra.
 
     for i in palabraJuegoCompleta:
        palabraIncompleta.append ("_")
    palabraIncompleta [0]= palabraJuegoCompleta [0]
    palabraIncompleta [len (palabraIncompleta)-1]= palabraJuegoCompleta [len (palabraJuegoCompleta)-1]
    
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


    
