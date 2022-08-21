# Portafolio de evidencias.

## Semana 6.
Python desde cero
                                                                
                                                                Operadores Relacionales
     En Python, los operadores relacionales son símbolos que se usa para comparar dos valores, y generalmente son utilizados para comparar dos valores, y generalmente        son utilizados en las sentencias condicionales para la toma de decisiones.
     Al utilizar operadores relacionales dentro de una sentencia condicional, si el resultado de la comparación es correcto, la expresión o condición es considerada          verdadera (true), y en caso contrario será falsa (false).
     
     
                     | Operador |              Nombre                  |           Ejemplo           |              Significado                    |
                     |    <     |             Menor que                |           5 < 4             |             5 es menor que 4                |
                     |    >     |             Mayor que                |           7 > 5             |             7 es mayor que 5                |
                     |   ==     |              Igual a                 |           5 == 5            |             5 es igual a 5                  |
                     |   !=     |       No igual a (diferente)         |           4 != 5            |             4 no es ugual a 5               |
                     |   <=     |       Menor que o igual a            |           6 <= 6            |             6 es menor que o igual a 6      |
                     |   >=     |       Mayor que o igual a            |           9 >= 5            |             9 es mayor que o igual a 5      |
                     
                     


print("Introduce los números a comparar: \n")

num_uno = int(input("Introduce el primer número: "))
num_dos = int(input("Introduce el segundo número: "))

print("\n Los números a comparar son: ", + num_uno, " y ", num_dos, "\n")

if num_uno == num_dos:
    print("Es igual...")
if num_uno != num_dos:
    print("Es diferente...")
if num_uno < num_dos:
    print("Es menor...")
if num_uno > num_dos:
    print("Es mayor...")
if num_uno <= num_dos:
    print("Es menor o igual...")
if num_uno >= num_dos:
    print("Es mayor o igual...")
    
    
    
   
                                                             Operadores lógicos:
   En ocasiones, es necesario utilizar más de 2 condiciones lógicas dentro de una misma condición, con lo cual nos vemos en la necesidad de implementar múltiples                                                   operadores relacionales para crear una expresión lógica mucho más compleja.
    
   Sin embargo, no es posible colocar 2 condiciones lógicas dentro de una misma condición, sin el apoyo de algún elemento qué les indique a nuestros programas, que se                                          realizará en la unión de 2 o más condiciones lógicas Dentro de una misma expresión.

   Para este tipo de situaciones existen los operadores lógicos, los cuales, permiten agrupar condiciones lógicas dentro de una misma condición. Es decir, con los                            operadores lógicos tenemos la posibilidad de utilizar múltiples operadores dentro de una misma condición lógica.
     


En python, contamos con tres tipos de operadores lógicos:

                                                        | Operador lógico  |   Símbolo   |
                                                        |    Conjunción    |    and      |
                                                        |   Disyunción     |    or       |
                                                        |   Negación       |    not      |
                                                        
                                                        
  
  #Conjunción

print("Conjunción (and)")

num_uno = int(input("Escibre un número mayor a 2 y menor a 5:"))

if num_uno > 2 and num_uno < 5:
    print("El número ", num_uno, " cumple con la condcición.\n")
else:
    print("El número ", num_uno, " NO cumple co la condición.\n")

#Disyunción
print("Disyunción (or)")

palabra = input("Para cumplir con la condición escibe 'si' o 'yes': ")

if palabra == "si" or palabra == "yes":
    print("La condición se ha cumplido.\n)")
else:
    print("La condición NO se ha cumplido.\n)")

#Negación
print("Negación (not)")

num_uno = int(input("Introduce un número igual a 5: "))

if not num_uno == 5:
    print("\n El número es diferente a cinco y SI cumple la condición.\n")
else:
    print("\n El número es igual a cinco y NO cumple la condición.\n")
