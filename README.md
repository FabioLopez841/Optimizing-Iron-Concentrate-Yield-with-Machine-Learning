# 🔧 Optimizing Iron Concentrate Yield with Machine Learning / Optimización del Porcentaje de Hierro en el Concentrado mediante Machine Learning  

---

![Project Cover](https://imgur.com/ytZ9LCf.png)

---

## 📌 Overview / Resumen

This project presents a complete Machine Learning workflow aimed at optimizing the **% Iron Concentrate** produced in a mineral flotation process. The analysis incorporates operational variables such as pH, reagent dosage, feed composition, and pulp density to improve decision-making, maximize recovery, and reduce inefficiencies in mineral processing plants.

Este proyecto desarrolla un flujo completo de Machine Learning orientado a optimizar el **% de Hierro en el Concentrado** en un proceso de flotación minera. El análisis integra variables operativas como pH, dosificación de reactivos, composición de alimentación y densidad de pulpa para mejorar la toma de decisiones, maximizar la recuperación y reducir ineficiencias en plantas de procesamiento mineral.

---

## 🔄 Workflow Funnel / Embudo de Trabajo

| Step / Paso | Description (EN) / Descripción (ES) | Contribution / Contribución |
|--------------|-------------------------------------|------------------------------|
| **1. Data Import** | Load raw operational dataset and validate sensor integrity. <br> Carga del dataset operativo y validación de lecturas de sensores. | **10%** |
| **2. Data Cleaning & Preprocessing** | Handle missing values, convert numeric strings, detect anomalies. <br> Manejo de nulos, conversión de datos numéricos, detección de anomalías. | **25%** |
| **3. Feature Engineering** | Create derived variables and normalization pipelines. <br> Creación de variables derivadas y normalización. | **15%** |
| **4. Exploratory Data Analysis (EDA)** | Understand correlations, process trends, and variable dependencies. <br> Análisis de correlación, tendencias y dependencias entre variables. | **20%** |
| **5. Predictive Modeling** | Train ML models (RF, XGBoost) and evaluate performance. <br> Entrenamiento y evaluación de modelos ML (RF, XGBoost). | **20%** |
| **6. Optimization & Reporting** | Apply Bayesian Optimization and summarize operational insights. <br> Optimización bayesiana y reporte de hallazgos operativos. | **10%** |

---

## 📊 Key Insights / Principales Hallazgos

- **High predictive accuracy** achieved by XGBoost (R² = 0.9574).  
  **Alta precisión predictiva** obtenida con XGBoost (R² = 0.9574).

- **Most influential variables:**  
  - % Silica Feed  
  - % Iron Feed  
  - Pulp pH  
  - Amina Reagent Flow  
  **Variables más influyentes:**  
  - % Sílice en alimentación  
  - % Hierro en alimentación  
  - pH de pulpa  
  - Flujo de reactivo Amina  

- **Operational anomalies detected:** 7,264 irregular conditions across 736,282 records.  
  **Anomalías detectadas:** 7,264 condiciones irregulares en 736,282 registros.

- **Optimized output:**  
  - Best predicted Iron Concentrate: **66.52%**  
  **Resultado optimizado:**  
  - Mejor valor predicho de Hierro en Concentrado: **66.52%**
---

## 🧰 Tech Stack / Herramientas

`Python` · `Pandas` · `NumPy` · `Scikit-learn` · `XGBoost` · `Matplotlib` · `Seaborn` · `SciPy` · `Jupyter Notebook`

---


## 🚀 Next Steps / Próximos Pasos

### 🔍 Technical Next Steps (EN)
- Integrate real-time sensor data for predictive control.  
- Develop a digital twin for the flotation circuit.  
- Implement time-series forecasting to predict drift in pH, density, and reagent flow.  
- Expand optimization to multi-objective goals (Iron ↑, Silica ↓, Reagent Cost ↓).

### 🔧 Technical Next Steps (ES)
- Integrar datos en tiempo real para control predictivo.  
- Desarrollar un “digital twin” del circuito de flotación.  
- Implementar modelos de series de tiempo para anticipar desvíos de pH y densidad.  
- Expandir la optimización a objetivos múltiples (Hierro ↑, Sílice ↓, Costo de reactivos ↓).

---

### 🏭 Industry Recommendations (Mining Sector)

**EN:**  
- Deploy anomaly-based alarms to prevent quality deviations.  
- Use ML-driven reagent dosing to improve recovery and reduce waste.  
- Prioritize continuous pH monitoring, as small deviations significantly impact concentrate quality.  
- Adopt hybrid control systems combining ML predictions with operator expertise.

**ES:**  
- Implementar alarmas basadas en anomalías para prevenir desviaciones de calidad.  
- Usar dosificación de reactivos basada en ML para mejorar recuperación y reducir desperdicio.  
- Priorizar monitoreo continuo de pH, ya que pequeñas variaciones afectan fuertemente la calidad del concentrado.  
- Adoptar sistemas híbridos que combinen predicción ML y experiencia del operador.



---

## 👤 Author / Autor

**Fabio López**  
*Data Analyst | Machine Learning | Industrial Optimization | Python*  
📧 fabio.lopez.analyst@gmail.com  
🌐 https://www.linkedin.com/in/fabiolopezt/

---

> 💬 *"Data-driven optimization transforms industrial performance — La optimización basada en datos transforma el rendimiento industrial."*
