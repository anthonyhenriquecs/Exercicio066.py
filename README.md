# Exercicio066.py

n = s = cont = 0
while True:
    n = int(input('Digite um numero:'))
    if n == 999:
        break
    cont += 1
    s += n
print(f'A soma dos {cont} valores é: {s}')
