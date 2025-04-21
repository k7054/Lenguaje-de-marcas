# Ejercicio 3

## Descripción
Este ejercicio valida un archivo XML que representa una heladería con diferentes tipos de helados y sus cantidades, utilizando un esquema XSD.

## Archivos
- **heladeria.xsd**: Define la estructura y las restricciones del archivo XML de la heladería.
- **heladeria1.xml**: Contiene los datos de la heladería que se validan contra el esquema XSD.

## Estructura del XML
El archivo XML incluye:
- Elemento `helado` con un atributo `fabricación` que indica la fecha de fabricación.
- Subelementos como `chocolate`, `fresa`, `vainilla`, `turron` y `nata` con restricciones en las cantidades.

## Validación
Para validar el archivo XML, asegúrate de que el esquema XSD esté en la misma carpeta y que el atributo `xsi:noNamespaceSchemaLocation` apunte correctamente al archivo `heladeria.xsd`.
