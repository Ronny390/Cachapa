# Chpa 🌽 - Sistema de Control y Gestión de Cachapas

Aplicación web local y ligera para el control integral de producción, costos, inventario y cuentas por cobrar para un negocio de mezcla de cachapas congeladas (potes de arroz chino de 654ml / 500g de masa).

## 🚀 Características Principales

1. **Calculadora Dinámica de Receta & Costos:**
   - Adaptada a la economía venezolana con conversión bimoneda (USD / Bs a tasa BCV configurable).
   - Ajuste inteligente según el **estado del maíz**:
     - 💧 **Muy Tierno (Lechoso):** Reduce agua añadida y compensa con espesante para evitar mezcla aguada.
     - 🌽 **Punto Ideal:** Fórmula estándar cremosa (rendimiento ~20-22 potes/saco).
     - 🌾 **Sazón / Seco:** El almidón seco absorbe líquido y expande la masa ("aumenta volumen"), rindiendo hasta 24-28 potes/saco.
   - Costeo al gramo: maíz, azúcar, leche en polvo, harina, sal y potes plásticos con tapa.

2. **Control de Lotes y Detección de Merma:**
   - Registro de molienda en gramos (ej. 8.921g por saco).
   - Cálculo del rendimiento real (potes por saco) para detectar cuándo un saco viene seco o con merma excesiva.

3. **Módulo de Ventas y Cobranzas (Fiados):**
   - Seguimiento de entregas, montos en $ y Bs.
   - Filtro rápido para ver deudores.
   - Botón directo para enviar recordatorio de cobro personalizado por WhatsApp con tasa actualizada.

4. **Inventario Crítico:**
   - Semáforo de existencias (sacos de jojoto, potes, leche, azúcar, harina) con alertas de stock mínimo.

5. **Privacidad y Respaldos:**
   - Funciona 100% offline en el navegador.
   - Guarda los datos automáticamente en `localStorage`.
   - Botón para exportar e importar copias de seguridad en formato JSON.

## 💻 Cómo Usar

Simplemente abre el archivo `index.html` en cualquier navegador web moderno (Google Chrome, Microsoft Edge, etc.) o haz doble clic en `Abrir_Chpa.bat`.
