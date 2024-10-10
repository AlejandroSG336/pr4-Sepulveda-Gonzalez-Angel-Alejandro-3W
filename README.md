# pr4-Sepulveda-Gonzalez-Angel-Alejandro-3W

# 4. Función que calcula el total de una factura después de aplicar el IVA

def calcular_factura(cantidad_sin_iva, iva=21):

# Calculamos el IVA multiplicando la cantidad base por el porcentaje de IVA
   
total = cantidad_sin_iva + (cantidad_sin_iva * iva / 100)

# Devolvemos el total de la factura con IVA incluido

return total

# Solicitamos la cantidad sin IVA al usuario y la convertimos a un número flotante

cantidad = float(input("Introduce la cantidad sin IVA: "))

# Solicitamos el IVA al usuario, o usamos el 21% por defecto si no lo ingresa

iva = input("Introduce el porcentaje de IVA (presiona Enter para usar 21%): ")

# Si el usuario no introduce nada, usamos el IVA por defecto (21%)

if iva == "":

total_con_iva = calcular_factura(cantidad)

else:

total_con_iva = calcular_factura(cantidad, float(iva))

# Mostramos el total calculado

print(f"El total de la factura con IVA es: {total_con_iva}")
![image](https://github.com/user-attachments/assets/6004e5fb-4185-4099-b0ee-5b43b7c98506)
![image](https://github.com/user-attachments/assets/ec98f022-4727-4d91-a5d5-60926e90d29b)
![image](https://github.com/user-attachments/assets/fb195a73-f32b-4281-b40f-7190e607cac7)
