# S9-Student-Ecommerce-AB-Landing
Análisis de experimento A/B y optimización de conversión para landing page de e-commerce en Python.
## 📋 Descripción del Proyecto
Este proyecto forma parte de mis prácticas y proyectos de análisis de datos. Consiste en un **análisis completo de un experimento A/B** aplicado a la página de inicio (landing page) de un e-commerce con el objetivo de evaluar el impacto en la tasa de conversión y el gasto promedio por usuario entre dos versiones de la página (`A` y `B`).

---

## 🎯 Objetivos Principales
1. **Validación de Datos:** Verificar la integridad de las variables (usuarios únicos, rangos de fechas, valores nulos y tipos de datos).
2. **Análisis Financiero:** Comparar el gasto promedio por usuario entre la Página A y la Página B mediante pruebas de hipótesis estadísticas.
3. **Optimización de Conversión (CRO):** Analizar y comparar las tasas de conversión globales de ambas páginas.
4. **Segmentación de Tráfico y Usuarios:** Evaluar si la fuente de tráfico o el tipo de usuario (nuevo vs. recurrente) tienen una asociación estadísticamente significativa con la conversión.

---

## 🛠️ Tecnologías y Librerías Utilizadas
El análisis fue desarrollado en **Python**, utilizando las siguientes librerías de ciencia de datos:
* **Pandas & NumPy:** Manipulación y limpieza de datos.
* **SciPy:** Pruebas estadísticas (Prueba t de Student, Pruebas Z de proporciones, Chi-cuadrada).
* **Matplotlib & Seaborn:** Visualización de datos e interpretación gráfica.

---

## 📊 Principales Hallazgos y Conclusiones
* **Superioridad de la Página B:** La Página B superó a la Página A tanto en la tasa de conversión (**15.96% vs. 12.57%**) como en el gasto promedio de los usuarios convertidos (**68.75 vs. 61.09**), mostrando diferencias estadísticamente significativas ($p < 0.05$).
* **Canales de Tráfico:** Se encontró una ligera asociación estadística entre las fuentes de tráfico y la conversión, destacando canales como *Email* y *Ads* con mejor rendimiento.
* **Tipo de Usuario:** No se encontraron diferencias significativas entre usuarios nuevos y recurrentes respecto a su probabilidad de conversión, lo que sugiere enfocar los esfuerzos de optimización en el diseño general de la página en lugar de personalizar por veteranía.
