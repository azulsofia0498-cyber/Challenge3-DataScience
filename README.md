# Challenge3-DataScience
# 📊 Challenge Telecom X - Parte 2: Predicción de Churn con Machine Learning

Este proyecto corresponde a la **Parte 2 del Challenge Telecom X**, donde se desarrolla un modelo de **Machine Learning** para predecir qué clientes podrían cancelar el servicio (*churn*).

A partir del **dataset previamente analizado y limpiado en la Parte 1**, se construyó un pipeline de análisis y modelado que permite identificar clientes con mayor riesgo de abandono y así apoyar estrategias de retención basadas en datos.

---

## 🎯 Objetivos del proyecto

- Preparar y organizar los datos para su uso en modelos de **Machine Learning**.
- Analizar si existe **desbalance de clases** y su impacto en los modelos.
- Probar y comparar **distintos modelos de clasificación**.
- Evaluar el desempeño utilizando **métricas adecuadas para problemas de churn**.
- Identificar **las variables más influyentes** en la cancelación de clientes.
- Obtener **conclusiones y recomendaciones** útiles para el negocio.

---

## 🧠 Metodología

El proyecto siguió las siguientes etapas:

1. **Preparación de datos**
   - Uso del dataset limpio `telecomx_clean.csv`.
   - Transformación de variables categóricas.
   - Preparación del dataset para entrenamiento de modelos.

2. **Entrenamiento de modelos**
   - Implementación de distintos **modelos de clasificación**.
   - Comparación de desempeño entre ellos.

3. **Evaluación**
   - Uso de métricas relevantes para churn, como:
     - Accuracy
     - Precision
     - Recall
     - F1-score

4. **Análisis de variables**
   - Identificación de las variables que más influyen en la probabilidad de cancelación.

---

## 📈 Resultados

El modelo de **Regresión Logística** fue el que mostró **mejor desempeño general**, logrando un buen equilibrio entre precisión y capacidad de detectar clientes con riesgo de abandono.

El análisis indica que el **churn no depende de un solo factor**, sino de una combinación de variables como:

- Tipo de contrato
- Costos del servicio
- Antigüedad del cliente
- Forma de interacción con el servicio

---

## 💡 Conclusiones

El uso de **modelos predictivos** permite anticipar qué clientes tienen mayor probabilidad de cancelar el servicio. Esto facilita que las empresas puedan **implementar estrategias de retención más efectivas**, tomar decisiones basadas en datos y reducir la pérdida de clientes.




