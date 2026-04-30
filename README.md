# Curichazo - Sistema de Control de Ventas e Inventario

Aplicación web para la gestión de ventas, stock y fiados de una curichería artesanal, desarrollada con Spring Boot, Java 25 y MySQL.

## Tabla de Contenidos

* Descripción del Negocio
* Problema y Solución
* Preanálisis
* Análisis de Requisitos
* Stack Tecnológico
* Arquitectura del Proyecto
* Instalación

## 1. Descripción del Negocio

Curichazo es un pequeño negocio familiar ubicado en Pucallpa, Ucayali, dedicado a la elaboración y venta de curichis artesanales frescos a base de frutas locales como aguaje, coco, chapo, maní y fresa. 

La dueña maneja todo el negocio de forma individual, atendiendo directamente a sus clientes. Actualmente, el registro de ventas, control de stock y fiados se realiza de manera manual en cuadernos.

## 2. Problema y Solución

**Problema Identificado**  
La dueña del negocio registra las ventas y fiados de forma manual, lo que genera dificultades para conocer con exactitud la cantidad de productos vendidos, el stock disponible y los montos pendientes por cobrar. Esto provoca confusiones en el control del dinero, posibles pérdidas económicas y pérdida de tiempo en la administración diaria.

**Solución Propuesta**  
Desarrollar un sistema web que permita registrar ventas al contado y a crédito (fiados), controlar automáticamente el stock de productos y gestionar los clientes y sus deudas pendientes de manera digital y organizada.

## 3. Preanálisis

**Necesidades Identificadas**
- Registrar y gestionar clientes
- Administrar productos con control de stock
- Registrar ventas al contado y fiados
- Actualizar el stock automáticamente al realizar una venta
- Consultar historial de ventas y fiados pendientes
- Tener una interfaz sencilla e intuitiva para la dueña

**Estudio de viabilidad**
- Técnica: Uso de tecnologías modernas y accesibles (Java + Spring Boot + MySQL)
- Económica: Stack completamente gratuito
- Operacional: Sistema accesible desde cualquier navegador web

**Alcance del sistema**
Dentro del alcance: Gestión de clientes, productos, ventas y stock.  
Fuera del alcance: Módulo avanzado de reportes y aplicación móvil.

## 4. Análisis de Requisitos

**Requisitos Funcionales:**
- Registrar, listar, editar y eliminar clientes
- Registrar, listar, editar y eliminar productos con control de stock
- Realizar ventas al contado y fiados
- Actualizar stock automáticamente después de cada venta
- Visualizar el stock actual de productos

**Requisitos No Funcionales:**
- Interfaz intuitiva y fácil de usar
- Sistema responsive (funciona en computadora y celular)
- Buenas prácticas de programación
- Código organizado y mantenible

## Stack Tecnológico

| Capa          | Tecnología                          |
|---------------|-------------------------------------|
| Backend       | Java 25, Spring Boot, Spring Data JPA |
| Base de datos | MySQL / MariaDB                     |
| Frontend      | HTML5, CSS3, Bootstrap 5, JavaScript |
| IDE           | IntelliJ IDEA                       |
| Control de versiones | Git + GitHub                   |

## Arquitectura del Proyecto

El sistema sigue una arquitectura en capas con el patrón MVC:
- **Controller**: Maneja las peticiones HTTP
- **Service**: Contiene la lógica de negocio
- **Repository**: Acceso a la base de datos
- **Entity**: Representación de las tablas de la base de datos

Se utilizó Programación Orientada a Objetos (POO) y buenas prácticas de desarrollo.

## Instalación

### Requisitos previos
- Java 25
- IntelliJ IDEA
- MySQL o MariaDB
- Maven

### Pasos

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tuusuario/curichazo.git
