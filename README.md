# DataCo | Predicción del riesgo de entrega tardía

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Big Data](https://img.shields.io/badge/Big_Data-Análisis_de_datos-00695C)
![Estado](https://img.shields.io/badge/Estado-En_desarrollo-yellow)

Proyecto orientado a **predecir el riesgo de entrega tardía** mediante técnicas de Big Data y aprendizaje automático, utilizando el dataset **DataCo Smart Supply Chain**. El objetivo es anticipar posibles incumplimientos y aportar información para mejorar la planificación logística.

## 🎯 Variable objetivo

**`Late_delivery_risk`** permite abordar el problema como una clasificación binaria:

| Valor | Significado |
|:-----:|-------------|
| `0` | Entrega sin retraso |
| `1` | Entrega tardía |

El modelo buscará estimar este riesgo utilizando información disponible antes de la entrega, evitando variables que revelen el resultado, como el tiempo real de envío o el estado final de entrega.

## 🔍 Alcance previsto

- Limpiar y preparar los datos para el análisis.
- Identificar patrones asociados con entregas tardías.
- Entrenar y comparar modelos de clasificación.
- Evaluar su desempeño mediante precisión, recall y F1-score.

## 📂 Contenido

- [`Dataset/`](Dataset/): conjunto de datos y diccionario de variables.
- [`BigData_G2_Propuestas.ipynb`](BigData_G2_Propuestas.ipynb): presentación y justificación del dataset.

## 📊 Fuente de datos

[DataCo Smart Supply Chain — Kaggle](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)
