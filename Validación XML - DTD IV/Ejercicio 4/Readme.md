# Ejercicio 4

## Descripción
Este archivo XML representa una lista de flores. La validación se realiza mediante una DTD interna.

## Estructura
- **Elemento raíz**: `<flores>`  
  Contiene uno o más elementos `<flor>`.
- **Elemento `<flor>`**:  
  Contiene datos de texto (#PCDATA) que representan el nombre de una flor.

## Ejemplo
```xml
<flores>
  <flor>Rosa</flor>
</flores>
```
