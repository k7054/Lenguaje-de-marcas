# Ejercicio 6

## Descripción
Este ejercicio define una lista de países utilizando XML. Cada país puede pertenecer a la Unión Europea y/o a la OTAN.

## Estructura del DTD
- **paises**: Elemento raíz que contiene múltiples elementos `pais`.
- **pais**: Representa un país con los siguientes subelementos:
  - **nombre**: Nombre del país.
  - **unionEuropea** (opcional): Indica si el país pertenece a la Unión Europea.
  - **otan** (opcional): Indica si el país pertenece a la OTAN.

## Ejemplo de XML
```xml
<paises>
    <pais>
        <nombre>España</nombre>
        <unionEuropea/>
        <otan/>
    </pais>
    <pais>
        <nombre>Noruega</nombre>
        <otan/>
    </pais>
</paises>
```
