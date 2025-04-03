# Cuentos XML - Ejercicio 1

Este proyecto contiene dos documentos XML que representan cuentos estructurados según las especificaciones dadas. Además, se incluye un archivo DTD para validar la estructura de los cuentos.

## Archivos

### 1. `Cuento 1.xml`
- **Título**: El bosque encantado
- **Género**: Fantasía
- **Descripción**: Narra la historia de Alicia, una niña curiosa que se pierde en un bosque mágico y enfrenta pruebas mágicas para encontrar la salida.
- **Personajes**:
  - **Alicia**: Protagonista, una niña curiosa con cabello rubio y ojos azules.
  - **Bruja del Bosque**: Antagonista, una hechicera que protege los secretos del bosque.
- **Etiquetas**: Aventura, Magia
- **Precio**: 12.99 EUR

### 2. `Cuento 2.xml`
- **Título**: El secreto del faro
- **Género**: Misterio
- **Descripción**: Relata la investigación de Lucas, un joven periodista, sobre una leyenda oculta en el faro de la ciudad.
- **Personajes**:
  - **Lucas**: Protagonista, un joven periodista alto con cabello oscuro y gafas.
  - **Capitán Rojas**: Secundario, un anciano marinero con muchas historias sobre el faro.
- **Etiquetas**: Investigación, Suspenso
- **Precio**: 15.50 EUR

## Validación

Ambos documentos XML están validados mediante el archivo `Cuento.dtd`, que define la estructura y las reglas para los cuentos.

## Estructura General

Cada cuento tiene:
- Atributos obligatorios: `cod`, `titulo`.
- Atributo opcional: `genero` (valores: infantil, fantasía, terror).
- Elementos:
  - `personajes`: Contiene uno o más personajes.
  - `trama`: Describe la trama del cuento.
  - `etiqueta`: Elementos vacíos con un atributo `nombre` para clasificar el cuento.
  - `precio`: Opcional, con un atributo `moneda` (por defecto "eur").
