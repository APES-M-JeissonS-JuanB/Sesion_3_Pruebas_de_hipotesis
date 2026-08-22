# 📊 Aprendizaje Estadístico

[![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)]()
[![Pandas](https://img.shields.io/badge/Pandas-Análisis%20de%20Datos-150458?style=for-the-badge&logo=pandas&logoColor=white)]()
[![SciPy](https://img.shields.io/badge/SciPy-Pruebas%20de%20Hipótesis-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)]()
[![Git](https://img.shields.io/badge/Git-Control%20de%20Versiones-F05032?style=for-the-badge&logo=git&logoColor=white)]()
[![License](https://img.shields.io/badge/Licencia-MIT-black?style=for-the-badge)]()

## Sesión 3: Pruebas de hipótesis

## 📌 Descripción General

Este repositorio contiene el desarrollo del caso de estudio de la Sesión 3, centrado en **pruebas de hipótesis** aplicadas a un escenario real de negocio: la decisión de escalar a nivel nacional el programa piloto **"Consulta Prioritaria Vitalcol" (CPV)** de **Vitalcol EPS**, una entidad promotora de salud ficticia que opera en Bogotá, Medellín, Cali y Barranquilla.

A partir de tres conjuntos de datos simulados, se desarrollaron análisis estadísticos rigurosos orientados a responder preguntas concretas de distintas áreas de la organización, tales como:

- ¿El programa CPV incrementó el costo promedio por consulta prioritaria frente a las clínicas control?
- ¿Alguna de las tres modalidades de triage digital evaluadas reduce el tiempo de atención y las complicaciones evitables frente a las demás?
- ¿El programa de capacitación en triage digital mejoró el desempeño del personal de enfermería, lo suficiente como para hacerlo obligatorio a nivel nacional?

El trabajo se desarrolló íntegramente en un **Jupyter Notebook**, combinando código, salidas (numéricas y gráficas) y celdas de interpretación redactadas en lenguaje de negocio, siguiendo en cada ejercicio el procedimiento de 5 pasos de una prueba de hipótesis: planteamiento, formulación de H₀/H₁, selección de la prueba, análisis exploratorio, ejecución, y conclusión de negocio.

------------------------------------------------------------------------

## 👨‍💻 Integrantes

- **Juan Daniel Bogotá Fuentes**
- **Jeisson David Sanchez Gomez**

------------------------------------------------------------------------

## 🧠 Estructura del Análisis (Notebook)

### Ejercicio 1 — Costos operativos del programa CPV
Comparación del costo promedio por consulta prioritaria entre clínicas piloto (con CPV) y clínicas control (sin CPV), mediante una prueba t de dos muestras independientes (dos colas). Se evalúa si una eventual diferencia es no solo estadísticamente significativa, sino también relevante en términos financieros para el Comité Financiero.

### Ejercicio 2 — Comparación de modalidades de triage digital
Evaluación de tres modalidades de triage digital (síntomas auto-reportados, + signos vitales, + priorización por IA) desde dos ángulos independientes:
- **Parte A:** comparación del tiempo hasta la primera atención entre las tres modalidades mediante ANOVA de un factor.
- **Parte B:** prueba de independencia (Chi-cuadrado) entre el tipo de modalidad y la ocurrencia de complicaciones evitables, mediante tabla de contingencia.

### Ejercicio 3 — Evaluación del programa de capacitación en triage
Análisis de diseño abierto sobre la mejora en el desempeño del personal de enfermería (evaluación de competencias antes/después de una capacitación), incluyendo:
- Justificación de muestras pareadas.
- Evaluación visual del supuesto de normalidad sobre la diferencia de puntajes.
- Ejecución y comparación de una prueba paramétrica (t pareada) y su alternativa no paramétrica (Wilcoxon).
- Recomendación final a Recursos Humanos sobre la obligatoriedad del programa a nivel nacional.

------------------------------------------------------------------------

## 📁 Estructura del Proyecto

    📦 Sesion_3_Pruebas_de_hipotesis
     ├── README.md
     ├── Sanchez_Jeisson_y_Bogota_Juan_CasoEstudio_sesion3.ipynb
     ├── Sesión_2_ Análisis_Descriptivo_Multivariado.ipynb
     ├── Sesión_3_Pruebas_de_hipótesis.ipynb
     └── Sesion3_Caso_Estudio_Vitalcol.pdf

### 📖 Contenido

- **Desarrollo del taller** en Jupyter Notebook (Google Colab / VS Code):
  `Sanchez_Jeisson_y_Bogota_Juan_CasoEstudio_sesion3.ipynb`
- **Recurso de la Sesión 2** (Analisis descriptivo multivariado):
`Sesión_2_ Análisis_Descriptivo_Multivariado.ipynb`
- **Recurso de la Sesión 3** (introducción a las pruebas de hipótesis, caso guía Vitalcol):
  `Sesión_3_Pruebas_de_hipótesis.ipynb`
- **Enunciado del caso de estudio** (Tarea 3 — Pruebas de Hipótesis):
  `Sesion3_Caso_Estudio_Vitalcol.pdf`

------------------------------------------------------------------------

## 🛠 Tecnologías

- Python
- Pandas / NumPy
- SciPy (`scipy.stats`: t de Student, ANOVA, Chi-cuadrado, Wilcoxon)
- Statsmodels (pruebas complementarias y salidas formales)
- Matplotlib / Seaborn (visualización)
- Jupyter Notebook / Google Colab / VS Code
- Git y GitHub

------------------------------------------------------------------------

## 📈 Aprendizajes Obtenidos

A través de este taller se desarrollaron las siguientes competencias:

- Formulación formal de hipótesis estadísticas (H₀ y H₁) a partir de preguntas de negocio ambiguas, incluyendo la distinción entre pruebas de una y dos colas.
- Selección crítica de la prueba estadística adecuada según el tipo de variable, el número de grupos, y si las muestras son independientes o pareadas.
- Evaluación del supuesto de normalidad mediante inspección visual (histogramas, boxplots) y razonamiento sobre el tamaño de muestra, en lugar de depender únicamente de pruebas formales.
- Comparación entre pruebas paramétricas y no paramétricas (t vs. Wilcoxon), y análisis de cuándo su elección cambia (o no) la conclusión de negocio.
- Distinción entre significancia estadística y relevancia práctica de un resultado.
- Identificación de limitaciones metodológicas (ausencia de grupo control, sesgo de selección, correlación vs. causalidad) antes de tomar decisiones basadas en los resultados.
- Redacción de conclusiones orientadas a un público de negocio, no técnico.
- Trabajo colaborativo mediante Git y GitHub, incluyendo la resolución de conflictos de merge.

------------------------------------------------------------------------

## 👨‍💻 Autores

[![GitHub](https://img.shields.io/badge/GitHub-JeissonS02-181717?style=for-the-badge&logo=github)](https://github.com/JeissonS02)
[![GitHub](https://img.shields.io/badge/GitHub-JuanBogota-181717?style=for-the-badge&logo=github)](https://github.com/JuanBogota)
