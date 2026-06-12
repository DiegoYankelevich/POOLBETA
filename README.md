SALÓN DE POOL — SISTEMA DE GESTIÓN · VERSIÓN BETA 5 (11/06/2026 · v0.14)
==========================================================================

QUÉ ES
Demostración navegable del sistema de gestión: mesas de pool con
cronómetro y cobro por minuto, mesas de salón, cuentas de mostrador,
comandas estilo KDS, pre-cierre con cajero, venta de productos con
stock, gastos, reportes con balance y configuración.

CÓMO USARLA
1. Copiar el archivo SalonPool-BETA.html al pendrive (es un solo archivo,
   no necesita nada más: ni internet, ni instalación).
2. En cualquier PC: doble clic → se abre en el navegador
   (Chrome o Edge recomendados).

PARA LA DEMO
- Selector Mozo/Caja/Admin (arriba): muestra qué ve cada rol.
  · Mozo: Salón, Mi turno e Historial. Abre mesas (personas obligatorias),
    comanda con comentario y envía el pre-cierre a caja. No cobra.
  · Caja: suma Cajero (cola de pre-cierres + cuentas abiertas),
    Comandas (KDS con edición auditada), Productos y Gastos.
  · Admin: acceso total (Dashboard, Reportes, Config).
- Botón 中: toda la interfaz en chino. Botón 🌗: modo claro/oscuro.
- Mesa verde → se abre indicando personas (nombre opcional).
- Mesa roja → cuenta: productos, "Comandar" con comentario, estados
  por ítem (sin comandar / en preparación / entregado).
- "Enviar a caja" → la mesa queda azul 💳 PAGANDO, el cronómetro se
  congela y el cajero la cobra desde la pestaña Cajero (Pool 9 ya
  viene de ejemplo esperando cobro).
- Comandas → "✏️ Editar" (rol Caja/Admin) reemplaza productos con
  motivo; todo queda en el Historial con filtros.

IMPORTANTE
- Es un BOCETO: los datos son de ejemplo y viven en memoria.
  Al recargar la página (F5) todo vuelve al estado inicial
  — útil para reiniciar la demo.
- Las pantallas de Dashboard y Reportes muestran números
  de ejemplo fijos para ilustrar el diseño.

Versión de trabajo y documentación: carpeta del proyecto
"Gestion de Mesas" (OneDrive de Diego).
