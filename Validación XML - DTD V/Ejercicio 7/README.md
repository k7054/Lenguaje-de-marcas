# Ejercicio 7

## Descripción
Este ejercicio define una lista de colores utilizando XML. Cada color incluye un nombre y un código en formato RGB o CMYK.

## Estructura del DTD
- **colores**: Elemento raíz que contiene múltiples elementos `color`.
- **color**: Representa un color con los siguientes subelementos:
  - **nombreSvg**: Nombre del color en formato SVG.
  - **codigo**: Código del color, que puede ser en formato `rgb` o `cmyk`.

## Ejemplo de XML
```xml
<colores>
    <color>
        <nombreSvg>Purple</nombreSvg>
        <codigo>
            <rgb>#800080</rgb>
        </codigo>
    </color>
</colores>
```
