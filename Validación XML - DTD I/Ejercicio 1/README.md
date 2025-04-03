# Ejercicio 1 - Biblioteca XML

## Descripción
Este archivo XML representa una biblioteca con información sobre libros, incluyendo su título, editorial, autor y número de páginas. Está validado mediante un DTD interno.

## Estructura
- `<biblioteca>`: Elemento raíz que contiene una lista de libros.
  - `<libro>`: Representa un libro en la biblioteca.
    - `<titulo>`: Título del libro.
    - `<editorial>`: Editorial del libro.
    - `<autor>`: Información del autor del libro.
      - `<nombre>`: Nombre del autor.
      - `<apellidos>`: Apellidos del autor.
    - `<paginas>`: Número de páginas del libro.

## Validación
- Este archivo utiliza un DTD interno definido dentro del propio documento XML.
