# Ejercicio 3

## Descripción
Este archivo XML contiene una lista de cuadros, cada uno identificado por un título único y un autor.

## Estructura
- **Elemento raíz**: `<cuadros>`  
  Contiene una lista de elementos `<cuadro>`.

- **Elemento `<cuadro>`**:  
  Representa un cuadro.  
  - Atributos:
    - `titulo` (ID, requerido): Título único del cuadro.
    - `autor` (CDATA, requerido): Nombre del autor del cuadro.

## Ejemplo
```xml
<cuadros>
  <cuadro titulo="AdanEva" autor="Alberto Durero" />
</cuadros>
```
