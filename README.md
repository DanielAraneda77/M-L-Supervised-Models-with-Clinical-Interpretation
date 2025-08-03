# Diabetes-Predictor: Modelos Supervisados con Interpretación Clínica

## Objetivo del proyecto

Este proyecto aplica modelos de clasificación supervisada para predecir la presencia de diabetes en pacientes, utilizando atributos clínicos básicos como glucosa, IMC y presión arterial. A partir de un dataset real con moderado desbalance de clases, se desarrolla un flujo completo de análisis técnico e interpretativo que busca no solo precisión, sino también utilidad diagnóstica en contextos reales.

El enfoque prioriza la reproducibilidad, la optimización computacional y la narrativa visual clara, orientada tanto a públicos técnicos como no técnicos (como personal clínico y tomadores de decisión).

---

## Dataset

- **Fuente:** [Pima Indians Diabetes Dataset – Kaggle / UCI]([https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)](https://www.kaggle.com/datasets/mathchi/diabetes-data-set
- **Registros:** 768 observaciones, 8 atributos clínicos por paciente
- **Variable objetivo:** `Outcome` (presencia o ausencia de diabetes)

---

## Tecnologías y herramientas

- Python (`pandas`, `numpy`, `scikit-learn`)
- `train_test_split` (separación en entrenamiento y prueba)
- `RandomForestClassifier`, `XGBoost`(modelos supervisados)
- `classification_report`, `accuracy_score`, `precision_score`, `recall_score`, `f1_score`, `confusion_matrix`, `roc_auc_score`, `roc_curve` (métricas de evaluación)
- `Matplotlib`, `Seaborn`(visualización técnica e interpretativa)
- Jupyter Notebook / Google Colab (presentación interactiva)
  
---

## Hallazgos clave

- Los modelos muestran variaciones significativas en precisión y recall, especialmente al detectar la clase minoritaria
- El tratamiento de valores clínicos inválidos impacta fuertemente en la estabilidad del modelo
- Las visualizaciones ayudan a comunicar resultados complejos de forma accesible para personal no técnico

---

## 👤 Conéctate conmigo

[![Conectar en LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-blue?logo=linkedin&style=flat-square)](https://www.linkedin.com/in/daniel-araneda-yasic)

¿Eres reclutador o profesional del sector interesado en proyectos aplicados de Data Science, visualización de datos o inteligencia artificial eficiente?  
Este proyecto refleja mi enfoque técnico y comunicativo, y estoy abierto a oportunidades laborales, colaboración en equipos multidisciplinarios y desarrollo de soluciones prácticas y reproducibles.

📫 No dudes en contactarme para conversar sobre cómo puedo aportar valor desde la intersección entre análisis técnico, creatividad visual y documentación didáctica.

