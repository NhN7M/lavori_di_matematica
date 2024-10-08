import math  # inporta il modulo Math.


def hipotenusa(x1, x2):
    h = math.sqrt(x1**2 + x2**2)
    return h  # definiisce il calcolo della hipotenusa.


def cateto1(x2, x3):
    c1 = math.sqrt(x2**2 - x3**2)
    return c1  # definiisce il calcolo dell primo cateto.


def cateto2(x2, x3):
    c2 = math.sqrt(x2**2 - x3**2)
    return c2  # definiisce il calcolo dell secondo cateto.


x = input(
    "quiere calcular: cateto b, cateto c o la hipotenusa de tu triangulo rectangulo? :"
).lower()  # chiede se si vuole calcolare un cateo o la hipotenusa scritto con o senza maiuscole.

if x == "hipotenusa":
    cat1 = float(input("cateto b:"))
    cat2 = float(input("cateto c:"))
    print(
        "la hipoenusa es:{:.3f}".format(hipotenusa(cat1, cat2))
    )  # calcola la hipotenusa con un risultato a tre decimali.

elif x == "cateto b":
    hipo = float(input("hipotenusa:"))
    cat2 = float(input("cateto c:"))
    print(
        "el cateto b es:{:.3f}".format(cateto1(hipo, cat2))
    )  # calcola il cateto b con un risultato a tre decimali.


elif x == "cateto c":
    hipo = float(input("hipotenusa:"))
    cat1 = float(input("cateto b:"))
    print(
        "el cateto c es:{:.3f}".format(cateto2(hipo, cat1))
    )  # calcola il cateto c con un risultato a tre decimali.

else:
    print(
        "Lo que has intoducido o esta mal escrito o no se puede calcular"
    )  # da un risultato nel caso non si compia nessuna delle regole seguenti.
