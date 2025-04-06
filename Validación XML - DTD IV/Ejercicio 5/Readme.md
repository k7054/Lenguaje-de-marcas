# Ejercicio 5

## Descripción
Este archivo XML representa una lista de animales. La validación se realiza mediante una DTD interna.

## Estructura
- **Elemento raíz**: `<animales>`  
  Contiene cero o más elementos `<animal>`.
- **Elemento `<animal>`**:  
  Contiene datos de texto (#PCDATA) que representan el nombre de un animal.

## Ejemplo
```xml
<animales>
  <animal>Caniche</animal>
  <animal>Siamés</animal>
</animales>
```
