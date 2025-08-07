# 📊 Challenge Telecom X: Análisis de Evasión de Clientes - Parte 2

Este proyecto forma parte del programa ONE (Oracle Next Education) junto a Alura Latam, y tiene como objetivo principal **predecir la cancelación (churn)** de clientes en una empresa de telecomunicaciones utilizando modelos de Machine Learning y análisis exploratorio de datos.

## 📁 Contenido del Proyecto

1. **Carga y exploración de datos**
   - Limpieza y tratamiento de datos nulos.
   - Transformación de tipos de datos y detección de outliers.

2. **Análisis exploratorio de datos (EDA)**
   - Visualización de distribución de cancelaciones.
   - Análisis de correlaciones y patrones de comportamiento.

3. **Preprocesamiento**
   - Codificación de variables categóricas (One-Hot Encoding).
   - Escalado de variables numéricas.
   - Verificación del desbalance de clases (churn).

4. **Modelado predictivo**
   - Modelos implementados:
     - Regresión Logística
     - Random Forest
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
   - Evaluación de desempeño con matriz de confusión y métricas (accuracy, precision, recall, f1-score).

5. **Interpretación y conclusiones**
   - Análisis de importancia de variables en cada modelo.
   - Identificación de factores clave para la cancelación.
   - Recomendaciones estratégicas para retención de clientes.

## 🔍 Principales Hallazgos

- Los factores que más influyen en la cancelación incluyen:
  - Tipo de servicio de internet (especialmente "Fiber optic").
  - Métodos de pago electrónicos.
  - Facturación electrónica y consumo mensual alto.
  - Antigüedad del cliente (tenure).

- Modelos con mejor desempeño:
  - 🔝 **Random Forest** y **SVM**, con mayor precisión para detectar clientes propensos a cancelar.

## 🛠 Tecnologías utilizadas

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook / Google Colab

## 🧠 Autores y Créditos

Este proyecto fue desarrollado como parte del desafío práctico del curso **Formación en Ciencia de Datos - ONE/Alura**.

---

