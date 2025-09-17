# Salon Pro Dashboard

Un sistema web para gestión de salones de belleza: agenda, cobros, facturación, rendimiento, configuración, backups y multi‑pestaña. 

---

## 📌 Resumen
**Salon Pro Dashboard** es una aplicación en HTML/JS que funciona localmente en el navegador (sin servidor). Permite administrar:
- 📅 **Agenda** de citas con técnicos/estilistas.
- 💵 **Cobros y facturas** con exportación a PDF/CSV/JSON.
- 📊 **Analytics** (KPIs, gráficas, no‑shows).
- ⚙️ **Configuración** de branding, horarios, servicios, usuarios.
- 📂 **Backups** de datos y restauración.
- 🔄 **Sincronización multi‑pestaña** en tiempo real.

---

## ⚡ Requisitos
- Navegador moderno (Chrome, Edge, Firefox, Safari).
- **Soporte para LocalStorage** (persistencia de datos local).
- (Opcional) **Webhook/Google Sheets** para integración con hojas de cuadre.

---

## 🚀 Instalación
1. Descarga el archivo `index.html` (este proyecto).
2. Abre el archivo en tu navegador.
3. ¡Listo! Se ejecuta 100% local.

> ✅ No necesita servidor ni base de datos externa.

---

## 🎯 Uso
### Agenda
- Crea y edita citas.
- Define técnicos, servicios y horarios.
- Marca asistencia o no‑show.
- Exporta agenda a CSV/PDF.

### Cobros / Facturación
- Registra facturas con número consecutivo.
- Guarda datos: cliente, servicio, técnica, método de pago, monto.
- Exporta historial completo o agrupado (día/hora/técnica).
- Genera facturas en PDF individuales.

### Analytics
- KPIs: ingresos, citas, no‑shows.
- Gráficas de ingresos por técnica, servicio o método de pago.
- Export a PDF o CSV.

### Configuración
- Personaliza nombre, logo, colores y footer.
- Define horarios laborales por día.
- CRUD de servicios, técnicas y usuarios.
- Ajusta intervalo de agenda (ej. cada 30 min).

### Backups
- Exporta datos parciales (citas, cobros) o totales.
- Importa JSON para restaurar estado.

---

## 🔄 Sincronización multi‑pestaña
El sistema usa:
- `localStorage` events.
- `BroadcastChannel` (cuando está disponible).

De esta forma, **cualquier cambio en una pestaña se refleja en las demás** sin recargar.

---

## 📑 Exportaciones
- **Cobros** → PDF, CSV, JSON.
- **Agenda** → CSV, PDF.
- **Analytics** → CSV, PDF.
- **Logs** → CSV, PDF.

---

## 🛠️ Solución de problemas
| Problema | Posible causa | Solución |
|----------|---------------|----------|
| No se guardan cambios | Navegador bloquea LocalStorage | Revisar configuración de privacidad |
| PDF no genera | Pop‑ups bloqueados | Permitir ventanas emergentes |
| No sincroniza entre pestañas | `localStorage` deshabilitado | Habilitar almacenamiento local |

---

## ❓ FAQ
**¿Dónde se guardan los datos?**  
En `localStorage` del navegador. Opcionalmente puedes exportar backups.

**¿Puedo usarlo offline?**  
Sí, funciona 100% offline.

**¿Puedo conectar Google Sheets?**  
Sí, configurando el webhook en la sección de Configuración.

---

## ✅ Checklist de QA
- [ ] Crear y editar una cita.
- [ ] Generar factura y exportar a PDF.
- [ ] Exportar cobros agrupados a CSV.
- [ ] Probar login/logout y permisos.
- [ ] Restaurar un backup.
- [ ] Ver sincronización en 2 pestañas abiertas.

---

## 📄 Licencia
Uso interno para gestión de salones.
