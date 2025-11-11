# 🏗️ ARCHITECTURE.md  
## Sistema de Inventario y Ventas

---

## 1️⃣. Propósito del sistema

El sistema de Inventario tiene como objetivo ofrecer una solución ligera para la gestión básica de productos y existencias.

**Objetivos principales:**
- Registrar productos.
- Actualizar automáticamente el inventario.
- Facilitar mantenimiento y futuras ampliaciones del sistema.

---

## 2️⃣. Contexto general

El sistema está compuesto por tres capas principales:

| Capa | Tecnología | Responsabilidad |
|------|-------------|-----------------|
| **Frontend** | Next.js + React + TypeScript | Interfaz gráfica del usuario (UI) |
| **Backend** | ASP.NET Core (.NET 8) | Lógica de negocio y servicios REST |
| **Base de Datos** | PostgreSQL | Almacenamiento persistente de datos |

**Comunicación:**  
El frontend se conecta con la API REST del backend a través de HTTP, intercambiando datos en formato JSON.

**Usuarios principales:**
- **Administrador:** gestiona productos y reportes.
- **Vendedor:** registra ventas diarias.

---

## 3️⃣. Mapa de módulos

### 🧱 Backend (.NET)
#