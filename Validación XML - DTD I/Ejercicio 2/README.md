# Ejercicio 2 - Liga XML

## Descripción
Este archivo XML representa una liga de baloncesto con información sobre jugadores, sus equipos y presidentes. Está validado mediante un DTD externo llamado `liga.dtd`.

## Estructura
- `<liga>`: Elemento raíz que contiene una lista de jugadores.
  - `<jugador>`: Representa a un jugador de la liga.
    - `<nombre>`: Nombre del jugador.
    - `<apellidos>`: Apellidos del jugador.
    - `<equipo>`: Información del equipo al que pertenece el jugador.
      - `<ciudad>`: Ciudad del equipo.
      - `<presidente>`: Información del presidente del equipo.
        - `<nombrePresidente>`: Nombre del presidente.
        - `<apellidosPresidente>`: Apellidos del presidente.
    - `<edad>`: Edad del jugador.

## Dependencias
- `liga.dtd`: Archivo DTD externo que define la estructura del documento.
