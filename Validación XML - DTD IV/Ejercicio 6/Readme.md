# Ejercicio 6

## Descripción
Este archivo XML representa una lista de escritores, donde cada escritor tiene un nombre y una fecha de nacimiento. La validación se realiza mediante una DTD interna.

## Estructura
- **Elemento raíz**: `<escritores>`  
  Contiene cero o más elementos `<escritor>`.
- **Elemento `<escritor>`**:  
  Contiene un `<nombre>` y un `<nacimiento>`.
- **Elementos `<nombre>`, `<nacimiento>`**:  
  Contienen datos de texto (#PCDATA).

## Ejemplo
```xml
<escritores>
  <escritor>
    <nombre>Mario Vargas Llosa</nombre>
    <nacimiento>28 de marzo de 1936</nacimiento>
  </escritor>
</escritores>
```
