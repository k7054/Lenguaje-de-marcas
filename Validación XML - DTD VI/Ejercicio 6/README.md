# Ejercicio 6

## Descripción
Este archivo XML representa una estructura de datos relacionada con el fútbol. Contiene información sobre jugadores y equipos, y cómo están relacionados entre sí.

## Estructura
- **Elemento raíz**: `<futbol>`  
  Contiene una lista de elementos `<jugador>` y `<equipo>`.

- **Elemento `<jugador>`**:  
  Representa un jugador de fútbol.  
  - Atributos:
    - `nombre` (NMTOKENS, requerido): Nombre del jugador.
    - `codigo` (ID, requerido): Identificador único del jugador.

- **Elemento `<equipo>`**:  
  Representa un equipo de fútbol.  
  - Atributos:
    - `nombre` (CDATA, requerido): Nombre del equipo.
    - `jugadores` (IDREFS, opcional): Referencias a los códigos de los jugadores que pertenecen al equipo.

## Ejemplo
```xml
<futbol>
  <jugador nombre="Diego Armando Maradona" codigo="dam" />
  <equipo nombre="Società Sportiva Calcio Napoli" jugadores="dam" />
</futbol>
```
