

def zad1(kod1, kod2):
    kod1a, kod1b = kod1.split("-")
    kod2a, kod2b = kod2.split("-")

    print("Lista kodów znajdujących się pomiędzy {} a {}".format(kod1, kod2))
    for i in range(int(kod1b), 1000):
        print(kod1a + "-" + str(i))

    for i in range(0, (int(kod2b) + 1)):
        i = str(i)
        print(kod2a + "-" + i.rjust(3, '0'))


kod_1 = "79-900"
kod_2 = "80-155"

zad1(kod_1, kod_2)


def zad2():
    listx = int(input("\n\nLista zaczyna się od cyfry '1' i kończy na 'x'. Podaj 'x': "))
    lista = list(range(1, listx + 1))

    listb = input("Podaj elementy listy 'b' oddzielając je przecinkami: ")
    listb = list(map(int, listb.split(",")))

    print("Różnica między listami: ")
    print(list(set(lista) - set(listb)))


zad2()


def zad3(x, y, z):
    print("\n\nLista liczb od {} do {} z przeskokiem co {}".format(x, y, z))
    x = float(x * 2)
    y = float(y * 2)
    z = float(z * 2)
    x, y, z = int(x), int(y), int(z)
    for i in range(x, (y+1), z):
        print(i/2)


zad3(2, 5.5, 0.5)
