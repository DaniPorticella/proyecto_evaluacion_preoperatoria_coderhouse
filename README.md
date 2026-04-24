# Evaluación Preoperatoria — Análisis y Predicción de Riesgo Anestésico

Este repositorio contiene el desarrollo de dos entregas del curso de Data Science (Coderhouse), ambas basadas en un dataset de evaluaciones preoperatorias. 

El objetivo general es caracterizar y predecir el riesgo anestésico de los pacientes a partir de variables clínicas relevantes: clasificación ASA, edad, sexo, capacidad funcional, comorbilidades y tipo de cirugía.

## 📁 Estructura del repositorio

- `AnestData_EvalPreop.v3supabase.csv`  
  Dataset utilizado para el análisis, correspondiente a evaluaciones preoperatorias realizadas en un único centro asistencial.

- `Porticella_EvaluacionPreoperatoria_Coderhouse.ipynb`  
  Notebook en Python con el análisis exploratorio de datos y visualizaciones.

- `Porticella_EvaluacionPreoperatoria_ML_Coderhouse.ipynb`
  Entrega 2 — Entrenamiento y optimización de modelos de Machine Learning para predecir riesgo anestésico elevado (ASA III–IV). Incluye ingeniería de atributos, validación cruzada, GridSearchCV y simulación clínica con casos ficticios.
 
- `README.md`  
  Descripción general del proyecto.

## 🧪 Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 📊 Alcance del análisis

El análisis está orientado a:
- Coordinación de quirófano y jefatura de anestesiología  
- Equipos de anestesia y cirugía (planificación de recursos)  
- Gestión hospitalaria y análisis de riesgo preoperatorio  

El dataset fue anonimizado y contiene datos sintéticos generados con fines académicos. Los resultados no deben extrapolarse a la práctica.

## ▶️ Reproducibilidad

El notebook carga el dataset directamente desde el repositorio de GitHub mediante una URL *raw*, lo que permite ejecutar el análisis sin necesidad de subir archivos manualmente.

