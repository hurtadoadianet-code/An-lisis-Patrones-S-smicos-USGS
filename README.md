# Analisis-Patrones-Sismicos-USGS
Proyecto de análisis de datos sísmicos basado en registros del USGS. Incluye exploración, limpieza de datos, preprocesamiento, reducción de dimensionalidad mediante PCA y segmentación con K-Means. El objetivo es identificar patrones en la actividad sísmica global y caracterizar terremotos según magnitud, profundidad y ubicación geográfica.

# 🌎 Análisis de Patrones Sísmicos mediante PCA y K-Means

## Descripción del Proyecto

Este proyecto desarrolla un análisis exploratorio y de aprendizaje no supervisado sobre datos de terremotos obtenidos del Servicio Geológico de los Estados Unidos (USGS). El conjunto de datos contiene información detallada de eventos sísmicos registrados durante los últimos 30 días, incluyendo magnitud, profundidad, ubicación geográfica y otras características relevantes.

El objetivo principal es identificar patrones ocultos en la actividad sísmica mundial mediante técnicas de reducción de dimensionalidad y clustering, permitiendo segmentar los eventos sísmicos en grupos homogéneos y explorar posibles comportamientos asociados a diferentes contextos tectónicos.

## Fuente de Datos

**Dataset:** Earthquake Dataset (USGS)

**Fuente:** Servicio Geológico de los Estados Unidos (USGS)

**Kaggle:** https://www.kaggle.com/datasets/farazrahman/earthquake


## Objetivos

* Realizar un Análisis Exploratorio de Datos (EDA).
* Identificar y tratar valores faltantes.
* Preparar los datos mediante codificación y escalamiento.
* Reducir la dimensionalidad utilizando Análisis de Componentes Principales (PCA).
* Aplicar algoritmos de clustering mediante K-Means.
* Identificar grupos de terremotos con características similares.
* Analizar patrones asociados a la magnitud, profundidad y ubicación geográfica de los eventos sísmicos.


## Metodología

### 1. Exploración y limpieza de datos

* Carga del dataset.
* Inspección de variables.
* Detección de valores faltantes.
* Validación de tipos de datos.

### 2. Análisis Exploratorio de Datos (EDA)

* Estadísticas descriptivas.
* Distribuciones de variables.
* Matriz de correlaciones.
* Visualizaciones geoespaciales.
* Identificación de patrones preliminares.

### 3. Preprocesamiento

* Tratamiento de valores faltantes.
* Codificación de variables categóricas.
* Estandarización de variables numéricas.

### 4. Reducción de Dimensionalidad

Se utilizó el método de Análisis de Componentes Principales (PCA) para:

* Reducir la complejidad de los datos.
* Eliminar redundancias.
* Facilitar la visualización de los clusters.

### 5. Modelado de Clustering

Se implementó el algoritmo K-Means para:

* Agrupar terremotos según características similares.
* Detectar estructuras latentes en los datos.
* Caracterizar diferentes patrones de actividad sísmica.

### 6. Evaluación de Resultados

* Método del Codo (Elbow Method).
* Visualización de clusters.
* Interpretación geológica y estadística de los grupos encontrados.

---

## Tecnologías Utilizadas

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Resultados Principales

El análisis permitió identificar distintos grupos de eventos sísmicos diferenciados por:

* Magnitud.
* Profundidad.
* Localización geográfica.
* Características energéticas.

Los resultados sugieren la existencia de patrones sísmicos diferenciados que podrían estar relacionados con diversos entornos tectónicos alrededor del mundo.

