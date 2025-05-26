# dados
# Lista para guardar os números primos
primos = []

# Verifica todos os números de 2 até 100
for numero in range(2, 101):
    eh_primo = True
    for i in range(2, numero):
        if numero % i == 0:
            eh_primo = False
            break
    if eh_primo:
        primos.append(numero)

# Mostra os números primos encontrados
print("Números primos de 1 a 100:")
print(primos)

# Mostra quantos foram encontrados
print("Total de números primos:", len(primos))# Lista para guardar os números primos
primos = []

# Verifica todos os números de 2 até 100
for numero in range(2, 101):
    eh_primo = True
    for i in range(2, numero):
        if numero % i == 0:
            eh_primo = False
            break
    if eh_primo:
        primos.append(numero)

# Mostra os números primos encontrados
print("Números primos de 1 a 100:")
print(primos)

# Mostra quantos foram encontrados
print("Total de números primos:", len(primos))