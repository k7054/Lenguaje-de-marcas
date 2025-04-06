# Ejercicio 9

## Descripción
Este ejercicio define una lista de mensajes utilizando XML. Cada mensaje incluye información sobre el remitente, destinatario, hora y texto.

## Estructura del DTD
- **mensajes**: Elemento raíz que contiene múltiples elementos `mensaje`.
- **mensaje**: Representa un mensaje con los siguientes subelementos:
  - **de**: Remitente del mensaje.
  - **para**: Destinatario del mensaje.
  - **hora**: Fecha y hora del mensaje.
  - **texto**: Contenido del mensaje, que puede incluir texto y elementos `strong`.

## Ejemplo de XML
```xml
<mensajes>
    <mensaje>
        <de>Pepe (pepe@example.com)</de>
        <para>Juan (juan@example.com)</para>
        <hora>28/02/2011 17:48:23,61</hora>
        <texto>Hola, Juan, ¿qué haces?</texto>
    </mensaje>
</mensajes>
```
