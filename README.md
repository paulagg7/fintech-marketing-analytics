# fintech-marketing-analytics
# Análisis de campañas de marketing - Fintech

## 📌 Descripción del proyecto
Este proyecto tiene como objetivo analizar el rendimiento de campañas telefónicas de marketing de una empresa fintech, identificar los principales factores que influyen en la conversión de clientes y desarrollar un modelo predictivo que permita optimizar la estrategia comercial.

A partir de los datos disponibles, se realiza un análisis exploratorio (EDA), se construye un modelo de clasificación y se desarrolla un dashboard orientado a negocio para facilitar la toma de decisiones.

---

## 🎯 Objetivos
- Analizar el comportamiento de los clientes y las campañas
- Identificar variables clave que impactan en la conversión
- Construir un modelo predictivo de suscripción
- Evaluar el rendimiento del modelo
- Diseñar un dashboard para la toma de decisiones

---

## 📊 Análisis exploratorio (EDA)
En esta fase se analizan:
- Distribución de variables
- Relación entre variables y conversión
- Detección de patrones y tendencias
- Identificación de posibles problemas (desbalanceo, valores nulos, etc.)

---

## 🤖 Modelo predictivo
Se desarrolla un modelo de clasificación (Regresión Logística) para predecir la probabilidad de conversión de cada cliente.

Evaluación del modelo mediante:
- AUC-ROC
- Accuracy
- Precision y Recall
- Análisis por deciles para aplicación en negocio

---

## 📈 Dashboard (Looker Studio)
Se ha diseñado un dashboard interactivo orientado a negocio que permite:

- Analizar la conversión global
- Identificar segmentos de alto valor
- Evaluar el rendimiento del modelo
- Simular escenarios de priorización (Top % de clientes)

👉 Acceso al dashboard:  
https://lookerstudio.google.com/reporting/9f510470-2e06-416d-8358-6ff3da3cad54

---

## 🗂️ Estructura del repositorio

- `datos/`  
  Contiene el dataset original utilizado en el análisis y la documentación de variables.

- `notebooks/`  
  Incluye los notebooks principales del proyecto:
  - Análisis exploratorio (EDA)
  - Desarrollo y evaluación del modelo

- `dashboard/`  
  Capturas del dashboard y acceso a la versión interactiva.

---

## 🛠️ Tecnologías utilizadas
- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib y Seaborn
- Jupyter Notebook
- Looker Studio

---

## 💡 Conclusión
Este proyecto demuestra cómo, a partir del análisis de datos y el uso de modelos predictivos, es posible mejorar la eficiencia de las campañas de marketing y optimizar la toma de decisiones en entornos de negocio.

