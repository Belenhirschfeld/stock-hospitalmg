# SisGest - Sistema de Gestión de Inventario Hospitalario

**SisGest** es una solución completa para automatizar el control de inventario, stock y auditoría en hospitales. Diseñado específicamente para resolver los desafíos operacionales de instituciones de salud.

## 🚀 Características Principales

- **Control en Tiempo Real**: Dashboard automático con stock actualizado al instante
- **Auditoría Completa**: Registro de cada movimiento (quién, qué, cuándo, por qué)
- **Alertas Automáticas**: Notificaciones de vencimientos próximos y stock bajo
- **Reportes Avanzados**: Análisis de rotación FEFO, consumo por unidad
- **Acceso Multi-dispositivo**: Funciona desde computadoras, tablets y celulares
- **Historial Inmutable**: Trazabilidad completa para cumplimiento regulatorio

## 📁 Estructura del Proyecto

```
sisgest/
├── public/
│   ├── index.html       # Landing page informativa
│   └── dashboard.html   # Demo interactiva del sistema
└── assets/              # Recursos (imágenes, estilos)
```

## 🎯 Uso

### Landing Page (index.html)
Abre `public/index.html` en tu navegador para ver:
- Descripción de problemas que resuelve
- Características principales
- Comparativa manual vs. automático
- Plan de implementación
- Call-to-action hacia la demo

### Dashboard Demo (dashboard.html)
Abre `public/dashboard.html` en tu navegador para:
- **Credenciales de demo**: Usuario: `demo` / Contraseña: `demo123`
- Explorar el sistema de control de inventario
- Ver tabla de movimientos con timestamps
- Agregar y eliminar medicamentos
- Registrar salidas con auditoría completa
- Consultar historial completo de transacciones

## 💻 Funcionalidades del Dashboard

### Panel Principal
- Métricas de stock total, vencimientos próximos, items bajo mínimo
- Últimos movimientos registrados
- Medicamentos próximos a vencer

### Tabla de Inventario
- Lista completa de medicamentos con stock actual
- Indicadores de estado (verde: OK, naranja: próximo a vencer, rojo: stock bajo)
- Opción para eliminar items

### Registro de Movimientos
- **Agregar Medicamento**: Ingresa nuevo item con cantidad y fecha de vencimiento
- **Registrar Salida**: Usa medicamento con registro de usuario, fecha/hora y detalles

### Historial Completo
- Auditoría de todas las operaciones
- Tipos: Ingreso, Salida, Login, Logout, Eliminación
- Información: Usuario, Fecha, Hora, Cantidad, Detalles

## 🔐 Seguridad y Auditoría

Todos los movimientos quedan registrados con:
- ✅ Usuario responsable
- ✅ Timestamp preciso
- ✅ Tipo de operación
- ✅ Detalles del procedimiento
- ✅ Cantidad afectada

Ideal para:
- Cumplimiento regulatorio
- Auditorías internas
- Investigación de discrepancias
- Reportes de conformidad

## 🛠️ Opciones de Implementación

### Opción 1: Google Sheets Automatizado
- **Costo**: Gratuito
- **Suscripción**: No
- **Ventajas**: Acceso ilimitado, fácil mantenimiento, integración con Google Workspace

### Opción 2: Plataforma Web Dedicada (Recomendada)
- **Costo**: $20-50 USD/mes
- **Suscripción**: Mensual
- **Ventajas**: Interfaz profesional, base de datos real, backups automáticos

### Opción 3: Software Especializado (ERPNext, Odoo)
- **Costo**: $50-200+ USD/mes
- **Suscripción**: Anual o mensual
- **Ventajas**: Sistema integral completo, soporte técnico incluido

## 📋 Plan de Implementación (6-8 semanas)

| Semana | Fase | Descripción |
|--------|------|-------------|
| 1-2 | Relevamiento | Análisis de procesos específicos del hospital |
| 3-4 | Desarrollo | Desarrollo e integración de datos |
| 5-6 | Capacitación | Entrenamiento del equipo |
| 7-8 | Go-Live | Lanzamiento y soporte |

## 🎓 Guía Rápida

### Para Directivos
- Acceso a reportes de control de inventario
- Visibilidad del status general del stock
- Conformidad regulatoria demostrada

### Para Equipo Administrativo
- Reducción de 70-80% en tiempo de administración
- Cero errores de entrada manual
- Automatización de alertas

### Para Enfermería
- Acceso rápido a información de stock desde cualquier lugar
- Sin formularios complejos
- Interface intuitiva y simple

## 🔗 URLs de Acceso

- **Landing Page**: `sisgest/public/index.html`
- **Dashboard**: `sisgest/public/dashboard.html`
- **Demo**: Usuario `demo` / Contraseña `demo123`

## 📞 Contacto y Más Información

Para consultas, demostraciones personalizadas o implementación:
- Solicita una reunión a través de la landing page
- Contacta al equipo de implementación

## 📄 Licencia

Este proyecto está disponible bajo licencia proprietaria. 
Todos los derechos reservados © 2024 SisGest.

## 👥 Desarrollo

Desarrollado con:
- HTML5 & CSS3
- JavaScript vanilla
- Diseño responsive
- Tema oscuro automático

---

**SisGest** - Transformando la gestión hospitalaria, un sistema a la vez.
