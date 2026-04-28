# 🎉 Full Party Labels

Sistema de etiquetas con código de barras para tiendas de artículos para fiestas.  
Aplicación de escritorio para Windows construida con **Electron + FastAPI + Supabase**.

---

## 📦 Descargar

Descarga el instalador más reciente en la sección [**Releases**](../../releases/latest).

---

## 🖥️ Stack tecnológico

| Capa | Tecnología |
|------|-----------|
| Frontend / Desktop | Electron.js + HTML5 + Tailwind CSS |
| Backend local | FastAPI (Python) compilado con PyInstaller |
| Base de datos | Supabase (PostgreSQL) |
| Impresora | Brother QL-800 — etiquetas 62mm |

---

## ✨ Funcionalidades

- 🏷️ **Múltiples formatos de código de barras** — EAN-13, EAN-8, UPC-A y Code128
- 🖨️ **Impresión de etiquetas PDF** 62×29mm optimizadas para Brother QL-800
- 👥 **Sistema de roles** — Modo Cajero y Modo Admin con PIN de seguridad
- 📊 **CRUD de productos** — Alta, edición y baja con SKU auto-generado
- 📥 **Importar/Exportar CSV y Excel** — Carga masiva de inventario
- 🔍 **Búsqueda en tiempo real** y paginación
- 🌐 **Multi-usuario** — Sincronización entre varias PCs via Supabase
- 📡 **Modo offline** — Guarda cambios localmente y sincroniza al reconectar
- 🔄 **Auto-actualizaciones** — Notificación automática de nuevas versiones

---

## 📸 Capturas de pantalla

### Pantalla principal
![Inicio](screenshots/01-inicio.png)

### Modo Cajero — controles restringidos
![Cajero](screenshots/02-cajero.png)

### Modo Admin — acceso completo
![Admin](screenshots/03-admin.png)

### PIN de seguridad
![PIN](screenshots/04-pin.png)

### Etiqueta generada
![Etiqueta](screenshots/05-etiqueta.png)

### Importar inventario CSV/Excel
![Importar](screenshots/06-importar.png)

---

## 🔄 Auto-actualizaciones

Esta aplicación incluye un sistema de actualizaciones automáticas basado en `electron-updater`.  
Cuando se publica una nueva versión aquí en GitHub Releases, los usuarios instalados reciben una notificación al abrir la app y pueden instalar con un clic.

---

## 📄 Licencia

Uso interno — Full Party, Uruapan, Michoacán 🎉
