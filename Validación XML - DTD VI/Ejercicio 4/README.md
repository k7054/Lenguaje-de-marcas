# Ejercicio 4

## Descripción
Este archivo XML representa una lista de compras, donde cada elemento de la lista tiene un nombre y una cantidad.

## Estructura
- **Elemento raíz**: `<listaCompra>`  
  Contiene una lista de elementos `<item>`.

- **Elemento `<item>`**:  
  Representa un artículo de la lista de compras.  
  - Atributos:
    - `nombre` (CDATA, requerido): Nombre del artículo.
    - `cantidad` (CDATA, requerido): Cantidad del artículo.

## Ejemplo
```xml
<listaCompra>
  <item nombre="leche" cantidad="12 litros" />
</listaCompra>
```
