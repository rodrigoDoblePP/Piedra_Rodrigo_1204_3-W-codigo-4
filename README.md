#Piedra_Rodrigo_1204_3-W-codigo-4
Codigo 4 Del examen

#4-.Desarrolle un algoritmo que permita leer tres valores y almacenarlos en las variables: A, B y C respectivamente.

print (" ")
print ("Piedra Gonzalez Rodrigo 1204 3-W")
print (" ")
print(" ")

# Leer los valores
A = int(input("Agrega el primer valor(a): "))                                 # Solicitar el primer valor
B = int(input("Agrega  el segundo valor (b): "))                               # Solicitar el segundo valor
C = int(input("Agrega el tercer valor (c): "))                                  # Solicitar el tercer valor

if A == B or A == C or B == C:                             #Si las variables son iguales imprime un texto alerta
    print (" ")
    print("Aguas!! : Los valores deben de ser distintos.")   # Si alguno de los valores son iguales muestra una alerta bien botana
    print (" ")
else:                                                        
    print (" ")
    mayor = max ( A,B, C)                                #Buscamos el maximo valor en las 3 variables disponibles (A,B,C)
    menor = min (A, B , C)                               #Buscamos el minimo o menor valor en las 3 variables disponibles (A,B,C)
    print ("El mayor es : ", mayor )                     #imprimimos el mayor de los numeros
    print ("El menor es: "  ,  menor )                   #Imprimimos el menor de los numeros

![imagen](https://github.com/user-attachments/assets/65b6e35e-3002-4ff8-8330-d37b403058ac)
