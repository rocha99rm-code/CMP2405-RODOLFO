print("Por favor ingrese los valores de Q0 uno por uno")
print("Ejemplo")
print("A1=1")
print("A2=0")
print("A3=1")
print("A4=1")
print("Por favor ingrese los valores de Q1 uno por uno")
print("Ejemplo:")
print("B1=1")
print("B2=0")
print("B3=1")
print("B4=1")

while True:
    try:
        A1 = int(input("Ingrese el valor de A1 (0 o 1): "))
        if A1 in (0, 1):
            break
        print(" Error: Debe ingresar únicamente 0 o 1.\n")
    except ValueError:
        print(" Error: Ingrese solo un número (0 o 1).\n")

while True:
    try:
        A2 = int(input("Ingrese el valor de A2 (0 o 1): "))
        if A2 in (0, 1):
            break
        print(" Error: Debe ingresar únicamente 0 o 1.\n")
    except ValueError:
        print(" Error: Ingrese solo un número (0 o 1).\n")

while True:
    try:
        A3 = int(input("Ingrese el valor de A3 (0 o 1): "))
        if A3 in (0, 1):
            break
        print(" Error: Debe ingresar únicamente 0 o 1.\n")
    except ValueError:
        print(" Error: Ingrese solo un número (0 o 1).\n")

while True:
    try:
        A4 = int(input("Ingrese el valor de A4 (0 o 1): "))
        if A4 in (0, 1):
            break
        print(" Error: Debe ingresar únicamente 0 o 1.\n")
    except ValueError:
        print(" Error: Ingrese solo un número (0 o 1).\n")

print(f"\nQ0 ingresado: {A1} {A2} {A3} {A4}")

print("\nPor favor ingrese los valores de Q1 uno por uno")

while True:
    try:
        B1 = int(input("Ingrese el valor de B1 (0 o 1): "))
        if B1 in (0, 1):
            break
        print(" Error: Debe ingresar únicamente 0 o 1.\n")
    except ValueError:
        print(" Error: Ingrese solo un número (0 o 1).\n")

while True:
    try:
        B2 = int(input("Ingrese el valor de B2 (0 o 1): "))
        if B2 in (0, 1):
            break
        print(" Error: Debe ingresar únicamente 0 o 1.\n")
    except ValueError:
        print(" Error: Ingrese solo un número (0 o 1).\n")

while True:
    try:
        B3 = int(input("Ingrese el valor de B3 (0 o 1): "))
        if B3 in (0, 1):
            break
        print(" Error: Debe ingresar únicamente 0 o 1.\n")
    except ValueError:
        print(" Error: Ingrese solo un número (0 o 1).\n")

while True:
    try:
        B4 = int(input("Ingrese el valor de B4 (0 o 1): "))
        if B4 in (0, 1):
            break
        print(" Error: Debe ingresar únicamente 0 o 1.\n")
    except ValueError:
        print(" Error: Ingrese solo un número (0 o 1).\n")

print(f"Q1 ingresado: {B1}{B2}{B3}{B4}")

num1 = A1 * 8 + A2 * 4 + A3 * 2 + A4 * 1
num2 = B1 * 8 + B2 * 4 + B3 * 2 + B4 * 1
print(f"\nEl valor decimal de Q0 es: {num1}")
print(f"El valor decimal de Q1 es: {num2}") 
resultado = num1 * num2 
print(f"\nEl resultado de la multiplicación es: {resultado}\n")

if A4 == 0 or B4 == 0:
    C1 = 0
else:
    C1 = 1

if A3 == 0 or B4 == 0:
    C2 = 0
else:
    C2 = 1

if A2 == 0 or B4 == 0:
    C3 = 0
else:
    C3 = 1

if A1 == 0 or B4 == 0:
    C4 = 0
else:
    C4 = 1  

if A4 == 0 or B3 == 0:
    D1 = 0
else:
    D1 = 1  

if A3 == 0 or B3 == 0:
    D2 = 0
else:
    D2 = 1

if A2 == 0 or B3 == 0:
    D3 = 0
else:
    D3 = 1

if A1 == 0 or B3 == 0:
    D4 = 0
else:
    D4 = 1

if A4 == 0 or B2 == 0:
    E1 = 0
else:
    E1 = 1

if A3 == 0 or B2 == 0:
    E2 = 0
else:
    E2 = 1      

if A2 == 0 or B2 == 0:
    E3 = 0
else:
    E3 = 1

if A1 == 0 or B2 == 0:
    E4 = 0
else:
    E4 = 1

if A4 == 0 or B1 == 0:
    F1 = 0
else:
    F1 = 1

if A3 == 0 or B1 == 0:
    F2 = 0
else:
    F2 = 1

if A2 == 0 or B1 == 0:
    F3 = 0
else:
    F3 = 1  

if A1 == 0 or B1 == 0:
    F4 = 0
else:
    F4 = 1

print("    ", A1, A2, A3, A4)
print("x   ", B1, B2, B3, B4)
print("_________________")
print("    ", C4, C3, C2, C1)
print("   ", D4, D3, D2, D1, "0")
print("  ", E4, E3, E2, E1, "0 0")
print(" ", F4, F3, F2, F1, "0 0 0")
print("_________________")
print("  ", bin(resultado)[2:])