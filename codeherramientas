# Andres Felipe Cruz
# Herramientas


print("Bienvenidos a la cafeteria")
print("Escriba su rol (Estudiante o Profesor)")



#Las variables que usare para resolver el problema
descuento = None
rolaceptado = False
total = 0
codigos = ""






#Un ciclo para que la persona elija el rol y solo poder seguir si el rol esta bien ingresado
while not rolaceptado:
    rol = input().lower()     
    if rol == "estudiante":
        rolaceptado = True
        descuento = 30

        print("¿Estás en el programa de becas?")
        beca = input().lower()

        if beca == "si":
            descuento = 50

    elif rol == "profesor":
        rolaceptado = True
        descuento = 20

    else:
        print("ingrese una opcion valida")
        print("Estudiante o Profesor")



print("Ingrese su cédula")
cedula = input()




#Un menu para poder agregar mas de un item en la lista y que el usuario decida cuando salir. En el caso que elija una opcion erronea le envia un mensaje.
comprar  = False
while not comprar:
    
    
    print("Elija la opcion")
    print("1. Registrar producto a comprar")
    print("2. Salir")

    
    op = int(input())

    if op == 1:
        print("Ingrese el código del producto")
        codigo = input()
        print("Ingrese la cantidad")
        cantidad = int(input())
        print("Costo del producto (Valor de un solo producto)")
        costo = int(input())


        total = total + (cantidad*costo)

        codigos = codigos + " ," + codigo 
    

    elif op == 2:
        print("Gracias por su compra")
        comprar = True

    else:
        print("Elija una opcion valida.")    



#Aqui hago el calculo para hacer el descuento de su compra total.
total = total - (total * (descuento/100))


#Un print para mostrar el rol, cedula, total a pagar y los codigos de los productos
print("El", rol , "con cédula", cedula, "debe pagar", "$",total,"por el/los producto/s", codigos)





