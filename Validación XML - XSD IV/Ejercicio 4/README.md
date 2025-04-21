# Ejercicio 4

## Descripción
Este ejercicio valida un archivo XML que representa una heladería con combinaciones específicas de sabores de helado, utilizando un esquema XSD.

## Archivos
- **heladeria.xsd**: Define la estructura y las restricciones del archivo XML de la heladería.
- **heladeria2.xml**: Contiene los datos de la heladería que se validan contra el esquema XSD.

## Estructura del XML
El archivo XML incluye:
- Elemento `helado` con combinaciones específicas de sabores (`fresa` y `chocolate`, o `vainilla` y `chocolate`).

## Validación
Para validar el archivo XML, asegúrate de que el esquema XSD esté en la misma carpeta y que el atributo `xsi:noNamespaceSchemaLocation` apunte correctamente al archivo `heladeria.xsd`.
