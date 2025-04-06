# Ejercicio 9

## Descripción
Este archivo XML representa un sistema solar con diferentes tipos de cuerpos celestes, como planetas, satélites y asteroides. La validación se realiza mediante una DTD interna.

## Estructura
- **Elemento raíz**: `<sistemaSolar>`  
  Contiene cero o más elementos `<cuerpo>`.
- **Elemento `<cuerpo>`**:  
  Puede contener un `<planeta>`, un `<satelite>` o un `<asteroide>`.
- **Elementos `<planeta>`, `<satelite>`, `<asteroide>`**:  
  Contienen datos de texto (#PCDATA) que representan el nombre del cuerpo celeste.

## Ejemplo
```xml
<sistemaSolar>
  <cuerpo>
    <planeta>Tierra</planeta>
    <satelite>Luna</satelite>
  </cuerpo>
  <cuerpo>
    <asteroide>Ceres</asteroide>
  </cuerpo>
</sistemaSolar>
```
