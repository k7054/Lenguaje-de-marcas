# Ejercicio 5

## Descripción
Este ejercicio valida un archivo XML que representa un FAQ (Preguntas Frecuentes) utilizando un esquema XSD.

## Archivos
- **faq.xsd**: Define la estructura y las restricciones del archivo XML del FAQ.
- **FAQ.xml**: Contiene las preguntas y respuestas que se validan contra el esquema XSD.

## Estructura del XML
El archivo XML incluye:
- Elemento `info` con detalles como título, autor, email, versión y fecha.
- Elemento `part` con múltiples preguntas (`q`) y sus respuestas (`a`).

## Validación
Para validar el archivo XML, asegúrate de que el esquema XSD esté en la misma carpeta y que el atributo `xsi:noNamespaceSchemaLocation` apunte correctamente al archivo `faq.xsd`.
