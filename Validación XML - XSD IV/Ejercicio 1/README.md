# Ejercicio 1

## Descripción
Este ejercicio valida un archivo XML que representa la información de un alumno utilizando un esquema XSD. El esquema define las reglas para los datos del alumno, como el formato del DNI, la dirección y los números de teléfono.

## Archivos
- **alumno.xsd**: Define la estructura y las restricciones del archivo XML del alumno.
- **Alumnos.xml**: Contiene los datos de un alumno que se validan contra el esquema XSD.

## Estructura del XML
El archivo XML incluye:
- Atributo `dni` con un formato específico.
- Elementos como `nombre`, `direccion` (con subelementos `calle`, `numero`, `ciudad`, `provincia`) y `telefono`.

## Validación
Para validar el archivo XML, asegúrate de que el esquema XSD esté en la misma carpeta y que el atributo `xsi:noNamespaceSchemaLocation` apunte correctamente al archivo `alumno.xsd`.
