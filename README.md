#Examen Del Primer Parcial. Codigo Creado Por Ramirez Torres Angel Manuel
- Ingresar un número natural por teclado. Se desea saber y mostrar
si es par o impar.


print(" ")
d = "Examen del primer parcial:" #Se declara la variable 'd'
a = "/ Alumno: Ramirez Torres Angel Manuel"#Se declara la variable 'a'
b = "/ Grado y Grupo: 3°W"#Se declara la variable 'b'
c = "/ Mi numero de contro es: 1206"#Se declara la variable 'c'
espacio = (" ")#Se declara la variable 'espacio'
info = d +espacio + a + espacio + b + espacio + c #Aqui se juntan los valores (d, a, b, c, espacio) para crear una sola variable 
print (info)#Muestra el contenido de la variable 'info'
print(" ")


# Solicita al usuario que ingrese un número 
numero = int(float(input("Ingrese un número natural: ")))

# Verifica si el número es negativo
if numero < 0:
    print("Por favor, ingrese un número natural (cero o positivo).")
else:
    # Determina si el número es par o impar
    if numero % 2 == 0:
        # Si el residuo de la división entre 2 es 0, el número es par
        print(f"El número {numero} es par.")
    else:
        # Si el residuo de la división entre 2 no es 0, el número es impar
        print(f"El número {numero} es impar.")



![image](https://github.com/user-attachments/assets/73d3e21e-bbff-4e33-80b0-8d2e35e3d120)
![image](https://github.com/user-attachments/assets/4561ad28-26dd-4573-b2f7-6e3d6c50209d)
![image](https://github.com/user-attachments/assets/1517098c-dcc3-4340-9ea0-308bf847d589)

