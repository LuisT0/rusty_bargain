# Rusty Bargain: Predicción de Precios de Autos con Machine Learning

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2%2B-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📖 Descripción

Este proyecto fue desarrollado para **Rusty Bargain**, un servicio de venta de autos usados, con el fin de crear una herramienta que estime el valor de mercado de un vehículo de forma rápida y precisa. Se construyó un **modelo de Machine Learning** que, basándose en el historial del vehículo (especificaciones, versión, kilometraje), predice su precio de venta.

El principal desafío es encontrar un equilibrio óptimo entre la **calidad de la predicción**, la **velocidad de inferencia** y el **tiempo de entrenamiento** del modelo.

## ✨ Fases del Proyecto

El Jupyter Notebook documenta todo el proceso, desde la exploración hasta la evaluación del modelo:

*   **Preparación de Datos:** Limpieza de valores nulos, corrección de tipos de datos y manejo de outliers en el dataset `car_data.csv`.
*   **Ingeniería de Características (Feature Engineering):** Aplicación de técnicas de codificación (como One-Hot Encoding) para las variables categóricas (marca, modelo, versión).
*   **Entrenamiento de Modelos:** Se experimentó con diferentes algoritmos de regresión, desde modelos simples como Regresión Lineal hasta ensambles más complejos como LightGBM y CatBoost.
*   **Evaluación Comparativa:** Los modelos fueron evaluados no solo por su precisión, sino también por su eficiencia computacional.

## 🎯 Criterios de Éxito

Para Rusty Bargain, un modelo exitoso debe balancear tres factores clave:

1.  **Calidad de la Predicción:** Minimizar el error (medido con **RMSE**) para dar estimaciones fiables a los clientes.
2.  **Velocidad de Predicción:** El tiempo de inferencia debe ser mínimo para garantizar una experiencia de usuario fluida en la aplicación.
3.  **Tiempo de Entrenamiento:** El modelo debe poder ser re-entrenado eficientemente con nuevos datos sin requerir una infraestructura excesivamente costosa.

## 🛠️ Tecnologías Usadas

<p align="left">
  <a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
  <a href="https://pandas.pydata.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>
  <a href="https://scikit-learn.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1200px-Scikit_learn_logo_small.svg.png" alt="scikit-learn" width="40" height="40"/> </a>
  <a href="https://lightgbm.readthedocs.io/en/latest/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/lightgbm/lightgbm-original.svg" alt="lightgbm" width="40" height="40"/> </a>
  <a href="https://catboost.ai/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/catboost/catboost-original.svg" alt="catboost" width="40" height="40"/> </a>
  <a href="https://jupyter.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original-wordmark.svg" alt="jupyter" width="40" height="40"/> </a>
</p>

## ⚙️ Instalación y Uso

1.  **Clona el repositorio:**
    ```
    git clone https://github.com/TU_USUARIO/RustyBargain.git
    cd RustyBargain
    ```
2.  **Crea y activa un entorno virtual:**
    ```
    python -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    ```
3.  **Instala las dependencias:**
    ```
    pip install -r requirements.txt # Asegúrate de tener este archivo en tu repo
    ```
4.  **Ejecuta Jupyter Notebook:**
    ```
    jupyter notebook
    ```
    Abre `notebooks/Proyecto Sprint 14.ipynb` para ver el análisis completo.

## 📂 Estructura del Repositorio
├── data/
│ └── car_data.csv
├── notebooks/
│ └── Proyecto Sprint 14.ipynb
├── requirements.txt
└── README.md


## 👤 Autor

¡Hablemos de modelos, métricas y cómo resolver problemas de negocio con datos!

*   **GitHub:** [LuisT0](https://github.com/LuisT0)
*   **LinkedIn:** [Luis Antonio Torres Villalobos](https://www.linkedin.com/in/luis-antonio-torres-villalobos/)


