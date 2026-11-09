# Análisis integral Rappi Plus
Se realiza un análisis de la aplicación con datos en el período 2025, evaluando la rentabilidad del negocio, conversión de usuarios, retención por cohortes y pruebas de hipótesis sobre una prueba A/B.

## Objetivo

El objetivo de este proyecto es evaluar el desempeño del servicio RappiPlus para apoyar decisiones de negocio basadas en datos.

**Datasets**

rappiplus_orders_raw.csv → información de pedidos, precios, descuentos y revenue
rappiplus_catalog.csv → costos de productos, categorías y proveedores
rappiplus_marketing_spend.csv → inversión en marketing por canal y país
events / users / user_activity (SQL) → comportamiento del usuario dentro de la plataforma
experiment_checkout_ui.csv → resultados de un experimento A/B en el checkout

**Etapas de análisis**

🔍 Evaluar si podemos confiar en los datos (calidad de datos en Python)

💰 Analizar si el negocio es rentable (revenue, costos y profit)

🛒 Entender dónde se pierden los usuarios (funnel de conversión)

🔁 Evaluar si los usuarios regresan (retención por cohortes)

🧪 Validar si los cambios generan impacto (test estadístico)

📊 Comunicar los resultados (dashboard en BI)


**Como ejecutar el notebook**

Desde el siguiente boton dando clic para ir al notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qncKIN3L-49Xy2BszDJ8lCQgqS3QHBnz?authuser=1#scrollTo=6ae9ff72)

**Guia de reproducción**

Descarga los archivos csv y cargarlos a colab. 

Dirígete al menú lateral izquierdo de tu Google Colab y haz clic en el ícono de Carpeta (Archivos).

Haz clic en el primer ícono de arriba que dice "Subir al almacenamiento de sesiones" (representado con una pequeña carpeta y una flecha hacia arriba).

Selecciona tu archivo desde tu PC.
