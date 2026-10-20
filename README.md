# 📊 Telecom X — Part 2: Churn Prediction & Retention Strategy  
**Machine Learning · Churn Drivers · Customer Retention**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)

This project is the second part of the Telecom X Challenge, where the role evolves from data analyst to data scientist. It builds a predictive model to anticipate customer churn and translates model insights into actionable retention strategies for marketing and CRM teams.

The main goal is to develop a robust churn prediction model, interpret the key drivers of customer attrition and deliver strategic recommendations to improve customer retention.

## 🎯 Project Objectives

- Build a churn prediction model with strong performance metrics.
- Identify the most influential drivers of customer churn.
- Generate executive visualizations (ROC curve, driver analysis, dashboard).
- Deliver a final PDF report with strategic conclusions.
- Provide a clear, reproducible and business-oriented notebook.

## 🗂️ Workflow

### ✔️ Data Preparation
- Load the cleaned dataset from Part 1.
- Additional cleaning and removal of irrelevant columns.
- Categorical encoding using One-Hot Encoding.
- Stratified Train/Test split.

### ✔️ Modeling
- Random Forest as the main classification model.
- Churn predictions and probability scores.
- Model evaluation:
  - Accuracy
  - Precision / Recall / F1-score
  - ROC-AUC
  - Technical and executive ROC curve

### ✔️ Interpretation
- Feature importance analysis (%).
- Identification of the Top 3 churn drivers.
- Impact visualization for stakeholders.
- Final dashboard for executive decision-making.

### ✔️ Deliverables
- Complete Jupyter notebook (`.ipynb`)
- PNG visualizations
- Executive PDF report (`INFORME_ALURA_CHURN.pdf`)
- README with executive conclusions

## 📈 Key Results

| Metric | Value |
|---|---|
| Model | Random Forest |
| Accuracy | 79% |
| ROC-AUC | 82.5% |
| Top churn driver | Total charges (17.2%) |

## 🧭 Critical Churn Drivers

1. **Total charges — 17.2%**  
   High-spending customers → VIP retention program for premium customers.

2. **Monthly charges — 15.2%**  
   Price sensitivity → pricing optimization for at-risk segments.

3. **Customer tenure — 14.5%**  
   High risk during the first 1–6 months → intensive onboarding program.

## ✅ Strategic Recommendations

- **VIP Program**  
  Focus on customers with total charges above the 80th percentile.  
  Direct impact on the main churn driver.

- **Onboarding (months 1–6)**  
  Reduce early churn and improve the initial customer experience.

- **Monthly Pricing Optimization**  
  Adjust pricing for customers sensitive to monthly charges.

- **Monthly Model Monitoring**  
  Update churn drivers and track model performance over time.

## 📄 Deliverables

- `telecomx_parte2.ipynb` — complete notebook  
- `top10_importance.png` — churn driver analysis  
- `roc_final.png` — executive ROC curve  
- `dashboard_final.png` — final dashboard  
- `INFORME_ALURA_CHURN.pdf` — executive report  
- `README.md` — project documentation  

## 👤 Author

**Nairobi Betancourt**  
Data Science · Customer Retention · Marketing Analytics  
*Oracle ONE — Alura · March 2026*

# 📊 TELECOM X – Parte 2  
## Predicción de Churn · Machine Learning · Drivers Estratégicos

Este proyecto corresponde a la **segunda parte del Challenge Telecom X**, donde el rol evoluciona desde analista hacia **científica de datos**, construyendo un modelo predictivo capaz de anticipar la evasión de clientes y entregar recomendaciones accionables para el negocio.

El objetivo principal es desarrollar un modelo robusto, interpretar los drivers de churn y traducirlos en **acciones estratégicas de retención**.

---

##  1. Objetivos del Proyecto

- Construir un modelo predictivo de churn con métricas sólidas.  
- Identificar los **drivers más influyentes** en la evasión.  
- Generar visualizaciones ejecutivas (ROC, drivers, dashboard).  
- Elaborar un **informe final en PDF** con conclusiones estratégicas.  
- Entregar un notebook claro, reproducible y orientado a negocio.

---

##  2. Flujo de Trabajo

### ✔️ Preparación de Datos
- Carga del dataset tratado en la Parte 1.  
- Limpieza adicional y eliminación de columnas irrelevantes.  
- Codificación de variables categóricas (One-Hot Encoding).  
- División estratificada Train/Test.

### ✔️ Modelado
- Entrenamiento de **Random Forest** como modelo principal.  
- Predicciones y probabilidades de churn.  
- Evaluación con:
  - Accuracy  
  - Precision / Recall / F1  
  - ROC-AUC  
  - Curva ROC técnica y ejecutiva  

### ✔️ Interpretación
- Importancia de variables (%).  
- Identificación de los **Top 3 drivers**.  
- Visualización de impacto.  
- Dashboard final para stakeholders.

### ✔️ Entregables
- Notebook completo (`.ipynb`)  
- Gráficos en PNG  
- Informe PDF (`INFORME_ALURA_CHURN.pdf`)  
- README con conclusiones ejecutivas

---

## 📈 3. Resultados Principales

| Métrica | Valor |
|--------|--------|
| **Accuracy** | **79%** |
| **ROC-AUC** | **82.5%** |
| **Modelo** | Random Forest |
| **Top Driver** | `cargo_total` (17.2%) |

---

##  4. Drivers Críticos de Churn

###  1. `cargo_total` — 17.2%  
Clientes de alto consumo → **Programa VIP** para retención premium.

###  2. `cargo_mensual` — 15.2%  
Sensibilidad al precio → **Optimización de pricing**.

###  3. `meses_cliente` — 14.5%  
Riesgo alto en meses 1–6 → **Onboarding intensivo**.

---

##  5. Recomendaciones Estratégicas

1. **VIP Program**  
   - Foco: clientes con `cargo_total` > percentil 80  
   - Impacto directo en el principal driver de churn  

2. **Onboarding 1–6 meses**  
   - Reduce abandono temprano  
   - Mejora experiencia inicial  

3. **Optimización de Pricing Mensual**  
   - Ajustes para clientes sensibles al cargo mensual  

4. **Monitoreo Mensual del Modelo**  
   - Actualización de drivers  
   - Seguimiento de performance  

---

## 📄 6. Entregables Incluidos

- `telecomx_parte2.ipynb` — Notebook completo  
- `top10_importance.png` — Drivers  
- `roc_final.png` — Curva ROC ejecutiva  
- `dashboard_final.png` — Dashboard final  
- `INFORME_ALURA_CHURN.pdf` — Informe ejecutivo  
- `README.md` — Documentación del proyecto  



👤 Autora
Nairobi Betancourt
Data Science | Oracle ONE – Alura
Marzo 2026
