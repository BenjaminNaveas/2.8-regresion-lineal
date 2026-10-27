# 📈 Actividad 2.8: Laboratorio - Implementación de Regresión Lineal

**Asignatura:** IEI097 · Minería de Datos  
**Institución:** Instituto Profesional Santo Tomás - Sede Arica  
**Estudiante:** Benjamín Eduardo Naveas Molina  

## 📋 Descripción del Proyecto
Este directorio contiene el desarrollo práctico del laboratorio de Regresión Lineal. El objetivo principal es entrenar modelos predictivos continuos, evaluar su error real (R², MAE, RMSE) y fundamentar la validez de los resultados detectando problemas estadísticos críticos que pueden invalidar un modelo en producción.

El trabajo está estructurado en dos cuadernos ejecutables de Google Colab que abordan tres fases analíticas:

### 📓 Cuaderno 1: Regresión Simple y Múltiple
* **Bloque 1 (Regresión Simple):** Análisis del dataset *Breast Cancer Wisconsin*. Evaluación comparativa de predictores (Radio vs Perímetro/Área) y comprobación del supuesto de linealidad mediante análisis visual de residuos.
* **Bloque 2 (Regresión Múltiple):** Análisis del dataset *FIFA 19*. Proceso de selección de variables y limpieza de **Data Leakage** (fuga de datos). Validación de **Multicolinealidad** mediante el cálculo del factor VIF y demostración empírica de **Heterogeneidad** poblacional al segmentar el error predictivo entre jugadores de campo y porteros.

### 📓 Cuaderno 2: Transferencia a Dataset Propio
* **Bloque 3 (Diabetes Prediction Dataset):** Aplicación del flujo de trabajo completo a un dataset clínico personal. Entrenamiento de un modelo de regresión lineal múltiple para predecir el Índice de Masa Corporal (BMI), analizando la estabilidad del error (Train vs Test) y documentando la heterogeneidad y los supuestos estadísticos incumplidos por la naturaleza atípica de los datos médicos.

## 🛠️ Tecnologías Utilizadas
* **Entorno:** Google Colab (Python 3)
* **Modelado y Métricas:** `scikit-learn` (LinearRegression, r2_score, mean_squared_error, mean_absolute_error)
* **Validación Estadística:** `statsmodels` (variance_inflation_factor)
* **Manipulación y Visualización:** `pandas`, `numpy`, `matplotlib`, `seaborn`
* **Conexión de Datos:** `kagglehub` (mediante Colab Secrets)

## 🚀 Ejecución en Colab
Puedes revisar y ejecutar los cuadernos directamente en Google Colab haciendo clic en los siguientes enlaces:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](ENLACE_A_TU_CUADERNO_1_AQUI) **Bloques 1 y 2 (Breast Cancer & FIFA 19)**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](ENLACE_A_TU_CUADERNO_2_AQUI) **Bloque 3 (Diabetes Prediction)**

*(Nota: Reemplaza "ENLACE_A_TU_CUADERNO_X_AQUI" con los enlaces reales de tus cuadernos compartidos).*

---
*Este proyecto fue desarrollado como parte de las evaluaciones prácticas de la Unidad II de la asignatura Minería de Datos.*
