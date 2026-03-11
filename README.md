# Challenge_Telecom_X_Parte2

# 📊 Telecom X – Predicción de Cancelación de Clientes (Churn)

## 📌 Descripción

Este proyecto tiene como objetivo **predecir la cancelación de clientes (Churn)** en Telecom X utilizando modelos de **Machine Learning**.
A partir de datos históricos de clientes se analizan variables relevantes para identificar patrones que permitan anticipar qué clientes tienen mayor probabilidad de cancelar sus servicios.

---

## 🎯 Objetivo

* Preparar los datos para modelos predictivos.
* Analizar variables relacionadas con el churn.
* Entrenar modelos de clasificación.
* Evaluar su desempeño e identificar factores clave de cancelación.

---

## 📂 Estructura del Proyecto

```
TelecomX-Churn/
│
├── TelecomX_Parte2_Modelo.ipynb
├── datos_tratados.csv
└── README.md
```

---

## 🧹 Preparación de los Datos

* Clasificación de variables en **numéricas** y **categóricas**.
* Codificación de variables categóricas con **One-Hot Encoding**.
* Normalización de variables para modelos sensibles a la escala.
* División del dataset en **entrenamiento (70%)** y **prueba (30%)**.

---

## 🤖 Modelos Utilizados

* **Regresión Logística**
* **Random Forest**

Los modelos se evaluaron utilizando **accuracy, precision, recall, f1-score y matriz de confusión**.

---

## 📊 Insights Principales

Factores más relacionados con la cancelación:

* Contratos **mensuales**
* **Poco tiempo** como cliente
* **Cargos mensuales altos**

---


## 🧠 Conclusión

El modelo **Regresión Logística** mostró mejor desempeño para predecir churn.
Los resultados permiten identificar clientes con alto riesgo de cancelación 
