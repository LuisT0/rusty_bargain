# Rusty Bargain: Predicción del Valor de Mercado de Autos Usados

## Descripción del proyecto

Rusty Bargain, servicio de venta de autos usados, está desarrollando una aplicación para atraer nuevos clientes. La app permite estimar rápidamente el valor de mercado de un vehículo a partir de su historial: especificaciones técnicas, versiones de equipamiento y precios históricos. El objetivo es construir un modelo de machine learning que determine el precio de mercado de forma precisa, eficiente y rápida.

## Estructura del repositorio

```
├── data/                       # Carpeta con el dataset de autos usados
│   └── car_data.csv            # Historial de autos (especificaciones y precios)
├── notebooks/                  # Carpeta con el notebook de Jupyter
│   └── Proyecto Sprint 14.ipynb # Notebook con EDA, modelado y evaluación
├── .gitignore                  # Ignorar archivos innecesarios (p.ej. .DS_Store)
└── README.md                   # Este documento
```

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/TU_USUARIO/RustyBargain.git
   cd RustyBargain
   ```
2. Crea y activa un entorno virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate    # Windows: venv\\Scripts\\activate
   ```

## Uso

Dentro del notebook encontrarás:

- **Preparación de datos**: limpieza y transformación de variables.
- **Ingeniería de características**: codificación de versiones de equipamiento.
- **Modelado**: entrenamiento y validación de modelos de regresión.
- **Evaluación**: métricas de calidad (RMSE/MAE), velocidad de predicción y tiempo de entrenamiento.

## Objetivos de evaluación

Rusty Bargain valora en el modelo final:

1. **Calidad de la predicción**: RMSE o MAE lo más bajo posible.
2. **Velocidad de inferencia**: tiempo medio de predicción por muestra.
3. **Tiempo de entrenamiento**: duración total del entrenamiento dentro de un límite razonable.

## Datos

El dataset `car_data.csv` contiene columnas como:

| Columna   | Descripción                             |
| --------- | --------------------------------------- |
| `make`    | Marca del vehículo (p.ej. Toyota, Ford) |
| `model`   | Modelo específico (p.ej. Camry, Fiesta) |
| `year`    | Año de fabricación                      |
| `mileage` | Kilometraje (km)                        |
| `version` | Nivel de equipamiento                   |
| `price`   | Precio de venta (variable objetivo)     |

*(Ajusta o amplía los detalles según tu dataset.)*

## Contribuciones

¡Bienvenidas! Si deseas mejorar este proyecto, abre un issue o envía un pull request con sugerencias en análisis, modelos o documentación.

## Licencia

Este proyecto se distribuye bajo la Licencia MIT.

