def encontrar_mayor(num1, num2, num3):
  if num1 > num2 and num1 > num3:
    mayor = num1
  elif num2 > num3:
    mayor = num2
  else:
    mayor = num3
  return mayor

# Pedimos al usuario los números
num1 = int(input("Ingrese el primer número: "))
num2 = int(input("Ingrese el segundo número: "))
num3 = int(input("Ingrese el tercer número: "))

# Llamamos a la función   
 y mostramos el resultado
resultado = encontrar_mayor(num1, num2, num3)
print("El número mayor es:", resultado)
