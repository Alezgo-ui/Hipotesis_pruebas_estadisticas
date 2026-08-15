# Validando hipótesis de negocio con pruebas estadísticas

📊 Introducción:

Soy analista de datos en el equipo de marketing digital de una empresa de ecommerce.

Se ejecutó un experimento A/B en la página de inicio (landing page), comparando dos versiones (A y B) con el objetivo de mejorar la tasa de conversión y el valor económico por usuario.

La empresa necesita una decisión basada en datos para definir qué versión implementar, considerando la tasa de conversión, el gasto promedio y el comportamiento por canal de tráfico y tipo de usuario.

Para ello, trabajare con el dataset:

  - landing_experiment: que contiene información de usuarios expuestos a las versiones A y B, incluyendo región, dispositivo, fuente de tráfico, tipo de usuario, conversión y gasto.

---


## 📂 Contenido del repositorio

- `data_cleaning_eda_ecommerce.ipynb`
  → Notebook  completo de limpieza y análisis exploratorio de datos (EDA) hasta la generación de insights listos para tomar decisiones de negocio.

- `Dashboard Rappi.pbix`
  → Archivo que contiene el dashboard para descarga/lectura en PowerBI.

- `Dashboard.md`
  → Notebook que describe el proceso de creacion completo y logica del dashboard.

- `screenshots`
  → Referencias visuales para el dashboard.    

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Alezgo-ui/Ecommerce_datacleaning_dashboard/blob/main/data_cleaning_eda_ecommerce_ipynb.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `data_cleaning_eda_ecommerce.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Resumen del análisis

- Limpieza y preparación de datos con pandas
- Pipeline propio de EDA reutilizable
- Análisis de rentabilidad y comportamiento de ventas
- Análisis de retención por cohortes en SQL
- Análisis de funnel de conversión en SQL
- Prueba de hipótesis estadística (A/B test con z-test)
- Modelo de datos en Power BI (esquema de estrella)
- Dashboard 1: Overview Ejecutivo
- Dashboard 2: Detalle / Drill-through
