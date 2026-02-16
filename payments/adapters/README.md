# Adapters

Esta carpeta contiene los adaptadores de la arquitectura hexagonal para el microservicio **payments**.

## Propósito

Los adaptadores son responsables de conectar el núcleo de la aplicación (dominio y casos de uso) con el mundo exterior. Aquí se implementan las interfaces para:

- Persistencia de datos (por ejemplo, repositorios de bases de datos)
- Mensajería (por ejemplo, integración con Kafka)
- APIs externas o servicios de terceros
- Adaptadores de entrada/salida (por ejemplo, controladores HTTP, consumidores de eventos)

Cada adaptador traduce las llamadas y datos entre el dominio y la tecnología específica utilizada.

## Contenido

- `db/`: Adaptadores para acceso a bases de datos.
- `kafka/`: Adaptadores para publicar/consumir mensajes en Kafka.
- `rest/`: Adaptadores para exponer/controlar APIs REST.