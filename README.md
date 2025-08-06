# 📊 Telecom X - Predicción de Cancelación de Clientes (Churn)

Este proyecto forma parte del desafío final del curso de Ciencia de Datos de **Alura**. El objetivo es desarrollar un modelo de Machine Learning capaz de predecir qué clientes tienen mayor probabilidad de cancelar sus servicios, ayudando así a la empresa **Telecom X** a tomar decisiones estratégicas para reducir la tasa de churn.

---

## 🧠 Objetivos del Proyecto

- Preprocesar y preparar los datos para modelado.
- Analizar correlaciones entre variables y la variable objetivo (`Churn`).
- Entrenar al menos dos modelos de clasificación.
- Evaluar y comparar el desempeño de los modelos.
- Interpretar la importancia de las variables y generar recomendaciones estratégicas.

---

## ⚙️ Tecnologías y Bibliotecas

- Python 3.11+
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- imbalanced-learn

---

## 🧰 Estructura del Proyecto

### 📁 `notebooks/`
Contiene los pasos completos del proyecto en etapas:
1. **Preprocesamiento** de datos (limpieza, codificación, normalización).
2. **Análisis exploratorio** y de correlación.
3. **Entrenamiento de modelos**: Regresión Logística y Random Forest.
4. **Evaluación** de métricas (precisión, recall, f1-score, AUC-ROC).
5. **Interpretación** de variables más relevantes.
6. **Conclusiones** y recomendaciones de negocio.

### 📁 `data/`
Conjunto de datos original proporcionado por el curso (**no incluido** en este repo por temas de licencia, pero se puede obtener desde Alura).

---

## 🔍 Resultados Destacados

- **Modelos entrenados**:
  - Regresión Logística (con normalización).
  - Random Forest (sin normalización).
- **Métricas clave (Random Forest)**:
  - AUC-ROC: 0.80+
  - Accuracy: 0.79
- **Variables más influyentes**:
  - Tiempo como cliente (`tenure`).
  - Método de pago.
  - Tipo de contrato.
  - Soporte técnico.
  - Seguridad online.

---

## 📚 Créditos

Proyecto desarrollado por Iván Roldán como parte del curso de Ciencia de Datos de **Alura**.
