Algoritmo CosteoYPrecioBase

    // ENTRADA


        Definir nombreProducto Como Cadena
        Definir costoBase, porcentajeGanancia Como Real
        Definir gananciaMonetaria, subtotal, valorIva, precioFinal Como Real
        PORCENTAJE_IVA = 0.19
    
    //PROCESO
    
        ESCRIBIR "Ingrese el nombre del producto:"
        LEER nombreProducto

        ESCRIBIR "Ingrese el costo base del producto:"
        LEER costoBase

        ESCRIBIR "Ingrese el porcentaje de ganancia esperado:"
        LEER porcentajeGanancia


        gananciaMonetaria = costoBase * (porcentajeGanancia / 100)

        subtotal = costoBase + gananciaMonetaria

        valorIva = subtotal * PORCENTAJE_IVA

        precioFinal = subtotal + valorIva

    //SALIDA

    Escribir "Producto: " nombreProducto
    Escribir "Valor monetario de ganancia: " gananciaMonetaria
    Escribir "Subtotal " subtotal
    Escribir "Impuesto IVA (19%): " valorIVA
    Escribir "4. Precio Final de Venta: " precioFinal
    
    
    FinAlgoritmo