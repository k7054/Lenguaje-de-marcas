# Ejercicio 2

## Descripción
Este ejercicio define una lista de efemérides históricas utilizando XML. Cada efeméride incluye una fecha y un hecho.

## Estructura del DTD
- **efemerides**: Elemento raíz que contiene múltiples elementos `efemeride`.
- **efemeride**: Representa un evento histórico con los siguientes subelementos:
  - **fecha**: Fecha del evento.
  - **hecho**: Descripción del evento.

## Ejemplo de XML
```xml
<efemerides>
    <efemeride>
        <fecha>20 de julio de 1969</fecha>
        <hecho>Llegada del hombre a la Luna</hecho>
    </efemeride>
    <efemeride>
        <fecha>12 de octubre de 1492</fecha>
        <hecho>Llegada de Colón a América</hecho>
    </efemeride>
</efemerides>
```
