# Ejercicio 2

## Descripción
Este archivo XML valida una lista de letras utilizando una DTD interna. Cada letra está contenida dentro de un elemento `<letra>` y todas las letras están agrupadas dentro del elemento raíz `<letras>`.

## Estructura
- **Elemento raíz**: `<letras>`  
  Contiene una o más elementos `<letra>`.
- **Elemento `<letra>`**:  
  Contiene datos de texto (#PCDATA) que representan una letra.

## Ejemplo
```xml
<letras>
  <letra>m</letra>
  <letra>uve doble</letra>
</letras>
```
