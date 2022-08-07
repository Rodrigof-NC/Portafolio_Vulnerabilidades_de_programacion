# Portafolio de evidencias.

## Semana 4.

Python desde cero
                              
                                                                Tipos de datos en Python
 
 En programación, un tipo de dato, es un atributo de los datos que indica a la computadora y al programador, sobre la clase de daros que se va manejar.

                                                     En python, existen los siguientes tipos de datos:
                                                     
                                                     1.- Enteros y Larrgos
                                                     2.- Flotantes
                                                     3.- Números complejos
                                                     4.- Cadenas
                                                     5.- Booleanos
 
 Los números enteros, son aquellos que no tienen decimales, tanto positivos como negativos.
 En python se pueden representar mediante el tipo int (entero) o el tipo long (largo).
 
                                                                       Los números flotantes o reales, son los que tiene decimales, tanto positivos como negativos.
                                                                       En phyton se expresan mediante el tipo float.
                                                                       
 Los números complejos, son aquellos que tienen una parte real y una parte imaginaria.
 *La mayor parte de lenguajes de programación carecen de este tipo, aunque son muy utilizados por ingenieros o científicos en general.
 En python se expresan mediante el tipo complex. 
                                           
                                                                       Cadenas: Las cadenas o tmabién conocidas como strings, no son más que texto encerrado entre                                                                              comillas simples (`Cadena`) o dobles ("Cadena").
                                                                       También es posible encerrar una cadena entre triples comillas (simples o dobles).
                                                                       
De esta forma podemos escribir el texto en varías líneas, y al imprimir la cadena, se representarán los saltos de línea que introducimos sin tener que recurrir al crácter /n.

                                                                      El tipo booleano, sólo puede tener dos valores: True(cierto) y False(falso). Estos valores son 
                                                                      especialmente importantes para las expresiones condicionales y los bucles.
                                                                      
                                                       Códigos hechos: 
#Tipo de dato entero o largo
numero = 15
print(numero, type(numero))

#Tipo de dato flotante
numero_flotante = 15.5
print(numero_flotante, type(numero_flotante))

#Tipo de dato Número complejo
numero_complejo = 5 + 6j
print(numero_complejo, type(numero_complejo))

#Tipo de dato String
nombre = "Rodrigo"
print(nombre, type(nombre))

#Tipo de dato Booleano
verdadero_falso = 3 == 3
print(verdadero_falso, type(verdadero_falso))

---------------------------------------------------------------------------------------------

palabra = input("Introduce una palabra: ")
num_int = int(input("Introduce un número entero: "))
num_float = float(input("Introduce un número flotante"))
num_complex = complex(input("Introduce un npumero complejo: "))

print("Strig: ",palabra)
print("Entero: ", + num_int)
print("Float: ", num_float)
print("Número complejo; ", num_complex)

----------------------------------------------------------------------------------------------
nombre = input("¿Cuál es tú nombre?: ")
print("Hola " + nombre + ", vamos a realizar una suma.")

num_uno = int(input("Porfavor introduce el primer valor: "))
num_dos = int(input("Porfavor introduce el segundo valor: "))

resultado = num_uno + num_dos

print(nombre + " El resultado de la suma es: ", resultado)

-----------------------------------------------------------------------------------------------
