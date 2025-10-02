# 📦 Proyecto API - Clean Architecture con .NET 9 + PostgreSQL

Este proyecto implementa una **API REST** utilizando **.NET 9**, siguiendo el enfoque de **Clean Architecture**.  
Se integra con **PostgreSQL** como base de datos relacional y hace uso de **Entity Framework Core** como ORM.  
También incorpora **AutoMapper** para el mapeo entre entidades y DTOs, además de **FluentValidation** para validaciones robustas.  

Actualmente, la API expone endpoints básicos para las entidades (CRUD completo).

---

## 🚀 Tecnologías principales

- **.NET 9.0**  
- **Entity Framework Core 9.0.9** (con `dotnet ef`)  
- **PostgreSQL 16** (puede correr en Docker o localmente)  
- **AutoMapper 12.0.1**  
- **FluentValidation** (para validaciones de modelos y DTOs)  
- **Docker Compose** (orquestación de servicios)  
- **Swagger / OpenAPI** (documentación automática de endpoints)

---

## 📂 Estructura del Proyecto (Clean Architecture)

- **Api/** → Capa de entrada (controladores, configuración de servicios, middlewares).  
- **Application/** → Contiene casos de uso, lógica de negocio, DTOs y validaciones.  
- **Infrastructure/** → Persistencia con EF Core, contexto de base de datos, repositorios.  

---
