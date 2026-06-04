# LdG-BI-ReportingPortal
Portal empresarial desarrollado para centralizar información, reportes y métricas de negocio, proporcionando una base escalable para soluciones de Business Intelligence, análisis de datos y toma de decisiones basada en información confiable.

## Project Overview
LdG-BI-ReportingPortal es una plataforma en desarrollo orientada a la gestión y visualización de información empresarial. Su objetivo es servir como una base tecnológica para integrar reportes, dashboards, indicadores de desempeño y herramientas de análisis dentro de un entorno seguro y escalable.
La arquitectura ha sido diseñada para permitir la incorporación progresiva de nuevos módulos relacionados con Business Intelligence, administración de datos y monitoreo de indicadores clave del negocio.
Actualmente, el proyecto cuenta con un módulo completo de autenticación y seguridad que establece los fundamentos para el crecimiento de la plataforma.

## Authentication & Security Module
El módulo de seguridad implementa una arquitectura robusta para la gestión de usuarios y control de acceso:

### Key Features
* Authentication basada en Claims y Cookies.
* Gestión de sesiones con control de tiempo de expiración.
* CRUD completo de usuarios para administradores.
* Búsqueda, filtrado y paginación para una administración eficiente.
* Almacenamiento seguro de contraseñas mediante BCrypt Hashing.
* Sistema de Roles y Permissions para control granular de acceso.
* Arquitectura preparada para futuras extensiones de seguridad y gobernanza.

### Security Approach
La plataforma aplica principios de seguridad orientados a aplicaciones empresariales:

* Protección de credenciales mediante hashing seguro.
* Separación de responsabilidades mediante roles.
* Restricción de acceso basada en permisos.
* Diseño escalable para futuros mecanismos de auditoría y monitoreo.

## Current Status
### Implemented
* User Authentication
* Session Management
* User Administration
* Role-Based Access Control (RBAC)
* Secure Password Storage
* Search and Pagination Features

### Planned Features
* Business Dashboards
* KPI Monitoring
* Report Management
* Data Visualization Components
* Audit and Activity Tracking
* Advanced BI Modules

### Technology Stack
* ASP.NET Core
* C#
* Entity Framework Core
* Claims-Based Authentication
* Cookie Authentication
* BCrypt Password Hashing
* SQL Database

## Project Vision
LdG-BI-ReportingPortal busca evolucionar hacia una plataforma integral de Business Intelligence que permita a organizaciones centralizar información, monitorear indicadores y facilitar procesos de análisis y toma de decisiones mediante herramientas modernas de gestión de datos y reporting.
