# Mocking y Manejo de Errores

Consigna:
Se visitará el endpoint /mockingproducts y deberá corroborarse una respuesta de 50 productos generados con el formato de un producto real del proyecto.
- Se intentará crear un producto **con todos los datos válidos**, el producto debe crearse satisfactoriamente.
- Se intentará crear un un producto  con todos los campos **menos el título y el precio**, los cuales deberían ser requeridos, por lo tanto, se debe recibir un error customizado, en consola debe aparecer una lista de las propiedades requeridas y los tipos (como visto en clase) para reconocer en qué propiedades no se enviaron los datos.

## Mocking de Productos

- Visitar el endpoint `/mockingproducts` para corroborar una respuesta de 50 productos generados con el formato de un producto real del proyecto.

- Intentar crear un producto **con todos los datos válidos**. El producto debe crearse satisfactoriamente si todos los campos requeridos están presentes.

- Intentar crear un producto omitiendo el título y el precio, que son campos requeridos. Debería recibir un error customizado. En la consola, aparecerá una lista de las propiedades requeridas y sus tipos para reconocer en qué propiedades faltan datos.

## Generar Mocking

- Generar un módulo de Mocking para el servidor. Al inicializarse, este módulo deberá ser capaz de generar y entregar 100 productos con el mismo formato que una petición a la base de datos. Este funcionamiento solo se activará en un endpoint específico, `/mockingproducts`.

## Manejo de Errores

- Generar un customizador de errores y establecer un diccionario para los errores más comunes que puedan ocurrir al crear un producto, agregarlo al carrito, entre otros casos.
