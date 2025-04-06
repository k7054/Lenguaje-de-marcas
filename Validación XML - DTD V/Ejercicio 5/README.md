# Ejercicio 5

## Descripción
Este ejercicio define una lista de reyes y reinas españoles utilizando XML. Cada rey o reina incluye información sobre sus padres.

## Estructura del DTD
- **reyesEspañoles**: Elemento raíz que contiene múltiples elementos `rey` y un elemento `reina`.
- **rey** y **reina**: Representan un monarca con los siguientes subelementos:
  - **nombre**: Nombre del monarca.
  - **padre**: Nombre del padre.
  - **madre**: Nombre de la madre.

## Ejemplo de XML
```xml
<reyesEspañoles>
    <rey>
        <nombre>Felipe III</nombre>
        <padre>Felipe II</padre>
        <madre>Ana de Austria</madre>
    </rey>
    <reina>
        <nombre>Juana la Loca</nombre>
        <padre>Fernando el Católico</padre>
        <madre>Isabel la Católica</madre>
    </reina>
</reyesEspañoles>
```
