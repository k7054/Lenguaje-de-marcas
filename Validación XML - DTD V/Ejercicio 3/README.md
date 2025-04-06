# Ejercicio 3

## Descripción
Este ejercicio define una lista de aeropuertos utilizando XML. Cada aeropuerto puede incluir información sobre si está cerrado.

## Estructura del DTD
- **aeropuertos**: Elemento raíz que contiene múltiples elementos `aeropuerto`.
- **aeropuerto**: Representa un aeropuerto con los siguientes subelementos:
  - **nombre**: Nombre del aeropuerto.
  - **cerrado** (opcional): Año en que el aeropuerto fue cerrado.

## Ejemplo de XML
```xml
<aeropuertos>
    <aeropuerto>
        <nombre>Berlin Schönefeld (SFX)</nombre>
    </aeropuerto>
    <aeropuerto>
        <nombre>Berlin Tempelhof (THF)</nombre>
        <cerrado>2008</cerrado>
    </aeropuerto>
</aeropuertos>
```
