def Media(tot, cant):
    med = tot / cant
    return med


def Moda(data):
    rep = 0
    for i in data:
        exist = data.count(i)
        if exist > rep:
            rep = exist

    moda = []
    for i in data:
        exist = data.count(i)
        if exist == rep and i notin moda:
            moda.append(i)
    return moda


def Mediana(data):
    dOrder = sorted(data)
    n = len(dOrder)
    middle = n / 2
    if n % 2 == 0:
        mediana = (dOrder[middle + 1] + dOrder[middle + 2]) / 2
    else:
        mediana = dOrder[middle + 1] * 1

    return mediana


def Todo(array):
    cant = len(array)
    suma = sum(array)
    media = Media(suma, cant)
    print"Media: {}".format(media)
    moda = Moda(array)
    print"Moda: {}".format(moda)
    mediana = Moda(array)
    print"Mediana: {}".format(mediana)
    return"Total: {}".format(suma)


print Todo([1525, 257, 378, 9543, 7854, 152])
