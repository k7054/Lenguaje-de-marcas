# Ejercicio 1

## Descripción
Este archivo XML representa una factura. Contiene información sobre el emisor, el cliente y los detalles de los artículos facturados.

## Estructura
- **factura**: Elemento raíz que incluye los atributos:
  - `numero`: Número de la factura.
  - `fecha`: Fecha de emisión de la factura.
  - Sub-elementos:
    - **datos-emisor**: Información del emisor de la factura.
      - **nombre**: Nombre del emisor.
      - **cif**: Código de identificación fiscal del emisor.
      - **telefono**: Teléfono del emisor.
    - **datos-cliente**: Información del cliente.
      - **nombre**: Nombre del cliente.
      - **cif**: Código de identificación fiscal del cliente.
      - **telefono**: Teléfono del cliente.
    - **detalle-factura**: Detalles de los artículos facturados, con el atributo:
      - `importe`: Importe total de la factura.
      - Sub-elementos:
        - **linea**: Detalle de un artículo, con los atributos:
          - `codigo-articulo`: Código del artículo.
          - `tipo`: Tipo de artículo (por ejemplo, "Libro" o "DVD").
          - Sub-elementos:
            - **descripcion**: Descripción del artículo.
            - **cantidad**: Cantidad comprada.
            - **pvp**: Precio por unidad.
            - **oferta**: Indica si el artículo está en oferta (opcional).

## Dependencias
Este archivo utiliza un DTD externo llamado `factura.dtd` para validar su estructura.
