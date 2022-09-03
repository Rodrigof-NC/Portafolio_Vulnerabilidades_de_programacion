# Portafolio de evidencias.

## Semana 8.

Python desde cero

                                                                            Bucle o ciclo while
                                                                            
En ocasiones cuando estamos desarrollando un programa, nos encontramos con la necesidad de ejecutar una o más líneas de código en repetidas ocasiones, con lo cual la opción más lógica es duplicar el código de estas instrucciones para que el programa realice la tarea asignada.

Sin embargo, esta alternativa no es la óptima ya que duplicar código puede generar diversos problemas como, por ejemplo, archivos innecesariamente más extensos y difíciles de comprender al momento de querer realizar alguna modificación o actualización del mismo.

*Ante esta situación, en programación contamos con sentencias de repetición de código, las cuales permiten ejecutar una serie de instrucciones o líneas de código de manera controlada dentro de nuestros programas, a las cuales se les conoce como ciclos o bucles.

En Python contamos con el ciclo o bucle while, el cual permite repetir la ejecución de instrucciones, mientras se cumpla una condición, es decir, mientras la conexión del ciclo bucle se cumpla las instrucciones se seguirán ejecutando.


#Ejemplo 1
x=1

while x<3:
    print(x)
    x+=1

print("Fin.")

#Ejemplo 2

x=1
while x<1000:
    print("Rodrigo")
    x+=1
    
    
    
                                                                    Sentencias break y continue
 En Python, los bucles o ciclos pueden ser interrumpidos, o simplemente, dejar de ejecutar el código que se encuentre dentro del bucle e iniciar una nueva iteración.
                       
                       Cabe destacar que en programación una iteración es la repetición de un segmento del código dentro de un programa. 
                            
                            Para lograr la interrupción de una iteración, contamos con las sentencias  break y continue.
                            
                                                                           Sentencia break
                                                               
 En Python, la sentencia break Se utiliza para detener la ejecución de una iteración y salir de ella, con lo cual, el programa podrá continuar con la ejecución del código que se encuentre fuera de nuestro bucle.
                                                                           Sentencia continue
                                                                           
Por otro lado, en Python, también contamos con la sentencia continue, la cual permite detener la iteración actual y volver al principio del bucle para realizar una nueva iteración, si es que la comisión que rige a nuestro bucle se sigue cumpliendo.

*En programación una iteración es la repetición de un segmento de código dentro de un programa.


#Ejemplo para break

print("while con la sentencia break \n")
contador = 0
while contador < 10:
    contador += 1

    if contador == 5:
        break

    print("Valor actual de la variable: ", contador)

print("Fin del prgrama, la sentencia break se ha ejecutado.")



#Ejemplo para continue

print("\nwhile con la sentencia continue \n")
contador = 0
while contador < 10:
    contador += 1

    if contador == 5:
        continue

    print("Valor actual de la variable: ", contador)

