# Sistema de Control de Asistencia de Empleados

Aplicación web para el registro y gestión de asistencia del personal, desarrollada con Spring Boot, Java y MySQL.

## Tabla de Contenidos

- Descripción del Negocio
- Problema y Solución
- Preanálisis
- Análisis de Requisitos
- Stack Tecnológico
- Arquitectura del Proyecto
- Instalación

## 1. Descripción del Negocio

El sistema está diseñado para ayudar a las empresas a gestionar de forma digital la asistencia de sus empleados. Reemplaza los registros manuales en papel o planillas físicas, permitiendo un control más preciso y eficiente de las entradas y salidas del personal.

## 2. Problema y Solución

### Problema Identificado
Muchas empresas aún registran la asistencia de sus empleados de manera manual (en hojas o cuadernos), lo que genera:
- Registros incompletos o manipulados
- Dificultad para generar reportes históricos
- Pérdida de tiempo en el área de Recursos Humanos
- Imposibilidad de detectar patrones de ausentismo rápidamente
- Errores en el cálculo de horas trabajadas

### Solución Propuesta
Desarrollar un **Sistema Web de Control de Asistencia** que permita:
- Registrar la entrada y salida de empleados con fecha y hora automática
- Gestionar el catálogo de empleados
- Consultar el historial de asistencias
- Visualizar un dashboard con el estado de asistencia del día

## 3. Preanálisis

### Necesidades Identificadas
1. Registrar asistencia de entrada y salida con fecha y hora exacta
2. Gestionar empleados (CRUD)
3. Consultar historial de asistencias por empleado y rango de fechas
4. Visualizar el estado de asistencia del día actual
5. Autenticación básica de usuarios
6. Interfaz sencilla y fácil de usar

### Estudio de Viabilidad
- **Técnica**: Tecnologías modernas y accesibles (Java + Spring Boot + MySQL)
- **Económica**: Stack completamente gratuito
- **Operacional**: Sistema accesible desde cualquier navegador web

## 4. Análisis de Requisitos

### Requisitos Funcionales
- Registrar entrada y salida de empleados
- Gestionar empleados (crear, listar, editar, eliminar)
- Consultar historial de asistencias
- Visualizar dashboard con asistencia del día
- Diferenciar roles (Administrador y Empleado)

### Requisitos No Funcionales
- Interfaz intuitiva y responsive
- Buenas prácticas de programación
- Código organizado y mantenible
- Seguridad básica en el acceso

## Stack Tecnológico

| Capa          | Tecnología                          |
|---------------|-------------------------------------|
| Backend       | Java 25, Spring Boot, Spring Data JPA |
| Base de datos | MySQL / MariaDB                     |
| Frontend      | HTML5, CSS3, Bootstrap 5, JavaScript |
| IDE           | IntelliJ IDEA                       |
| Control de versiones | Git + GitHub                   |

## Arquitectura del Proyecto

El proyecto sigue una arquitectura en capas:
- **Controller**: Maneja las peticiones HTTP
- **Service**: Contiene la lógica de negocio
- **Repository**: Acceso a la base de datos
- **Entity**: Representación de las tablas

Se utilizó el patrón MVC y Programación Orientada a Objetos (POO).

## Instalación

### Requisitos previos
- Java 25
- IntelliJ IDEA
- MySQL o MariaDB
- Maven

### Pasos
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tuusuario/sistema-asistencia.git
