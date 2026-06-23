# Grupo Cordillera - Microservicio Datos Organizacionales

Microservicio de datos organizacionales de la Plataforma de Monitoreo Inteligente. Spring Boot + JPA + PostgreSQL.

Gestiona empleados y departamentos.

## Maven

```bash
./mvnw clean test
./mvnw spring-boot:run
```

## Docker

```bash
docker build -t cordillera-ms-datos-org .
docker run -p 8082:8082 cordillera-ms-datos-org
```

## Puertos

| Entorno | Puerto |
|---|---|
| Desarrollo/Producción | 8082 |

