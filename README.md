# challenge2-data-science-LATAM_Nu-ez_Coronel

# 📊 Telecom X – Análisis de Evasión de Clientes (Churn)

## 📌 Propósito del proyecto

El objetivo de este proyecto es realizar un análisis exploratorio de datos (EDA) sobre la evasión de clientes (Churn) de la empresa Telecom X, con el fin de identificar patrones y factores que influyen en la cancelación de servicios.

A través de técnicas de ETL (Extracción, Transformación y Carga) y visualización de datos, se busca preparar información limpia y relevante que sirva como base para futuros modelos predictivos desarrollados por el equipo de Ciencia de Datos.

---

## 🧠 Alcance del análisis

- Carga de datos desde un archivo JSON
- Limpieza y transformación de datos
- Análisis exploratorio de variables clave
- Identificación de posibles causas de evasión
- Generación de conclusiones basadas en datos

---

## 📁 Estructura del proyecto

TelecomX/
│
├── TelecomX_Data.json # Dataset principal en formato JSON
├── TelecomX_LATAM.ipynb # Notebook con el análisis completo
├── TelecomX_diccionario.md # Diccionario de datos
└── README.md # Documentación del proyecto


---

## 📊 Ejemplos de análisis y gráficos realizados

Durante el análisis exploratorio se generaron distintos gráficos para comprender el comportamiento de la evasión de clientes, entre ellos:

### 🔹 Distribución de Churn
- Gráfico de conteo que muestra la proporción de clientes que abandonaron el servicio frente a los que permanecen.

### 🔹 Churn según tipo de contrato
- Se identificó que los clientes con contratos mensuales presentan una mayor tasa de evasión en comparación con contratos anuales o de mayor duración.

### 🔹 Churn vs Antigüedad del cliente
- Los clientes con menor antigüedad (tenure) tienden a abandonar el servicio con mayor frecuencia.

### 🔹 Churn vs Cargos mensuales
- Se observa una mayor evasión en clientes con cargos mensuales elevados, lo que sugiere posibles problemas de percepción de valor.

---

## 📌 Principales insights obtenidos

- El tipo de contrato es uno de los factores más influyentes en la evasión.
- La retención temprana es crítica, ya que los clientes nuevos abandonan con mayor frecuencia.
- Los cargos mensuales altos** están asociados a una mayor probabilidad de churn.
- Estas variables deben ser consideradas como claves para futuros modelos predictivos.

---

## ▶️ Instrucciones para ejecutar el notebook

### Requisitos
- Cuenta de Google
- Acceso a Google Colab
- Archivo `TelecomX_Data.json`

### Pasos

1. Abrir [Google Colab](https://colab.research.google.com/)
2. Crear un nuevo notebook o abrir `TelecomX_LATAM.ipynb`
3. Subir el archivo `TelecomX_Data.json` al entorno de Colab
4. Ejecutar las celdas en orden (de arriba hacia abajo)
5. Verificar que las gráficas y resultados se muestren correctamente

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## ✍️ Autor

Proyecto desarrollado como parte del desafío de análisis de datos del programa ONE / Alura LATAM.

