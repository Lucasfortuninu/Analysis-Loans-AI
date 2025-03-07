# Análisis de Elegibilidad para Préstamos con Aprendizaje Automático

## 📌 Descripción
Este repositorio contiene un análisis de elegibilidad para préstamos basado en **aprendizaje automático**. El objetivo es predecir si un solicitante es apto para recibir un préstamo en función de diversos atributos financieros y personales.

Este proyecto fue desarrollado como trabajo final de la asignatura de Aprendizaje Automatico en el tercer curso del grado de Ingeniería Informática en la Universidad Pública de Navarra (UPNA).

## 🏆 Objetivos del Proyecto
- Evaluar la **elegibilidad de un solicitante** para recibir un préstamo.
- Aplicar técnicas de **preprocesamiento de datos** para mejorar la calidad del dataset.
- Entrenar y comparar diferentes **modelos de clasificación**.
- Evaluar la **interpretabilidad** del modelo seleccionado.

## 🚀 Tecnologías Utilizadas
- **Python** 🐍
- **Pandas y NumPy** para manipulación de datos.
- **Scikit-learn** para modelado y evaluación.
- **Matplotlib y Seaborn** para visualización de datos.
- **Jupyter Notebook** para el desarrollo del análisis.

## 📂 Contenido del Proyecto
1. **Elección del dataset y motivación**.
2. **Exploración y tratamiento del dataset**.
3. **División de datos en entrenamiento y prueba**.
4. **Comparación de diferentes modelos de clasificación**.
5. **Explicabilidad del modelo seleccionado**.
6. **Conclusiones y mejoras futuras**.

## 📊 Modelos Evaluados
Se compararon diferentes modelos de clasificación, incluyendo:
- **Regresión Logística**
- **Naive Bayes**
- **Redes Neuronales**
- **Arboles de Decisión**
- **Random Forest**
- **Ensemble Methods (Bagging, Boosting)**

El modelo con mejor rendimiento fue **Árboles de Decisión**, con una precisión del **98.47% en el conjunto de prueba**.

## 🔍 Explicabilidad del Modelo
- Se identificó que la **puntuación CIBIL** es la característica más influyente en la predicción.
- La **duración del préstamo** también juega un papel clave.
- Se recomienda balancear las clases para mejorar la equidad del modelo.
