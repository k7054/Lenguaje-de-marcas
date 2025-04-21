# Ejercicio 2

## Descripción
Este ejercicio valida un archivo XML que contiene una lista de alumnos utilizando un esquema XSD. Cada alumno tiene información como nombre, dirección, teléfono y DNI.

## Archivos
- **alumnos.xsd**: Define la estructura y las restricciones del archivo XML de alumnos.
- **Alumnos.xml**: Contiene una lista de alumnos que se validan contra el esquema XSD.

## Estructura del XML
El archivo XML incluye:
- Atributo `dni` con un formato específico.
- Elementos como `nombre`, `direccion` (con subelementos `calle`, `numero`, `ciudad`, `provincia`) y `telefono`.
- Soporte para múltiples direcciones y teléfonos por alumno.

## Validación
Para validar el archivo XML, asegúrate de que el esquema XSD esté en la misma carpeta y que el atributo `xsi:noNamespaceSchemaLocation` apunte correctamente al archivo `alumnos.xsd`.
