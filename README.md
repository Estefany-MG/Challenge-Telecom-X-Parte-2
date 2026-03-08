# 🔮 Telecom X (Parte 2): Predicción de Evasión de Clientes (Churn)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine_Learning-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Processing-green.svg)

## 🎯 Misión del Proyecto
En esta segunda fase del proyecto para **Telecom X**, hemos dado el salto de Analistas a Científicos de Datos. El objetivo es utilizar los datos limpios obtenidos en la fase de ETL para entrenar **modelos predictivos de Machine Learning**.

Buscamos predecir qué clientes tienen mayor riesgo de cancelar su servicio (Churn) e identificar las variables que más influyen en esta decisión, permitiendo a la empresa tomar acciones preventivas.

## ⚙️ Metodología
1. **Preparación de Datos:** Eliminación de variables irrelevantes (`customerID`), codificación de variables categóricas (One-Hot Encoding) y escalado de datos.
2. **Análisis de Correlación:** Identificación de relaciones estadísticas entre los servicios contratados y la tasa de abandono.
3. **Modelado (Machine Learning):** Separación de datos (Train/Test) y entrenamiento de modelos de clasificación (Regresión Logística y Random Forest).
4. **Evaluación:** Análisis de la importancia de las variables (Feature Importance) y métricas de rendimiento (Accuracy, Recall).

## 🚀 Instrucciones de Ejecución
1. Clona este repositorio: `git clone https://github.com/tu-usuario/telecom-x-ml.git`
2. Asegúrate de tener el archivo `datos_tratados.csv` (generado en la Parte 1) en el directorio raíz.
3. Instala las dependencias: `pip install pandas scikit-learn matplotlib seaborn`
4. Ejecuta el notebook `telecom_parte2.ipynb`.
