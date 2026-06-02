## CLASIFICACION CON REDES NEURONALES
Este proyecto consiste en el desarrollo de un modelo de Inteligencia Artificial para predecir la presencia de enfermedad cardíaca 
utilizando una Red Neuronal Artificial tipo MLP (Multi-Layer Perceptron). Para ello se empleó el dataset Heart Disease, realizando 
análisis exploratorio de datos, entrenamiento, evaluación e inferencia del modelo.

## Objetivo
Construir un modelo capaz de clasificar si un paciente presenta o no una enfermedad cardíaca a partir de diferentes variables clínicas.

## Herramientas Utilizadas
Python
Pandas
NumPy
Matplotlib
Scikit-Learn
Joblib

## Archivos del Proyecto

- `heart_disease_eda.py` → Análisis exploratorio de datos.
- `mlp_training.py` → Entrenamiento y evaluación del modelo.
- `mlp_inference.py` → Carga del modelo y predicciones.
- `models/mlp_heart_model.pkl` → Modelo entrenado.
- `models/scaler.pkl` → Escalador utilizado para normalización.
- `data/heart.csv` → Dataset utilizado.

## Ejecución

### 1. Análisis Exploratorio

```bash
python heart_disease_eda.py
