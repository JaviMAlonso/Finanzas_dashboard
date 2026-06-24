# URL

https://javimalonso.github.io/Finanzas_dashboard/

# 💰 Finanzas

Aplicación web de finanzas personales desarrollada en HTML, CSS y JavaScript puro.

Permite registrar ingresos y gastos, crear metas de ahorro, gestionar deudas y visualizar la evolución financiera mediante gráficos interactivos.

## ✨ Características

### 📊 Gestión de ingresos y gastos
- Registro de transacciones.
- Clasificación por categorías.
- Diferenciación entre ingresos y gastos.
- Historial completo de movimientos.
- Eliminación de transacciones.

### 📈 Resumen financiero
- Balance total actualizado automáticamente.
- Gastos del mes actual.
- Ahorro acumulado.

### 🎯 Metas de ahorro
- Creación de objetivos de ahorro.
- Seguimiento visual mediante barras de progreso.
- Añadir nuevas aportaciones.
- Eliminación de metas.

### 💳 Gestión de deudas
- Registro de préstamos y deudas.
- Control del importe total y amortizado.
- Registro del tipo de interés anual.
- Seguimiento visual del progreso de pago.
- Actualización de pagos realizados.

### 📉 Gráficos
- Evolución mensual de ingresos y gastos.
- Visualización mediante Chart.js.

### 💾 Persistencia de datos
- Guardado automático en `localStorage`.
- Recuperación automática al abrir la aplicación.

### 📂 Importación y exportación
- Exportación de todos los datos a un archivo TXT.
- Importación desde archivos TXT previamente exportados.
- Sustitución completa de los datos actuales mediante confirmación.

---

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Chart.js 4.4.1

---

## 📁 Estructura del proyecto

Todo el proyecto está contenido en un único archivo para facilitar su despliegue y distribución.

---

## 🚀 Instalación

No requiere instalación.

1. Descargar el archivo:

2. Abrirlo directamente en cualquier navegador moderno:

- Chrome
- Firefox
- Edge
- Safari

---

## 💡 Uso

### Añadir una transacción

1. Introducir descripción.
2. Introducir importe.
3. Seleccionar:
   - Ingreso
   - Gasto
4. Seleccionar categoría.
5. Elegir fecha.
6. Pulsar **"Añadir transacción"**.

### Crear una meta de ahorro

1. Introducir nombre.
2. Definir objetivo económico.
3. Indicar cantidad ya ahorrada (opcional).
4. Pulsar **"Crear meta"**.

### Registrar una deuda

1. Introducir nombre de la deuda.
2. Indicar importe total.
3. Indicar importe ya amortizado (opcional).
4. Añadir interés anual (opcional).
5. Pulsar **"Añadir deuda"**.

---

## 📤 Exportación de datos

La aplicación permite exportar toda la información a un archivo TXT mediante el botón:

El archivo generado incluye:

- Transacciones
- Metas de ahorro
- Deudas

---

## 📥 Importación de datos

La aplicación permite restaurar información previamente exportada mediante:

Durante la importación se mostrará un resumen de los datos encontrados y se solicitará confirmación antes de reemplazar los datos actuales.

---

## 🔒 Almacenamiento local

No existe comunicación con servidores externos ni bases de datos.
