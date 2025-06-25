# PyS.report-service

[![PyS.report-service CI](https://github.com/PyS-services/PyS.report-service/actions/workflows/maven.yml/badge.svg?branch=main)](https://github.com/PyS-services/PyS.report-service/actions/workflows/maven.yml)

## Descripción

Servicio de generación de reportes para la plataforma PyS.

## Tecnologías

- **Java 21**
- **Spring Boot 3.5.3**
- **Spring Cloud 2025.0.0**
- **Spring Boot Actuator**
- **Spring Web**

## Requisitos

- Java 21 o superior
- Maven 3.6.3 o superior
- Spring Boot 3.5.3

## Instalación

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/PyS-services/PyS.report-service.git
   ```

2. Navegar al directorio del proyecto:
   ```bash
   cd PyS.report-service
   ```

3. Compilar el proyecto:
   ```bash
   mvn clean install
   ```

## Uso

Para iniciar el servicio:

```bash
mvn spring-boot:run
```

## Configuración

La configuración se maneja a través de `application.yml` y `bootstrap.yml`.

## Desarrollo

### Estructura del Proyecto

```
src/
├── main/
│   ├── java/com/pys/reportservice/
│   └── resources/
└── test/
    └── java/com/pys/reportservice/
```

### Pruebas

Para ejecutar las pruebas:

```bash
mvn test
```

## Despliegue

El despliegue se realiza a través de GitHub Actions. Ver el archivo `.github/workflows/maven.yml` para más detalles.

## Licencia

[Incluir información de licencia]

## Contribución

Las contribuciones son bienvenidas. Por favor, lee las pautas de contribución antes de enviar un pull request.
