# Ejercicio 7

## Descripción
Este archivo XML representa una lista de músicos, donde cada músico tiene un nombre o apodo y una fecha de nacimiento. La validación se realiza mediante una DTD interna.

## Estructura
- **Elemento raíz**: `<musicos>`  
  Contiene cero o más elementos `<musico>`.
- **Elemento `<musico>`**:  
  Contiene un `<nombre>` o `<apodo>` y un `<fechaNacimiento>`.
- **Elementos `<nombre>`, `<apodo>`, `<fechaNacimiento>`**:  
  Contienen datos de texto (#PCDATA).

## Ejemplo
```xml
<musicos>
  <musico>
    <nombre>Antonio Vivaldi</nombre>
    <apodo>El cura pelirrojillo</apodo>
    <fechaNacimiento>4 de marzo de 1678</fechaNacimiento>
  </musico>
</musicos>
```
