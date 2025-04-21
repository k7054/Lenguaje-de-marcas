# Ejercicio 2 - Fichas

## Descripción
Este ejercicio define un esquema XML (`fichas.xsd`) y un documento XML (`fichas.xml`) que representan una lista de fichas con atributos y elementos específicos.

## Contenido
- **`fichas.xsd`**: Define las restricciones para los elementos y atributos de las fichas:
  - `codigo`: Un valor de dos dígitos entre 00 y 19.
  - `numero`: Un atributo obligatorio con el mismo formato que `codigo`.
  - `letra`: Un atributo opcional que solo puede ser **X**, **Y** o **Z**.
- **`fichas.xml`**: Ejemplo de un documento XML que cumple con las restricciones del esquema.

## Uso
1. Valida el archivo `fichas.xml` utilizando el esquema `fichas.xsd`.
2. Asegúrate de que los elementos y atributos cumplan con las restricciones definidas.
