# Application

Esta carpeta contiene la lógica de aplicación (casos de uso) del microservicio **payments** bajo la arquitectura hexagonal.

## Propósito

La capa de aplicación orquesta los casos de uso del dominio, coordinando la interacción entre los adaptadores y el núcleo de negocio. Aquí se definen los servicios de aplicación, comandos, consultas y lógica de orquestación.

- Implementa los casos de uso del sistema.
- No contiene lógica de infraestructura ni detalles tecnológicos.
- Invoca los puertos definidos en el dominio y utiliza los adaptadores concretos.

## Ejemplo de contenido

- Servicios de aplicación (Application Services)
- Comandos y consultas (Command/Query Handlers)