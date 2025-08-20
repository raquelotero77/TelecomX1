# TelecomX1
# 📊 Análisis de Evasión de Clientes (Churn) - TelecomX

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de una empresa de telecomunicaciones y detectar patrones que expliquen la evasión (churn). A través de técnicas de limpieza, visualización y análisis exploratorio, se identifican variables clave que influyen en la cancelación del servicio.

---

## 🧠 Objetivo

Comprender los factores que llevan a los clientes a cancelar sus contratos y proponer estrategias basadas en datos para reducir la tasa de evasión.

---

## 📁 Estructura del Proyecto

- `TelecomX_Data.json`: Dataset original en formato JSON.
- `notebook.ipynb`: Notebook principal con todo el análisis.
- `README.md`: Este archivo de documentación.

---

## 🧹 Limpieza y Tratamiento de Datos

- Lectura del JSON desde GitHub.
- Normalización de estructuras anidadas (`customer`, `account`, `internet`, etc.).
- Conversión de tipos de datos.
- Detección y corrección de inconsistencias categóricas.
- Creación de la columna `Cuentas_Diarias` para análisis granular de facturación.

---

## 📊 Análisis Exploratorio

Se realizaron visualizaciones para entender la distribución de churn y su relación con otras variables:

- **Distribución de Churn**: Gráfico de barras.
- **Churn vs Variables Categóricas**: Género, contrato, método de pago, tipo de internet.
- **Churn vs Variables Numéricas**: Tenure, ChargesTotal, ChargesMonthly.
- **Boxplots y histogramas** para detectar patrones y outliers.

---

## 🔍 Principales Insights

- Los clientes con contrato mensual y bajo tenure presentan mayor evasión.
- El método de pago `electronic check` está asociado con mayor churn.
- Los usuarios de `fiber optic` muestran mayor tendencia a cancelar.
- Clientes con mayor gasto total y antigüedad tienden a permanecer.

---

## ✅ Recomendaciones

- Implementar estrategias de fidelización para clientes nuevos.
- Incentivar contratos de largo plazo con beneficios.
- Mejorar la experiencia de pago y atención en segmentos críticos.
- Entrenar modelos predictivos para anticipar churn y actuar proactivamente.

---

## 🚀 Tecnologías Utilizadas

- Python
- Pandas
- Seaborn & Matplotlib
- Jupyter Notebook

---

## 📌 Autor

**Raquel Otero**  

Apasionada por el análisis de datos y proyectos con impacto social.

---
