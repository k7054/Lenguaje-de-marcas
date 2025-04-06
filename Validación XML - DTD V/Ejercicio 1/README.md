# Ejercicio 1

## Descripción
Este ejercicio define una lista de marcadores favoritos utilizando XML. Cada marcador contiene un nombre y una URI.

## Estructura del DTD
- **favoritos**: Elemento raíz que contiene múltiples elementos `marcador`.
- **marcador**: Representa un marcador con los siguientes subelementos:
  - **nombre**: Nombre del marcador.
  - **uri**: Dirección URI del marcador.

## Ejemplo de XML
```xml
<marcadores>
    <marcador>
        <nombre>W3C</nombre>
        <uri>http://www.w3.org/</uri>
    </marcador>
    <marcador>
        <nombre>Web Hypertext Application Technology Working Group (WHATWG)</nombre>
        <uri>http://www.whatwg.org/</uri>
    </marcador>
</marcadores>
```
