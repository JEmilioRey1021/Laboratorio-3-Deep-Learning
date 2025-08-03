# Laboratorio 3 - Deep Learning


**Universidad del Valle de Guatemala**

**Curso:** CC3084 - Data Science

**Semestre II - 2025**

## Descripción

Este proyecto forma parte del Laboratorio 3 del curso de Data Science, cuyo objetivo principal es entrenar y evaluar modelos de Deep Learning para el reconocimiento de dígitos manuscritos utilizando el dataset [PolyMNIST](https://www.kaggle.com/datasets/agungpambudi/mnist-multiple-dataset-comprehensive-analysis/data). Se trabaja con cinco modalidades de datos, cada una con características visuales distintas, lo cual permite poner a prueba la capacidad de generalización de los modelos.

---

## Contenido del laboratorio

1. **Análisis Exploratorio**
   - Distribución de etiquetas por modalidad
   - Comparación entre conjuntos de entrenamiento y prueba
   - Visualización de intensidad promedio por clase

2. **Preprocesamiento de Datos**
   - Conversión a escala de grises
   - Normalización de pixeles
   - Estandarización de tamaño de entrada

3. **Modelos de Deep Learning**
   - Dos modelos convolucionales (CNN) con comparación de resultados
   - Modelo de red neuronal simple (fully connected)
   - Modelo con otro algoritmo de aprendizaje automático

4. **Aumento de datos (Data Augmentation)**
   - Técnicas como rotación, traslación y escalado
   - Comparación de resultados antes y después del aumento

5. **Evaluación con dígitos manuscritos**
   - Se probaron imágenes dibujadas por los integrantes del grupo
   - Se discute la capacidad de generalización del modelo seleccionado

---

## Requisitos

- Python 3.8+
- NumPy
- pandas
- matplotlib
- seaborn
- scikit-learn
- TensorFlow o PyTorch
- PIL (Pillow)

---

## Ejecución

```bash
# Entrenar modelo principal y ver análisis exploratorio
jupyter notebook Modelo1CNN.ipynb
```

---

## Autores

* Silvia Illescas
* Emilio Reyes
* Michelle Mejía

