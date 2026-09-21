# Practicas

## Descripción del proyecto

Este proyecto es una API backend desarrollada con Spring Boot para gestionar la autenticación de usuarios en una aplicación de veterinaria. Su objetivo principal es proporcionar un sistema seguro de registro e inicio de sesión para clientes o personal administrativo, usando JWT (JSON Web Tokens) para proteger las rutas y controlar el acceso a la aplicación.

La aplicación está enfocada en facilitar la creación de cuentas, el acceso seguro con credenciales, y la validación de usuarios mediante autenticación basada en roles y en tokens. Esto permite que la plataforma pueda escalar fácilmente hacia funcionalidades más avanzadas de gestión clínica, citas, historial médico y atención veterinaria.

## ¿De qué trata?

El proyecto simula un servicio de autenticación para un sistema veterinario, donde los usuarios pueden:

- registrarse con su correo y contraseña
- iniciar sesión de forma segura
- recibir un token JWT al autenticarse
- acceder a endpoints protegidos solo si están autorizados
- manejar usuarios con distintos roles dentro del sistema

Es una base sólida para construir una app completa de gestión veterinaria, donde la seguridad y la administración de usuarios sean una parte fundamental.

## Tecnologías utilizadas

- Java 17
- Spring Boot 3
- Spring Security
- Spring Data JPA
- PostgreSQL
- JWT (jjwt)
- Maven
- Docker / Docker Compose

## Funcionalidades principales

- Registro de usuarios
- Login con autenticación segura
- Generación y validación de tokens JWT
- Configuración de seguridad con CORS y rutas públicas/protegidas
- Persistencia de usuarios con base de datos PostgreSQL
- Base lista para integración con un frontend o servicios adicionales

## Ejecución

1. Clonar el repositorio
2. Configurar la base de datos PostgreSQL
3. Ajustar las credenciales en `application.properties`
4. Ejecutar la aplicación con Maven:

```bash
./mvnw spring-boot:run
```

## Objetivo general

Este proyecto busca demostrar cómo construir un backend seguro y modular para una aplicación de veterinaria, con una estructura limpia, autenticación moderna y capacidad de expansión para futuras funcionalidades del sistema.
