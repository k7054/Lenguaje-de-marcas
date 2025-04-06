# Ejercicio 5

## Descripción
Este archivo XML contiene una lista de jugadores de fútbol, cada uno identificado por un nombre y un código único.

## Estructura
- **Elemento raíz**: `<futbol>`  
  Contiene una lista de elementos `<jugador>`.

- **Elemento `<jugador>`**:  
  Representa un jugador de fútbol.  
  - Atributos:
    - `nombre` (NMTOKENS, requerido): Nombre del jugador.
    - `codigo` (ID, requerido): Identificador único del jugador.

## Ejemplo
```xml
<futbol>
  <jugador nombre="Johan Cruyff" codigo="4" />
</futbol>
```
