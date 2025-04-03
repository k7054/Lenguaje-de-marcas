# Ejercicio 3

## Descripción
Este archivo XML representa un panel de vuelos en un aeropuerto. Contiene información sobre el aeropuerto, así como detalles de los vuelos, incluyendo su código, estado, origen, destino, y horarios de salida y llegada.

## Estructura
- **panel**: Elemento raíz que incluye el atributo `fecha` para indicar la fecha del panel.
  - **aeropuerto**: Nombre del aeropuerto.
  - **vuelo**: Información de un vuelo, con los atributos:
    - `codigo`: Código del vuelo.
    - `estado`: Estado del vuelo (por ejemplo, "R" para retrasado, "C" para cancelado).
    - Sub-elementos:
      - **diario**: Indica si el vuelo es diario (opcional).
      - **origen**: Ciudad de origen.
      - **destino**: Ciudad de destino.
      - **hora-salida**: Hora de salida.
      - **hora-llegada**: Hora de llegada.

## Dependencias
Este archivo utiliza un DTD externo llamado `panel.dtd` para validar su estructura.
