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

- `data`
  → Carpeta con el archivo(s) csv necesarios para reproducir el analisis.

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

## 🎯 Objetivos:

Explorar, validar y analizar estadísticamente el experimento A/B para identificar diferencias significativas entre las páginas y traducir los resultados en recomendaciones para el negocio.

- Explorar y validar un dataset proveniente de un experimento A/B real.
- Comparar métricas de negocio mediante pruebas estadísticas apropiadas.
- Interpretar resultados estadísticos desde una perspectiva de negocio.
- Visualizar resultados para respaldar conclusiones.
- Comunicar hallazgos o insights de forma clara a stakeholders no técnicos.
