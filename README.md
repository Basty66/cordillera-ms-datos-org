# Grupo Cordillera - Microservicio Datos Organizacionales

Microservicio de datos organizacionales de la Plataforma de Monitoreo Inteligente. **Spring Boot + JPA + PostgreSQL**.

Gestiona empleados y departamentos.

## Tecnologías

- Spring Boot, Java 21, JPA/Hibernate
- PostgreSQL 14 (Neon.tech)
- Patrones: Repository, Factory Method
- JUnit 5 + Mockito + JaCoCo

## Cobertura de Pruebas

- **22 tests** — Cobertura: **99%** (instrucciones)
- La cobertura más alta del proyecto

## Endpoints

| Método | Ruta | Descripción |
|---|---|---|
| GET | /api/empleados | Listar empleados |
| POST | /api/empleados | Crear empleado |
| GET | /api/empleados/count | Contar empleados |
| GET | /api/departamentos | Listar departamentos |
| POST | /api/departamentos | Crear departamento |

## Ejecución

`ash
# Tests
./mvnw clean test

# Ejecutar
./mvnw spring-boot:run
`

Puerto: **8082**
