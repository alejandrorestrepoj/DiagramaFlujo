# Lapices

Realice un algoritmo para determinar cuánto se debe pagar por equis cantidad de lápices considerando que si son 1000 o más el costo es de $85 cada uno; de lo contrario, el precio es de $90. Represéntelo con el pseudocódigo y el diagrama de flujo.

...
Inicio
Escribir"Insertar la cantidad de lapices que desea comprar"
Leer cant_lapices
Si cant_lapices >= 1000
    P = 85 * cant_lapices
Si no:
    P = 90 * L
Fin si
Escribir "El valor total es: ", P
Fin
...
Un almacén de ropa tiene una promoción: por compras superiores a $250 000 se les aplicará un descuento de 15%, de caso contrario, sólo se aplicará un 8% de descuento. Realice un algoritmo para determinar el precio final que debe pagar una persona por comprar en dicho almacén y de cuánto es el descuento que obtendrá. Represéntelo mediante el pseudocódigo y el diagrama de flujo.
...
Inicio
Mensaje"Inserte el precio total de su compra."
Leer Pt
Si Pt > 250000
    D = Pt * 0.15
Si no:
    D = Pt * 0.8
Fin si
Escribir "El descuento total es: ", D
PrecioFinal = Pt - D
Escribir "El precio final es: ", PrecioFinal
Fin
...
El director de una escuela está organizando un viaje de estudios, y requiere determinar cuánto debe cobrar a cada alumno y cuánto debe pagar a la compañía de viajes por el servicio. La forma de cobrar es la siguiente: si son 100 alumnos o más, el costo por cada alumno es de $65.00; de 50 a 99 alumnos, el costo es de $70.00, de 30 a 49, de $95.00, y si son menos de 30, el costo de la renta del autobús es de $4000.00, sin importar el número de alumnos.

...
Inicio
Mensaje"Ingresar la cantidad de estudiantes que van al viaje de estudios."
Leer EstTotal
Si EstTotal >= 100
    CostoBus = EstTotal * 65
Sino EstTotal >= 50
    CostoBus = EstTotal * 70
Sino EstTotal >= 30
    CostoBus = EstTotal * 95
Sino
    CostoBus = 4000
Fin si
Escribir"El precio total del bus es: ", CostoBus
Fin