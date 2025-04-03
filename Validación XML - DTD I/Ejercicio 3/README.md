# Ejercicio 3 - Agenda XML

## Descripción
Este archivo XML representa una agenda personal con información sobre una persona, incluyendo sus datos de contacto y lugar de nacimiento. Está validado mediante un DTD externo llamado `agenda.dtd`.

## Estructura
- `<agenda>`: Elemento raíz que contiene la información de la persona.
  - `<nombre>`: Nombre de la persona.
  - `<apellido>`: Primer apellido de la persona.
  - `<apellido>`: Segundo apellido de la persona.
  - `<telefono>`: Número de teléfono de la persona.
  - `<fecha_nacimiento>`: Fecha de nacimiento de la persona.
    - `<anio>`: Año de nacimiento.
    - `<mes>`: Mes de nacimiento.
    - `<dia>`: Día de nacimiento.
  - `<lugar_nacimiento>`: Lugar de nacimiento de la persona.
    - `<pais>`: País de nacimiento.
    - `<ciudad>`: Ciudad de nacimiento.
    - `<localidad>`: Localidad de nacimiento.

## Dependencias
- `agenda.dtd`: Archivo DTD externo que define la estructura del documento.
