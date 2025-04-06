# Ejercicio 3

## Descripción
Este archivo XML representa una lista de colores. La validación se realiza mediante una DTD interna.

## Estructura
- **Elemento raíz**: `<colores>`  
  Contiene cero o más elementos `<color>`.
- **Elemento `<color>`**:  
  Contiene datos de texto (#PCDATA) que representan el nombre de un color.

## Ejemplo
```xml
<colores>
  <color>azul marino</color>
  <color>negro</color>
</colores>
```
