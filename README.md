# DeepLearning-Binary-Classification

# Cétien - Módulo de Clasificación de Imágenes (Dogs vs Cats) 🐾

Este repositorio contiene un modelo de **Deep Learning** enfocado en la visión artificial para la clasificación binaria de imágenes. Fue desarrollado como parte de la integración de inteligencia artificial para el ecosistema **Cétien**.

## 🚀 Descripción del Proyecto
El sistema utiliza una **Red Neuronal Convolucional (CNN)** construida con TensorFlow y Keras. Es capaz de procesar imágenes, identificar patrones visuales y determinar con un alto grado de probabilidad si el sujeto en la imagen es un perro o un gato.

### Características principales:
* **Procesamiento de imágenes:** Uso de OpenCV para normalización y redimensionamiento.
* **Arquitectura CNN:** Tres capas de convolución y pooling para extracción de características.
* **Validación Automática:** Separación de datos (80/20) para asegurar la precisión del modelo.
* **Interfaz Visual:** (Opcional) Integración con el dashboard de Cétien para visualización de resultados.

## 🛠️ Tecnologías Utilizadas
* **Python 3.x**
* **TensorFlow / Keras** (Entrenamiento del modelo)
* **OpenCV** (Preprocesamiento de imágenes)
* **Matplotlib & Numpy** (Visualización y manejo de datos)
* **Google Colab** (Entorno de ejecución)

## 📁 Estructura del Dataset
El modelo espera una estructura de carpetas dentro de un archivo `dataset1.zip`:
```text
dataset1/
├── Cats/
│   ├── cat1.jpg
│   └── ...
└── Dogs/
    ├── dog1.jpg
    └── ...
