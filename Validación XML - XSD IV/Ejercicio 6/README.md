# Ejercicio 6

## Descripción
Este ejercicio valida un archivo XML que representa una librería con información sobre libros, utilizando un esquema XSD.

## Archivos
- **libreria.xsd**: Define la estructura y las restricciones del archivo XML de la librería.
- **Libreria.xml**: Contiene los datos de la librería que se validan contra el esquema XSD.

## Estructura del XML
El archivo XML incluye:
- Elementos como `codigo`, `direccion`, `telefono`, `propietario` (con subelementos `nombre` y `telefono`).
- Elemento `libro` con subelementos como `titulo`, `autor`, `formato`, `publicacion`, `precio` y `cantidad`.

## Validación
Para validar el archivo XML, asegúrate de que el esquema XSD esté en la misma carpeta y que el atributo `xsi:noNamespaceSchemaLocation` apunte correctamente al archivo `libreria.xsd`.
