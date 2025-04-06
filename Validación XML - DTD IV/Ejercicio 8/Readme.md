# Ejercicio 8

## Descripción
Este archivo XML representa una agenda de contactos, donde cada contacto puede tener múltiples números de teléfono fijo y al menos un número de teléfono móvil. La validación se realiza mediante una DTD interna.

## Estructura
- **Elemento raíz**: `<agenda>`  
  Contiene cero o más elementos `<contacto>`.
- **Elemento `<contacto>`**:  
  Contiene un `<nombre>`, cero o más `<telefonoFijo>` y uno o más `<telefonoMovil>`.
- **Elementos `<nombre>`, `<telefonoFijo>`, `<telefonoMovil>`**:  
  Contienen datos de texto (#PCDATA).

## Ejemplo
```xml
<agenda>
  <contacto>
    <nombre>Ayuntamiento</nombre>
    <telefonoFijo>010</telefonoFijo>
    <telefonoMovil>Desconocido</telefonoMovil>
  </contacto>
</agenda>
```
