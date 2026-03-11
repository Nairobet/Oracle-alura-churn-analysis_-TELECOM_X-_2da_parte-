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
