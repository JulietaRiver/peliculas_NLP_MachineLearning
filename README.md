# peliculas_NLP_MachineLearning

🎬 Clasificador de Reseñas de Películas IMDb
Proyecto de clasificación de texto con NLP y modelos de Machine Learning para detectar automáticamente reseñas negativas de películas.

📌 Descripción
Film Junky Union, una comunidad para amantes del cine clásico, desea automatizar la detección de reseñas negativas en su plataforma. En este proyecto se entrena un modelo de clasificación binaria que, a partir de una reseña de IMDb, predice si es positiva o negativa. El objetivo es alcanzar un puntaje F1 ≥ 0.85.

🧠 Objetivo
Construir un modelo robusto de clasificación de texto que permita detectar críticas negativas de forma automática, optimizando métricas de evaluación como el F1-score.

🗂️ Dataset
Se utiliza un conjunto de datos con reseñas de películas y etiquetas de polaridad (positive / negative).
🔗 Fuente: IMDb (formato .tsv).

🛠️ Herramientas y Tecnologías
Python (Pandas, NumPy)

NLP: nltk, spacy, TfidfVectorizer

Modelos: LogisticRegression, LGBMClassifier, DummyClassifier

Visualización: matplotlib, seaborn

Métricas: sklearn.metrics

Transformers: transformers de Hugging Face (si se utiliza en etapas avanzadas)

🔍 Pasos del Proyecto
Exploración y limpieza de datos

Tokenización, lematización y eliminación de stopwords

Vectorización del texto (TF-IDF)

Entrenamiento de modelos base y avanzados

Evaluación de rendimiento con F1-score

Visualización de resultados

📊 Resultados
El mejor modelo alcanzó un F1-score ≥ 0.85, cumpliendo con el objetivo del negocio.

Se compararon distintos clasificadores y técnicas de preprocesamiento.

▶️ Cómo ejecutar

# Clonar repositorio
git clone https://github.com/tu_usuario/nombre_repositorio.git
cd nombre_repositorio

# Abrir el notebook
jupyter notebook f09626b4-68d9-4833-b1c3-94943b274bf0.ipynb
Se recomienda crear un entorno virtual e instalar las dependencias necesarias listadas en requirements.txt.

📸 Visualizaciones
Aquí podrías incluir imágenes como gráficos de métricas, matriz de confusión, etc.
