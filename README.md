# proyecto-prediccion-fotovoltaica
Modelo de predicción de energía generada por una planta fotovoltaica basado en datos meteorológicos

# 📡 Proyecto de Predicción Fotovoltaica  
Este proyecto desarrolla un modelo de Machine Learning para predecir la energía generada por una planta fotovoltaica en función de la previsión meteorológica.  

## 📌 Objetivos  
- Extraer datos históricos de producción y clima.  
- Limpiar y transformar los datos para entrenamiento.  
- Comparar modelos (Random Forest, Redes Neuronales, etc.).  
- Evaluar el mejor modelo con métricas.  
- Implementar un sistema de predicción en tiempo real.  

## 🚀 Tecnologías utilizadas  
- **Lenguaje:** Python  
- **Bases de Datos:** PostgreSQL / MongoDB  
- **Machine Learning:** Scikit-learn, TensorFlow  
- **API Meteorológica:** OpenWeatherMap (o similar)  
- **Colaboración:** GitHub

  ## 📂 Estructura del Proyecto
  proyecto-prediccion-fotovoltaica/
│── data/                   # 📂 Datos sin procesar y procesados
│   ├── raw/                # 📂 Datos originales (históricos, API)
│   ├── processed/          # 📂 Datos limpios y transformados
│── notebooks/              # 📂 Jupyter Notebooks para análisis
│   ├── 01-exploracion.ipynb
│   ├── 02-limpieza.ipynb
│   ├── 03-entrenamiento.ipynb
│── src/                    # 📂 Código fuente del proyecto
│   ├── data_ingestion.py   # 📄 Extracción de datos de la API
│   ├── preprocessing.py    # 📄 Limpieza y transformación de datos
│   ├── model.py            # 📄 Entrenamiento de modelos
│   ├── predict.py          # 📄 Predicción con el modelo entrenado
│── models/                 # 📂 Modelos entrenados guardados
│── docs/                   # 📂 Documentación del proyecto
│── tests/                  # 📂 Pruebas unitarias
│── requirements.txt        # 📄 Librerías necesarias
│── .gitignore              # 📄 Archivos a ignorar en Git
│── README.md               # 📄 Descripción del proyecto

