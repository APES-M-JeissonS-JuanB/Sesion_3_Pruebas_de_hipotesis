# 📊 Aprendizaje Estadístico
# ACTUALIZAR README EN BASE AL NUEVO CASO, ESTÁ IGUAL AL CASO 1
[![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)]()
[![Pandas](https://img.shields.io/badge/Pandas-Análisis%20de%20Datos-150458?style=for-the-badge&logo=pandas&logoColor=white)]()
[![Git](https://img.shields.io/badge/Git-Control%20de%20Versiones-F05032?style=for-the-badge&logo=git&logoColor=white)]()
[![License](https://img.shields.io/badge/Licencia-MIT-black?style=for-the-badge)]()

## Sesión 3: Pruebas de hipótesis


## 📌 Descripción General

Este repositorio contiene el desarrollo del caso de estudio de la Sesión 1, centrado en el **análisis descriptivo de datos** aplicado a un escenario real de negocio: la operación de última milla de una empresa ficticia de entregas, **RutaExpress**.

A partir de un conjunto de datos simulado de 1,500 envíos, se desarrollaron análisis orientados a responder preguntas concretas del negocio, tales como:

- ¿Vale la pena invertir en expandir la flota de drones más allá del piloto actual?
- ¿Qué zona de la ciudad requiere una intervención operativa prioritaria?
- ¿Qué meta de tiempo de entrega (SLA) es razonable comunicar públicamente a los clientes?

El trabajo se desarrolló íntegramente en un **Jupyter Notebook**, combinando código, salidas (numéricas y gráficas) y celdas de interpretación redactadas en lenguaje de negocio.

------------------------------------------------------------------------

## 👨‍💻 Integrantes

- **Juan Daniel Bogotá Fuentes**
- **Jeisson David Sanchez Gomez**

------------------------------------------------------------------------

## 🧠 Estructura del Análisis (Notebook)

### Parte A — Conceptos y tipos de variable
Clasificación de cada variable del dataset (numérica continua/discreta, categórica nominal/ordinal) y análisis del error de interpretación al codificar `nivel_servicio` como número y promediarlo.

### Parte B — Medidas de tendencia central
Cálculo de media, mediana y moda de `tiempo_entrega_min`; definición de un valor de SLA recomendado para comunicación pública; y comparación de la mediana del tiempo de entrega por tipo de vehículo, con recomendación operativa sobre la flota.

### Parte C — Medidas de dispersión
Cálculo de desviación estándar y coeficiente de variación del tiempo de entrega, tanto de forma global como por zona; y análisis del coeficiente de variación del costo de envío por nivel de servicio, evaluando la viabilidad de una tarifa fija garantizada.

### Parte D — Medidas de sesgo y curtosis
Cálculo del sesgo y la curtosis de `tiempo_entrega_min` con `scipy.stats`, interpretando la asimetría positiva de la distribución (cola hacia la derecha) y sus implicaciones para un futuro modelo predictivo, así como para el diseño de una política de compensación por retrasos extremos.

### Parte E — Visualización de datos
Construcción de un histograma de `tiempo_entrega_min` con líneas de media y mediana, relacionando la forma de la distribución con el sesgo calculado; y comparación mediante gráficos de densidad (KDE) del tiempo de entrega entre zonas.

### Parte F — Síntesis y decisión gerencial
Memo ejecutivo dirigido al Director de Operaciones, con recomendaciones sustentadas en las medidas descriptivas calculadas, y reconocimiento de las limitaciones del análisis.

------------------------------------------------------------------------

## 📁 Estructura del Proyecto

    📦 Sesion_1_Aprendizaje_Estadistico_Analisis_Descriptivo
     ├── README.md
     ├── Sanchez_Jeisson_y_Bogota_Juan_CasoEstudio_sesion1.ipynb
     ├── Sesión_1_Aprendizaje_Estadístico_Analisis_Descriptivo.ipynb 
     └── Sesion1_Caso_Estudio_RutaExpress.pdf

### 📖 Contenido

- **Desarrollo del taller** en Jupyter Notebook (Google Colab / VS Code):
  `Sanchez_Jeisson_y_Bogota_Juan_CasoEstudio_sesion1.ipynb`
- **Recurso de la Sesión 1** (introducción al análisis descriptivo):
  `Sesión_1_Aprendizaje_Estadístico_Analisis_Descriptivo.ipynb`
-  **Recurso de la Sesión 1** (introducción al análisis descriptivo):
  `Sesión_1_Aprendizaje_Estadístico_Analisis_Descriptivo.ipynb`


------------------------------------------------------------------------

## 🛠 Tecnologías

- Python
- Pandas / NumPy
- SciPy (sesgo y curtosis)
- Matplotlib / Seaborn (visualización)
- Jupyter Notebook / Google Colab / VS Code
- Git y GitHub

------------------------------------------------------------------------

## 📈 Aprendizajes Obtenidos

A través de este taller se desarrollaron las siguientes competencias:

- Clasificación correcta de variables numéricas y categóricas, y comprensión de los errores comunes al codificar variables ordinales como numéricas.
- Selección crítica de medidas de tendencia central según la presencia de valores atípicos.
- Interpretación del coeficiente de variación como herramienta para comparar la dispersión relativa entre grupos.
- Identificación de sesgo y curtosis en distribuciones reales, y su implicación en la toma de decisiones de negocio.
- Construcción de visualizaciones que respaldan el análisis estadístico.
- Redacción de conclusiones orientadas a un público de negocio, no técnico.
- Trabajo colaborativo mediante Git y GitHub.

------------------------------------------------------------------------

## 👨‍💻 Autores

[![GitHub](https://img.shields.io/badge/GitHub-JeissonS02-181717?style=for-the-badge&logo=github)](https://github.com/JeissonS02)
[![GitHub](https://img.shields.io/badge/GitHub-JuanBogota-181717?style=for-the-badge&logo=github)](https://github.com/JuanBogota)



