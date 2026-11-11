# Primeros pasos con Python para Modelos de Predicción Analítica

Recurso abierto de introducción a Python para predicción analítica, pensado
para personas **sin experiencia previa en programación**. Parte del módulo
"Modelos de Predicción Analítica" del Diplomado en Machine Learning y
Ciencia de Datos.

Todo el contenido son notebooks comentados en español, listos para abrir en
Google Colab y ejecutar celda por celda. **No necesitas instalar nada.**

## Autora
Mgr. Ing. Lesly Zerna

## Cómo usar este curso
1. Haz clic en el botón "Open in Colab" de cada notebook (necesitas una
   cuenta de Google).
2. Guárdate una copia en tu Drive: *Archivo → Guardar una copia en Drive*.
3. Ejecuta las celdas en orden con `Shift + Enter`.
4. Completa las celdas marcadas con `# TODO`. Si te atascas, revisa los
   comentarios y la carpeta `soluciones/` después de la clase.
5. Lee las explicaciones en texto antes de correr el código: explican el
   "por qué", no solo el "qué".

> Nota: Este no es un curso de programación. Aprenderás el Python mínimo necesario para entrenar, evaluar e interpretar modelos de predicción.

## Contenido

### Parte 1 — Fundamentos de Python para datos
| Notebook | Tema | Abrir |
|---|---|---|
| 00 | Colab, variables, listas, DataFrames, funciones y librerías | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leslysandra/primeros-pasos-python/blob/main/notebooks/00_bienvenido_a_python.ipynb) |
| 01 | Manipulación de datos con `pandas` | (badge) |
| 02 | Estadística descriptiva | (badge) |
| 03 | Visualización con `seaborn` y `matplotlib` | (badge) |
| 04 | Ingeniería de variables | (badge) |

### Parte 2 — Modelos de Predicción Analítica
| Notebook | Tema | Abrir |
|---|---|---|
| 10 | Regresión lineal simple y múltiple, diagnóstico de residuos | (badge) |
| 11 | Evaluación de regresión: MAE, RMSE, R², validación cruzada | (badge) |
| 12 | Regresión logística y clasificación | (badge) |
| 13 | Evaluación de clasificación: matriz de confusión, precision, recall, ROC | (badge) |

## Librerías utilizadas
`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`,
`scipy`. En Google Colab ya vienen instaladas.

Uso local (opcional): `pip install -r requirements.txt`

## Datasets
Todos están en la carpeta `data/` (descripción y fuente en `data/README.md`).
Incluye datos de la región para trabajar con casos más cercanos a tu contexto.

## Si vienes de R
Mira `recursos/equivalencias_R_python.md`.

## Licencia
(Elegir, por ejemplo CC BY 4.0 para el contenido y MIT para el código.)
