# Proyecto de Análisis de Abandono de Clientes - Telecom X

## 📊 Visión General del Proyecto
Este repositorio contiene un proyecto de análisis de datos enfocado en comprender y reducir la tasa de abandono de clientes (churn) en Telecom X, una empresa ficticia del sector telecomunicaciones.

Como parte del rol de Asistente de Análisis de Datos, el objetivo principal fue:

- Recopilar, limpiar, procesar y analizar datos de clientes para identificar los factores clave que contribuyen a su abandono.

El análisis exploratorio de datos (EDA) realizado en este proyecto sirve como base para futuros modelos predictivos y estrategias de retención personalizadas.
---
## 🎯 Objetivo del Análisis

El problema central que enfrenta Telecom X es una alta tasa de cancelaciones de servicio. Este proyecto busca:

* 🔍 Identificar patrones y tendencias entre los clientes que abandonan.

* 📈 Determinar variables clave (demográficas, de servicio, de contrato y gasto) asociadas al churn.

* 🧠 Extraer insights accionables para que el equipo de Data Science y la gerencia comprendan:

* **Por qué se van los clientes.**

* **¿Qué acciones pueden tomar para evitarlo?**

  ---

## 📂 Estructura del Repositorio

* `README.md`: Este archivo, con una descripción general del proyecto.
* `TelecomX.ipynb`: El archivo principal del proyecto que contiene todo el código Python, el análisis, las visualizaciones y el informe final.
---

## 🛠️ Herramientas y Librerías Utilizadas

El análisis se llevó a cabo utilizando el entorno de Python, con las siguientes librerías principales:

* **`pandas`**: Para la manipulación y el procesamiento de datos.
* **`numpy`**: Para operaciones numéricas eficientes.
* **`matplotlib`**: Para la creación de gráficos y visualizaciones estáticas.
* **`seaborn`**: Para la creación de visualizaciones estadísticas atractivas y complejas.
---
## 🚀 Flujo de Trabajo del Análisis

El proyecto se desarrolló en las siguientes etapas:

### 1. 📥 Carga de Datos
- Importación del dataset en formato **JSON**.

### 2. 🧹 Limpieza y Preprocesamiento
- Normalización del JSON (estructura anidada).
- Tratamiento de valores nulos y conversión de tipos.
- Transformación de variables categóricas (`'Yes'` / `'No'` → `1` / `0`).
- Unión de múltiples DataFrames en un dataset final consolidado.

  ---
### 3. 📊 Análisis Exploratorio de Datos (EDA)
- Cálculo de la **tasa general de churn**.
- Análisis de churn por variables **categóricas** y **numéricas**.
- Uso de **estadísticas descriptivas**, **gráficos de barras**, **boxplots** y **histogramas** para detectar patrones relevantes.
