# Entrypoints

Esta carpeta contiene los puntos de entrada del microservicio **billing** bajo la arquitectura hexagonal.

## Propósito

La capa de entrypoints define cómo los clientes externos interactúan con el microservicio. Aquí se implementan:

- Controladores HTTP/REST (por ejemplo, endpoints de la API)
- Consumidores de mensajes (por ejemplo, suscriptores de Kafka)

Esta capa recibe las solicitudes externas, las traduce y delega la lógica a la capa de aplicación.

## Contenido

- `api/`: Controladores y rutas HTTP/REST.
- `events/`: Consumidores de eventos/mensajes.