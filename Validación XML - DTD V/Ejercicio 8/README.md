# Ejercicio 8

## Descripción
Este ejercicio define una lista de apuntes contables utilizando XML. Cada apunte puede ser un ingreso o un gasto.

## Estructura del DTD
- **contabilidad**: Elemento raíz que contiene múltiples elementos `apunte`.
- **apunte**: Representa un apunte contable que puede ser:
  - **ingreso**: Incluye `fecha`, `cantidad` y `concepto`.
  - **gasto**: Incluye `fecha`, `cantidad` y `concepto`.

## Ejemplo de XML
```xml
<contabilidad>
    <apunte>
        <ingreso>
            <fecha>24 de febrero de 2011</fecha>
            <cantidad>1800,00 €</cantidad>
            <concepto>Salario</concepto>
        </ingreso>
    </apunte>
</contabilidad>
```
