# Infrastructure / Config

Esta carpeta contiene la configuración de infraestructura para el microservicio **reservas**.

## Propósito

Aquí se deben ubicar los archivos de configuración necesarios para la operación del microservicio, incluyendo:

- Configuración de acceso a bases de datos (por ejemplo, strings de conexión, credenciales)
- Configuración de mensajería (por ejemplo, parámetros de conexión a Kafka, nombres de topics)
- Variables de entorno y archivos de configuración (por ejemplo, `.env`, `config.yaml`, `settings.json`)
- Configuración de logging, monitoreo, etc.

## Contenido

- `database.yaml` o `database.env`: Configuración de base de datos.
- `kafka.yaml` o `kafka.env`: Configuración de Kafka.
- `app.env`: Variables de entorno generales.