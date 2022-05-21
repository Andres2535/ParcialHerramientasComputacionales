
**¿Qué problema es?**
- Una cafeteria donde el descuento se da en base al rol del comprador.

**¿Qué modelo computacional resulve el problema?**
  1- Primero reduje al problema en varios problemas menores
  2- identifique que tipo de solucion necesitaban dichos problemas
  3- Realice: operacion *matematicas - ciclos - verificaciones*
  
 **¿Qué recibe como entrada?**
   Los datos que recibo como entrada son:
       1. Rol del comprador
       2. Cedula del comprador
       3. Codigo del producto
       4. Cantidad del producto
       5. Costo del producto (Por unidad)
       6. Operacion que desea realizar (Comprar o salir del programa)
 
 **¿Cuál sería su salida?**
    Al final del programa se imprime un mensaje que contienen: *rol, cedula, total a pagar y el código del producto*
    
 **¿Cómo lo calcula?**
    Para calcular el total a pagar, primero debo conocer el rol, luego hago una multiplicacion entre los productos y su cantidad para 
    luego sumarlos mientras se repite el ciclo ***(Uso esta formula: total = total + (cantidad*costo)***, luego de que el comprador 
    decida que no va a agregar más productos aplico el descuento ***(Uso esta formula: (total = total - (total * (descuento/100)))*** 
    y así calculo el total a pagar.
