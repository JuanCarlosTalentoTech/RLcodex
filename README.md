# Analítica predictiva de supervivencia en Titanic

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-%232478AD.svg?style=for-the-badge&logo=Seaborn&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Talento Tech](https://img.shields.io/badge/Talento_Tech-Bootcamp_IA-orange?style=for-the-badge)

Proyecto de analítica de datos desarrollado en español a partir del archivo `tested.csv`. El cuaderno `RL_Housing.ipynb` contiene un flujo completo de trabajo: comprensión del dataset, revisión de calidad, análisis exploratorio, preparación de variables, entrenamiento de un modelo de clasificación y conclusiones.

## Archivos del proyecto

| Archivo | Descripción |
|---|---|
| `RL_Housing.ipynb` | Cuaderno principal con explicación Markdown, código reproducible y análisis predictivo. |
| `tested.csv` | Dataset utilizado para el análisis. Contiene información de pasajeros y la variable objetivo `Survived`. |
| `index.html` | Página de presentación lista para publicar con GitHub Pages. |
| `README.md` | Documentación general del repositorio. |
| `requirements.txt` | Dependencias sugeridas para ejecutar el notebook. |

## Objetivo

Construir un proceso de analítica de datos bien organizado para estudiar patrones de supervivencia en pasajeros del Titanic y entrenar un modelo base de clasificación.

## Flujo analítico

1. Carga del archivo CSV.
2. Documentación de variables mediante una tabla de datos.
3. Revisión de tipos, nulos, duplicados y estadísticos descriptivos.
4. Análisis exploratorio con tablas y visualizaciones.
5. Preparación de variables numéricas y categóricas.
6. Entrenamiento de una regresión logística con `scikit-learn`.
7. Evaluación mediante reporte de clasificación, matriz de confusión y AUC ROC.
8. Interpretación de variables y predicción sobre nuevos pasajeros.

## Nota técnica importante

En este archivo, la variable `Survived` está completamente alineada con `Sex`: los registros femeninos aparecen como sobrevivientes y los masculinos como no sobrevivientes. Por esa razón, el modelo puede obtener métricas muy altas. El cuaderno lo documenta explícitamente para evitar una interpretación exagerada de los resultados.

## Cómo ejecutar

Instala las dependencias principales en un entorno de Python:

```bash
pip install -r requirements.txt
```

Luego abre el cuaderno:

```bash
jupyter notebook RL_Housing.ipynb
```

## Publicación en GitHub Pages

El archivo `index.html` puede publicarse directamente con GitHub Pages desde la raíz del repositorio. La página incluye enlaces al cuaderno, al CSV y al repositorio del proyecto.

---

## Créditos y Agradecimientos

Este proyecto fue desarrollado como parte del proceso de aprendizaje en el **Bootcamp de Inteligencia Artificial** de **Talento Tech Colombia**. Agradecemos al Ministerio de Tecnologías de la Información y las Comunicaciones (MinTIC) por promover estas iniciativas de formación técnica avanzada.
