# Portafolio de evidencias.

## Semana 9.


Python desde cero
     
                                                                              La función len ()
               En Python, la función len() nos permite obtener la longitud de una cadena de caracteres, o bien, el número de elementos que componen a un objeto. 
                                                  
                                                  La sintaxis correcta para poder utilizar la función len(), es la siguiente:
                                                  
                                                                           
                                                                            len (|L|a| |G|a|l|a|x|i|a|
                                                                                 | | | | | | | | | | | 
                                                                                 | | | | | | | | | | |
                                                                        índice   0 1 2 3 4 5 6 7 8 9 10
                                                                        
 #Función len()

#Opción 1
print("Hola tiene", len("Hola"), "caracteres.")

#Opción 2
longitud = len("La Galaxia")
print("La Galaxia tiene", longitud, "caracteres")




                                                                   Concatenación en Python 3 con el método format()
                          En python, la concatenación es una operación que consiste en la unión de 2 o más cadenas de caracteres mejor conocidos como Strings.
  *Es importante mencionar, que la concatenación puede llevarse a cabo uniendo 2 cadenas de caracteres, o bien, enlazando un único carácter a otra cadena de caracteres.
       
El método format(),nos permite mostrar los valores contenidos en una variable y utilizarlos dentro de una cadena de caracteres, sustituyendo el nombre de la variable con un juego de{}, ubicándolas en la posición donde queremos que se muestren dichos valores.

Algo muy importante de mencionar, es que cuando utilizamos el método format(), la concatenación se puede realizar, sin importar que las variables sean de tipo string o de tipo numérico. 



#Alternativa 1
nombre = "Rodrigo"
edad = 18

print("Hola {} tienes {} años".format(nombre, edad))

#Alternativa 2
nombre = "Rodrigo"
edad = 18

print("Hola {nombre} tienes {edad} años".format(nombre = "Rodrigo", edad = 18))

#Alternativa 3
nombre = "Rodrigo"
edad = 18

print("Hola {1} tienes {0} años".format(edad, nombre))

                             
                             
                                                                     *ejercicio sucesión Fibonacci
                                                                     
 num_uno, num_dos = 0, 1
while num_dos <= 1597:
    print(num_uno, num_dos, end=" ")
    num_uno = num_uno + num_dos
    num_dos = num_uno + num_dos
