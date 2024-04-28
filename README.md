# Predictor de Precio de Coches

## Descripción
Este proyecto implementa un modelo de Machine Learning que utiliza datos históricos de vehículos de segunda mano para predecir sus precios de venta basándose en características como la marca, el modelo, el año, la potencia, y otros atributos relevantes.

## Características del Proyecto
- **Análisis exploratorio de datos:** Visualización y estadísticas descriptivas para entender las tendencias y características de los datos.
- **Preprocesamiento de datos:** Limpieza y transformación de datos para prepararlos para el modelado.
- **Modelado:** Desarrollo y entrenamiento de modelos predictivos usando algoritmos como regresión lineal, árboles de decisión, entre otros.
- **Evaluación del modelo:** Métodos para verificar la precisión y eficacia del modelo predictivo.
- **Visualización de resultados:** Gráficos y tablas para mostrar los resultados y las predicciones del modelo.

## Estructura del Repositorio
- `The_final_countdown.ipynb`: Jupyter Notebook que contiene todo el código y análisis.
- `audi.csv`, `bmw.csv`, `ford.csv`, etc.: Conjuntos de datos utilizados para el entrenamiento del modelo.

## Cómo Empezar

1. **Clona este repositorio:**
  ```bash
    git clone https://github.com/joferte84/Predictor_precio_coche.git
  ```
2. **Instala las dependencias utilizando el archivo `requirements.txt`:**
  ```bash
    pip install -r requirements.txt
  ```
3. ** Abre y ejecuta el notebook `The_final_countdown.ipynb` para ver el flujo de trabajo y las predicciones.**

## Aviso Importante
En este entorno de Jupyter, la ejecución de este documento genera un total de 14 archivos (pickles). Para garantizar un manejo adecuado, se recomienda mantener esta carpeta en un directorio que no cause inconvenientes.

### Nota Adicional
Los Grid Search incluidos en este documento están completamente funcionales, pero han sido comentados por razones de eficacia en el tiempo de ejecución. Los valores óptimos obtenidos a través de estos Grid Search se encuentran reflejados en la optimización posterior.
