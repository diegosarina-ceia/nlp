<div align="center">

# Procesamiento del Lenguaje Natural

![UBA](image.png)

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-2024-purple)
![NLP](https://img.shields.io/badge/NLP-Advanced-green)
</div>



## 🎯 Descripción General

Bienvenido al repositorio de resoluciones para la materia de Procesamiento del Lenguaje Natural del LSE-FIUBA. 

Este repositorio contiene los diferentes entregables que se desarrollaron como parte de **Desafíos** de la asignatura NLP perteneciente a la Especialización en IA de la UBA (Universidad Nacional de Buenos Aires).

## 📚 Desafíos Implementados

### 1️⃣ Desafío Nº 1: Vectorización de texto
En este desafío, se implementa el algoritmo Word2Vec para aprender representaciones vectoriales densas de palabras a partir de grandes corpus de texto. Estas representaciones permiten capturar similitudes semánticas y relaciones entre palabras dentro de un espacio vectorial, facilitando el análisis de conexiones y patrones entre términos.

📂 [Ver implementación](DESAFIO_1/Desafio_1.ipynb)

### 2️⃣ Desafío Nº 2: Custom Embeddings con Gensim
En este desafío, se utiliza la biblioteca Gensim para generar embeddings de palabras a partir de un corpus de texto. Se exploran técnicas como Skip-Gram y CBOW, aplicando los embeddings a tareas como búsqueda de palabras similares, análisis de analogías, y otras tareas de procesamiento del lenguaje natural.

📂 [Ver implementación](DESAFIO_2/Desafio_2.ipynb)

### 3️⃣ Desafío Nº 3: Modelo de lenguaje con tokenización
Implementación dual de modelos de lenguaje:
- **Enfoque por palabras**: [Ver notebook](Desafio3/Desafio_3_word.ipynb)
- **Enfoque por caracteres**: [Ver notebook](Desafio3/Desafio_3_char.ipynb)

Características principales:
- Arquitecturas RNN, LSTM y GRU
- Experimentación con beam search y temperature sampling
- Análisis comparativo de estrategias de tokenización

📂 [Ver implementación](DESAFIO_3/)

### 4️⃣ Desafío Nº 4: LSTM Bot QA
En este desafío, se desarrolla un bot de preguntas y respuestas (QA) utilizando un modelo encoder-decoder basado en LSTM. El bot es capaz de generar respuestas coherentes a preguntas simples en inglés. Para mejorar la representación semántica de las palabras, se utilizan embeddings de FastText. A lo largo del entrenamiento, se emplean técnicas de regularización como dropout para mitigar el sobreajuste, logrando un buen equilibrio entre calidad de las respuestas y generalización del modelo.

📂 [Ver implementación](DESAFIO_4/DESAFIO_4.ipynb)

### 5️⃣ Desafío Nº 5: Análisis de Sentimientos con BERT
Este desafío explora el poder del análisis de sentimiento utilizando BERT para procesar y comprender reseñas de aplicaciones. El proyecto se divide en dos aproximaciones principales:

- Modelo Base: Implementación clásica de clasificación tripartita (positivo/negativo/neutral) aprovechando la capacidad de BERT para entender el contexto bidireccional del texto.
- Modelo Extendido: Refinamiento que preserva las 5 categorías originales del dataset, permitiendo una granularidad más fina en la detección de sentimientos.

La arquitectura transformer de BERT, combinada con fine-tuning específico para nuestro dominio, permite capturar sutilezas lingüísticas y contextuales que son cruciales para entender el verdadero sentimiento detrás de cada reseña.

📂 [Ver implementación](DESAFIO_5/DESAFIO_5.ipynb)

## 📝 Notas
- Todas las notebooks fueron desarrolladas y probadas en Google Colab
- Se recomienda revisar cada notebook para requisitos específicos

---
<div align="center">
<i>Facultad de Ingeniería - Universidad de Buenos Aires</i>
</div>