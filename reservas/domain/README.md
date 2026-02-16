# Domain

Esta carpeta contiene el núcleo de dominio del microservicio **reservas** bajo la arquitectura hexagonal.

## Propósito

La capa de dominio encapsula la lógica de negocio, las reglas y los modelos fundamentales del sistema. Aquí se definen:

- Entidades y objetos de valor (Value Objects)
- Agregados y reglas de negocio
- Puertos (interfaces) que definen los puntos de entrada/salida del dominio (por ejemplo, repositorios, servicios de mensajería)
- Eventos de dominio

No debe haber dependencias hacia detalles tecnológicos ni hacia otras capas.

## Ejemplo de contenido

- `model/`: Entidades, agregados y objetos de valor.
- `ports/`: Interfaces para repositorios, servicios externos, colas de mensajes, etc.
- `events/`: Definición de eventos de dominio.