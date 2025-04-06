# Ejercicio 4

## Descripción
Este ejercicio define una lista de vuelos utilizando XML. Cada vuelo incluye un origen y un destino.

## Estructura del DTD
- **vuelos**: Elemento raíz que contiene múltiples elementos `vuelo`.
- **vuelo**: Representa un vuelo con los siguientes subelementos:
  - **origen**: Ciudad de origen del vuelo.
  - **destino**: Ciudad de destino del vuelo.

## Ejemplo de XML
```xml
<vuelos>
    <vuelo>
        <origen>Valencia (VLC)</origen>
        <destino>Londres Heathrow (LHR)</destino>
    </vuelo>
    <vuelo>
        <origen>Berlin Schönefeld (SFX)</origen>
        <destino>París Charles de Gaulle (CDG)</destino>
    </vuelo>
</vuelos>
```
