# 💬 ¿Positiva o negativa? Clasificación de opiniones con NLP y Transformers

![Python](https://img.shields.io/badge/Python-3.10-yellow?style=for-the-badge&logo=python)
![NLP](https://img.shields.io/badge/NLP-Procesamiento%20del%20Lenguaje%20Natural-blue?style=for-the-badge)
![Transformers](https://img.shields.io/badge/Transformers-HuggingFace-purple?style=for-the-badge)
![Estado](https://img.shields.io/badge/Estado-Completado-brightgreen?style=for-the-badge)

---

## 📌 Situación (Problema de negocio)

En plataformas digitales como Netflix, Amazon o IMDb, millones de usuarios generan reseñas de forma constante.

Analizar manualmente este volumen de opiniones no es viable, lo que genera problemas como:

- Dificultad para identificar rápidamente la percepción del usuario  
- Imposibilidad de escalar el análisis de feedback  
- Falta de sistemas automáticos de clasificación de sentimiento  
- Retrasos en la toma de decisiones basadas en opinión del cliente  

Esto impacta directamente en la experiencia de usuario y en la toma de decisiones de producto y negocio.

---

## 🎯 Tarea (Objetivo del proyecto)

Desarrollar un modelo de **Machine Learning supervisado** capaz de:

- Clasificar automáticamente reseñas de películas y series como **positivas o negativas**  
- Transformar texto no estructurado en una señal cuantificable de sentimiento  
- Permitir análisis escalable del feedback de usuarios  
- Servir como base para sistemas de análisis de opinión en plataformas digitales  

---

## ⚙️ Acción (Solución implementada)

Se diseñó un pipeline completo de NLP utilizando Python y modelos modernos de Deep Learning:

### 🔹 Procesamiento del texto
- Limpieza y normalización de reseñas  
- Tokenización y lematización  
- Preparación del corpus para modelado  

### 🔹 Representación del lenguaje
- Bag of Words  
- TF-IDF  
- Word Embeddings  

### 🔹 Modelos implementados
- Modelos clásicos: Naive Bayes, SVM, Regresión Logística  
- Modelos deep learning: RNN, LSTM  
- Fine-tuning de modelos Transformer (Hugging Face, BERT-like models)  

### 🔹 Evaluación
- Accuracy  
- Precision / Recall / F1-score  
- Análisis de errores de clasificación  

---

## 📊 Resultado

El sistema desarrollado permite:

- Clasificar automáticamente reseñas con alta precisión  
- Escalar el análisis de opiniones sin intervención manual  
- Transformar texto no estructurado en insights accionables  
- Servir como base para sistemas de sentiment analysis en producción  

---

## 🛠️ Tecnologías utilizadas

- Python (Pandas, NumPy)  
- Scikit-learn  
- NLTK / SpaCy  
- PyTorch / TensorFlow  
- Hugging Face Transformers  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 🚀 Uso del repositorio

1. Clonar el repositorio  
2. Instalar dependencias necesarias  
3. Ejecutar notebooks de preprocesamiento de texto  
4. Entrenar modelos clásicos o Transformers  
5. Evaluar resultados con métricas de clasificación    

