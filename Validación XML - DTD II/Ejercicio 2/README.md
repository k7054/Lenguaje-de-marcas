# Ejercicio 2

## Descripción
Este archivo XML representa información sobre equipos de la NBA. Contiene detalles como el nombre del equipo, su conferencia, títulos ganados, posición en la clasificación y su quinteto inicial.

## Estructura
- **EquiposNBA**: Elemento raíz que agrupa la información de los equipos.
  - **nombre**: Nombre del equipo.
  - **equipo**: Detalles del equipo, con el atributo:
    - `conferencia`: Conferencia a la que pertenece el equipo (por ejemplo, "oeste" o "este").
    - Sub-elementos:
      - **titulos**: Número de títulos ganados.
      - **posicion**: Posición en la clasificación.
      - **quinteto**: Lista de jugadores del quinteto inicial.

## Dependencias
Este archivo utiliza un DTD externo llamado `EquiposNBA.dtd` para validar su estructura.
