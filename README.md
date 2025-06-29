# 🧠 SmartInventory

**SmartInventory** es un sistema de gestión de inventario y facturación, desarrollado con una arquitectura limpia, API RESTful en .NET 8, PostgreSQL y un frontend moderno en Next.js 14.

---

## 🚀 Tecnologías utilizadas

### Backend (.NET 8)
- ASP.NET Core Web API
- Clean Architecture
- Dapper
- PostgreSQL

### Frontend
- Next.js 14 (App Router)
- TypeScript
- TailwindCSS
- API REST Integration

---

## 📁 Estructura del proyecto
SmartInventory/
├── src/ApplicationCore/ # Lógica de dominio (entidades, interfaces)
├── src/Infrastructure/ # Acceso a datos con Dapper
├── src/WebAPI/ # API REST
├── src/Shared/ # Objetos comunes (Result, ValueObject)
├── frontend/ # Interfaz gráfica en Next.js
└── README.md


---

## ⚙️ Requisitos

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download)
- [PostgreSQL](https://www.postgresql.org/download/)
- [Node.js (18+)](https://nodejs.org/)
- (opcional) [PNPM](https://pnpm.io/) o npm

---

## 🐘 Configuración de la base de datos

1. Crear una base de datos PostgreSQL llamada `smartinventory`.

2. Ejecutar el script SQL de inicialización:
   ```bash
   psql -U tu_usuario -d smartinventory -f init_database.sql

Interfaz disponible en: http://localhost:3000

🔐 Endpoints de autenticación
POST /api/auth/register

POST /api/auth/login

Pronto se agregará autenticación con JWT protegida.

📦 Funcionalidades en desarrollo
 Autenticación básica con JWT

 Estructura de base de datos inicial

 CRUD de clientes

 CRUD de productos

 Gestión de facturación (invoices)

 Interfaz gráfica con Next.js

 Tests unitarios con xUnit

🧑‍💻 Autor
Luis Hernández
Desarrollador Full Stack
📍 Uruguay

📜 Licencia
Este proyecto es de código abierto y está licenciado bajo los términos del MIT License.
