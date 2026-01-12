# informcaion de git
## API REST para procesamiento de transacciones de pago con validaciones de negocio y simulación de banco emisor.
    - API completa
    - Colección completa en postman donde están paso a paso como ejecutar los endpoint (directorio: COLECCION_POSTMAN)
    - Guía completa de usuario

## Requisitos

- Java 17+
- Maven 3.9+
- MySQL 5.5+ (o Docker)

## Ejecución

### Opción 1: Local (con MySQL propio)

1. Crear base de datos:
    sql
    CREATE DATABASE pagosdb;

2. Configurar application.properties con tus credenciales de MySQL

3. Ejecutar aplicación:
    ash
    mvn spring-boot:run


    La API estará disponible en: http://localhost:8001

### Opción 2: Con Docker

    bash
    docker-compose up --build


    La API estará en http://localhost:8001 y MySQL en puerto 3307