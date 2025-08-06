# Predicción de Cancelación de Clientes — Telecom X

## Objetivo del Proyecto

Como científico de datos, tu misión fue desarrollar modelos predictivos para **anticipar la cancelación de clientes** (churn) de la empresa **Telecom X**, ayudando a mejorar la retención de usuarios y optimizar campañas comerciales.

---

## Herramientas utilizadas

- Python + Pandas, NumPy
- Visualización: Matplotlib, Seaborn
- Modelado: Scikit-learn (Regresión Logística, Árbol de Decisión)
- Normalización: StandardScaler
- Evaluación: Matriz de confusión, Accuracy, Precision, Recall, F1-score

---

## Etapas del análisis

### 1. Exploración y limpieza de datos
- Eliminación de valores faltantes y columnas no informativas.
- Conversión de variables categóricas.
- Detección de inconsistencias.

### 2. Análisis de correlación
- Matriz de correlación con foco en la variable `Churn`.
- Selección de variables con mayor impacto en la cancelación.

### 3. Visualización dirigida
- Análisis de relación entre:
  - `Contract` y `Churn`
  - `TotalCharges` y `Churn`
- Gráficos de cajas y dispersión.

### 4. Modelado predictivo
- **Regresión Logística** con normalización (StandardScaler)
- **Árbol de Decisión** sin necesidad de escalar

---

## Resultados del modelo

| Modelo                | Accuracy | Precisión | Recall | F1-score |
|-----------------------|----------|-----------|--------|----------|
| Regresión Logística   | 0.82     | 0.70      | 0.62   | 0.66     |
| Árbol de Decisión     | 0.79     | 0.66      | 0.69   | 0.67     |

> *Nota: los valores anteriores son ilustrativos. Consultar notebook final para métricas exactas.*

---

## Conclusiones estratégicas

- Los clientes con **contratos mensuales** y **métodos de pago automáticos** tienen mayor tendencia a cancelar.
- Es posible predecir con buena precisión la cancelación y tomar acciones preventivas.
- El modelo de árbol ofrece interpretabilidad clara con reglas simples y buen recall.

---

## Recomendaciones para Telecom X

- Aplicar el modelo predictivo para identificar clientes en riesgo de cancelar.
- Enfocar estrategias de fidelización en perfiles identificados como de riesgo.
- Realizar seguimiento periódico y retrain del modelo con nuevos datos.

---

## Archivos entregables

- `churn_analysis.ipynb`: notebook completo con análisis, modelado y visualización.
- `datos_limpios.csv`: datos procesados y listos para el modelo.
- `README.md`: este archivo.

---

## Rol del Científico de Datos

> "Convertir datos en decisiones: tu análisis predictivo permite a Telecom X anticiparse a la pérdida de clientes, retener valor y optimizar su estrategia comercial."
