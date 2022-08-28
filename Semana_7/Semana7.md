# Portafolio de evidencias.

## Semana 7.
Python desde cero
                                                                   Operadores de asignación:
                                                                   
         Un operador de asignación, como su nombre lo indica, se encarga de asignar un valor a una variable de la izquierda basado en el valor de la derecha.
         El operador de asignación más utilizado es el igual (=), el cual asigna el valor que se encuentra del lado derecho a la variable del lado izquierdo.
                                                          
                                                            Es decir, x =y asigna el valor de y a x

                                                       En Python, contamos con los siguientes operadores de asignación:
                                                       
                        |            Nombre           |        Operador     |       Implemetación      |     Expresión equivalente       |
                        |         Asignación          |            =        |           X = Y          |            X = Y                |
                        |    Asignación de suma       |           +=        |          X += Y          |            X = X+Y              |
                        |    Asignación de resta      |           -=        |          X -= Y          |            X = X-Y              |
                        |Asignación de multiplicación |           *=        |          X *= Y          |            X = X*Y              |
                        |Asignación de división       |           /=        |          X /= Y          |            X = X/Y              |
                        |Asignación de devisión entera|           //=       |          X //= Y         |            X = X//Y             |
                        |Asignación de exponente      |           **=       |          X **= Y         |            X = X**Y             |
                        |Asignación de módulo o resta |            %=       |          X %=  Y         |            X = x%Y              |
                        
                        
                        
     nombre = "Hola "
nombre += input("Escribe tu nombre: ")

print(nombre, ", esto es el incremento y decremento de una variable \n")

print("incremento o aumento:")
x=1
print("El valor inicial de x es:", x)

x+=1
x+=1
x+=1
x+=1
print("El valor final de x es:", x, "\n")

print("decremento o disminución:")
print("El valor inicial de x es:", x)

x-=1
x-=1
x-=1
x-=1
print("El valor final de x es:", x)




                                                               Los parámetros sep y end

La función print(), es quizás una de las herramientas más útiles en el lenguaje de programación Python, al momento de interactuar con los usuarios de nuestros programas.
Por tal motivo, es indispensable conocer la manera en que podemos manipular dichas impresiones en pantalla, con la finalidad de tener el control completo del texto a mostrar.
                                                                       Parámetro end
                                                                       
                El parámetro end, se utiliza para agregar cualquier cadena de caracteres al final de la salida e impresión en pantalla de la función print().
Además, por defecto la función print() genera un salto de línea al terminar su ejecución, sin embargo, con ayuda del parámetro end, es posible evitar este salto de línea.
                                                                        Parámetro sep

En ocasiones, es posible que deseemos imprimir múltiples valores de manera legible utilizando la función print().
El parámetro sep, se utiliza para dar formato a las cadenas de caracteres que deben imprimirse en pantalla, agregando un separador entre las cadenas qué se imprimirán.


#Ejemplo para el parametro end

print("Esto es un", end="-*/")
print("ejemplo")


#Ejemplo para el parametro sep

print("1","2","3","4","5", sep="-")
