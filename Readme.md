# Detalles de la tarea de esta unidad

## Enunciado

- Casos de uso.

El responsable de almacén tiene como única tarea servir los pedidos de los socios. Aparece en el caso de uso "Cumplimentar pedidos". Si bien es una tarea complicada que se corresponde con la siguiente descripción:

El responsable de almacén revisa a diario los pedidos almacenados en el sistema para cumplimentarlos y enviarlos. El proceso consta de varios pasos:
1. El responsable recupera la lista de pedidos pendientes.
2. Selecciona el más antiguo.
3. Busca los artículos que lo componen en el almacén para generar el paquete y disminuye el stock de los artículos.
4. Cuando reúne todos los artículos los empaqueta para enviarlos al socio indicando al sistema que ya puede añadir el pedido a la ruta que le corresponde según la población del socio que ha hecho el pedido.
5. Como con los artículos comprados se debe adjuntar un albarán con el resumen del pedido, se genera este albarán automáticamente.
6. El sistema debe indicar al responsable de almacén en qué zona tiene que almacenar el pedido mientras llega el día de hacer el reparto.
7. Cambiar el estado del pedido a "almacén".

Contemplar como caso alternativo que no haya artículos disponibles en el almacén, en cuyo caso se realiza una petición a fábrica.

## Tu tarea consiste en elaborar la documentación del caso de uso "Cumplimentar pedidos" rellenando los siguientes apartados:

- Nombre.
- Actores.
- Propósito.
- Precondiciones.
- Flujo normal.
- Flujo alternativo.
- Postcondiciones.

Elabora el diagrama de secuencia para el caso de uso "Cumplimentar pedidos".
Elabora el diagrama de colaboración para el caso de uso "Cumplimentar pedidos".
Elaborar el diagrama de actividad para el caso de uso "Cumplimentar pedidos".

Describe a qué objeto puede corresponder el siguiente diagrama de transición de estados indicando cuál es la funcionalidad que representa.
