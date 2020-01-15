nrRepetari = input("Dati numarul de repetari: ")
nrPicioare = 6

for i in range(int(nrRepetari)):
    nrPicioare = int(nrPicioare) - 2 + 6

print("Numarul final de picioare: "+ str(nrPicioare))
