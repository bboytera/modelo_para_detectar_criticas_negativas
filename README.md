# Modelo_para_detectar_criticas_negativas
Este es un proyecto para la detección de reseñas negativas utilizando diferentes modelos de clasificación
# Introducción
Film Junky Union, una nueva comunidad vanguardista para los aficionados de las películas clásicas, está desarrollando un sistema para filtrar y categorizar reseñas de películas. Nuestro objetivo es entrenar un modelo para detectar las críticas negativas de forma automática. Para lograrlo utilizaremos un conjunto de datos de reseñas de películas de IMDB con leyendas de polaridad para construir un modelo que clasifique las reseñas positivas y negativas. Este deberá alcanzar un valor F1 de al menos 0.85.
# Descripción de los datos
Los datos se almacenan en el archivo imdb_reviews.tsv. 

Los datos fueron proporcionados por Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, y Christopher Potts. (2011). **Learning Word Vectors for Sentiment Analysis**. La Reunión Anual 49 de la Asociación de Lingüística Computacional (ACL 2011).

Aquí se describen los campos seleccionados:

- review: el texto de la reseña
- pos: el objetivo, '0' para negativo y '1' para positivo
- ds_part: 'entrenamiento'/'prueba' para la parte de entrenamiento/prueba del conjunto de datos, respectivamente
# Habilidades técnicas
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Spacy
# Conclusiones
El proyecto se centró en desarrollar un modelo de aprendizaje automático para la detección automática de críticas negativas en reseñas de películas, utilizando un conjunto de datos de IMDB. El objetivo principal era alcanzar un **valor F1 de al menos 0.85**, garantizando una alta precisión y un buen equilibrio entre las tasas de verdaderos positivos y falsos negativos.
## Metología
- Realizamos primeramente un analisis exploratorio de los datos(EDA)
- Normalizamos las reseñas del texto
- Tokenizamos y lematizamos las reseñas con librerias como NLTK Y Spacy y eliminamos las stopwords
- Transformamos las reseñas en vectores TF-IDF para facilitar su procesamiento para los modelos de aprendizaje automatico
- Se entrenaron y compararon varios modelos
- Realizamos una funcion de evaluacion con algunas métricas y las pudimos visualizar
## Evaluación
El proyecto logró sus objetivos principales al desarrollar un modelo robusto para la detección automática de críticas negativas en reseñas de películas. La combinación de técnicas avanzadas de preprocesamiento de texto, modelos de aprendizaje automático optimizados y una cuidadosa evaluación del rendimiento permitió alcanzar **un valor F1 mayor al 0.85.**, en nuestro **Modelo_2 y Modelo_3 un valor F1 de 0.88, en nuestro Modelo_4 un valor F1 de 0.86** de nuestros conjuntos de prueba. Este éxito demuestra el potencial de las técnicas de aprendizaje automático para mejorar la comprensión y gestión de la retroalimentación del cliente en diferentes reseñas de texto como en los ejemplos finales donde podemos medir la probabilidad de ser negativas.

