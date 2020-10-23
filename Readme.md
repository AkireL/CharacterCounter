# Prueba 

## Instrucciones
Al pulsar el botón Calcular número de la suerte, deben ocurrir los siguientes casos:

- Validar que el número tenga entre 14 y 16 dígitos, si la validación no es exitosa, mostrar una alerta al usuario
- Imprimir en el Log, el número de veces que se repite un número
- En el campo Label  que se encuentra por debajo del botón, mostrar cual es el número que se repite más veces

## Comentarios

La prueba se realizo con javascript.

Pasos: 
 - Cree un archivo html
 - Cree la estructura html
 - Cree los tag que se requerian
 - Agrege el evento click del tag input
 - Capturé el evento para validar la entrada
    - Valide el tamaño de la entrada 
     Si el número de caracteres no coinciden con lo requerido se muestra un mensaje al usuario
     en otro caso cuento el número de repeticiones y muestro en log las repeticiones, posteriormente ordeno el array y muestro en el tag el primer elemento del array.