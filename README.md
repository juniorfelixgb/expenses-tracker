# Expenses Tracker 💰

**Expenses Tracker** es una aplicación web diseñada para gestionar y realizar el seguimiento de tus gastos personales o financieros de manera eficiente. Construida utilizando el stack de tecnologías **.NET**, esta aplicación ofrece una solución moderna y escalable para el control financiero personal.

---

## 🚀 Características principales

- **Gestión de transacciones:** Registra ingresos y gastos con categorías personalizadas.
- **Panel de control intuitivo:** Visualiza gráficos interactivos y resúmenes financieros.
- **Filtros avanzados:** Consulta tus datos por fecha, categoría o tipo de transacción.
- **Seguridad robusta:** Manejo seguro de datos con autenticación y autorización basada en **Identity**.
- **Multiusuario:** Admite múltiples perfiles de usuario para gestionar cuentas separadas.
- **Escalabilidad:** Arquitectura preparada para ser extendida e implementada en la nube.

---

## 🛠️ Tecnologías utilizadas

- **Backend:**
  - ASP.NET Core
  - Entity Framework Core
  - API RESTful
  - SQL Server para el almacenamiento de datos

- **Frontend:**
  - Razor Pages / Blazor (o especificar si se usa un framework como Angular o React integrado con .NET)

- **Otros:**
  - Autenticación con ASP.NET Identity
  - Logging y monitoreo con Serilog
  - Inyección de dependencias (DI) nativa de .NET Core

---

## 🎯 Funcionalidades futuras (Roadmap)

- Notificaciones automáticas para alertas de presupuesto.
- Integración con APIs de bancos para sincronización de cuentas.
- Aplicación móvil (Xamarin / MAUI) para seguimiento sobre la marcha.
- Exportación de reportes financieros en PDF o Excel.

---

## ⚙️ Cómo empezar

1. Clona este repositorio:  
   ```bash
   git clone https://github.com/tu_usuario/expenses-tracker.git

2. Configura la base de datos en appsetting.json

3. Aplica las migraciones de Entity Framework Core
    dotnet ef database update

4. Inicia el proyecto:
    dotnet run

