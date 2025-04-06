# Ejercicio 1

## Descripción
Este archivo XML valida una lista de números utilizando una DTD interna. Cada número está contenido dentro de un elemento `<numero>` y todos los números están agrupados dentro del elemento raíz `<numeros>`.

## Estructura
- **Elemento raíz**: `<numeros>`  
  Contiene uno o más elementos `<numero>`.
- **Elemento `<numero>`**:  
  Contiene datos de texto (#PCDATA) que representan un número.

## Ejemplo
```xml
<numeros>
  <numero>25</numero>
</numeros>
```
