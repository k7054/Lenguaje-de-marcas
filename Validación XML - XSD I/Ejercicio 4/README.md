# Ejercicio 4: Validación de tipos de vehículos

## Descripción
Este ejercicio utiliza un esquema XSD que define un tipo restringido para vehículos. Solo se permiten valores específicos como "barco", "bicicleta", "coche" y "tren". El objetivo es validar un archivo XML que utilice este esquema.

## Archivos incluidos
- `Ejercicio 4.xsd`: Esquema XSD que define los valores permitidos para el tipo de vehículo.
- `Ejercicio 4.xml`: Archivo XML que debe cumplir con las restricciones del esquema (debe ser creado o proporcionado).

## Instrucciones
1. Revisa el archivo `Ejercicio 4.xsd` para entender las restricciones definidas.
2. Crea o utiliza un archivo XML llamado `Ejercicio 4.xml` que contenga elementos `<vehiculo>` con valores permitidos.
3. Valida el archivo XML contra `Ejercicio 4.xsd` utilizando una herramienta o librería.
4. Si el archivo XML no pasa la validación, corrige los errores según las reglas definidas en el esquema.

## Herramientas recomendadas
- [XML Validator Online](https://www.xmlvalidation.com/)
- Librerías en lenguajes como Python (`xmlschema`), Java (`javax.xml.validation`), etc.

## Resultado esperado
El archivo XML debe validarse correctamente contra el esquema `Ejercicio 4.xsd` sin errores.
