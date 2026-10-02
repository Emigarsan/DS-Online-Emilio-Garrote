# Team Challenges

[← Repositorio](../README.md)

Retos en equipo que cierran cada fase del bootcamp. Se resuelven en grupo, con Git y *Pull Requests*, y terminan con una breve presentación.

| Reto | Sprint | Tema | Qué hay en la carpeta |
|---|---|---|---|
| [TC 01 · Hundir la flota](TC_01_Sprint_03_Hundir_la_Flota/) | 03 | Programación con Python, NumPy y POO | Enunciado del reto: juego de *Hundir la flota* (tablero 10×10, usuario contra máquina) |
| [TC 02 · SQL](TC_02_Sprint_06_SQL/) | 06 | SQL y diseño de bases de datos | Parte I: [SQL Murder Mystery](TC_02_Sprint_06_SQL/parte_001/) · Parte II: [diseño de una BBDD de e-commerce en BigQuery](TC_02_Sprint_06_SQL/parte_002/) |
| [TC 03 · Toolbox ML](TC_03_Sprint_09_Toolbox/) | 09 | Paquetes de Python, EDA, *testing* | Enunciado: construir el paquete `toolbox_ml` con funciones de EDA y selección de *features* |
| [TC 04 · Kaggle “Data on the top”](TC_04_Sprint_12_Kaggle/) | 12 | ML supervisado (regresión) | Notebooks de la competición: predicción del precio de portátiles |

---

## TC 01 · Hundir la flota
Reto de integración de lo aprendido en los primeros sprints: NumPy, módulos, bucles, funciones, clases y colecciones. Entrega en varios scripts `.py`.
La carpeta contiene el [enunciado](TC_01_Sprint_03_Hundir_la_Flota/Team_Challenge_Hundir_la_Flota.ipynb).

## TC 02 · SQL
- **Parte I** — resolver el caso de [SQL Murder Mystery](http://mystery.knightlab.com) y documentar las consultas en un notebook sobre [la base de datos SQLite](TC_02_Sprint_06_SQL/parte_001/data/sql-murder-mystery.db).
- **Parte II** — diseñar y construir desde cero una base de datos relacional en **Google BigQuery** para un e-commerce de electrónica: modelo entidad-relación, normalización hasta **3FN**, carga de datos con Python, entornos virtuales y trabajo con *feature branches* y *Pull Requests*. Incluye [enunciado](TC_02_Sprint_06_SQL/parte_002/Parte_II_SQL.ipynb), plantilla de [entorno](TC_02_Sprint_06_SQL/parte_002/env.example) y [dependencias](TC_02_Sprint_06_SQL/parte_002/requirements.txt).

## TC 03 · Toolbox ML
Construcción de un paquete Python reutilizable (`describe_df`, `tipifica_variables`, selección y visualización de *features* numéricas y categóricas para regresión), con docstrings, *type hints* y tests con `pytest`. Carpeta: [enunciado](TC_03_Sprint_09_Toolbox/Team_Challenge_Toolbox.ipynb). El paquete `toolbox_ml` reaparece en la [práctica de repaso del Sprint 12](../Sprints/04_Machine_Learning/Sprint_12/Unidad_02_ML_Supervisado_Repaso/03_Practica_Obligatoria/toolbox_ml/).

## TC 04 · Kaggle “Data on the top”
Competición interna de Kaggle: predecir el precio de portátiles (métrica **RMSE**).

- [TC-Kaggle_submission_best.ipynb](TC_04_Sprint_12_Kaggle/TC-Kaggle_submission_best.ipynb) — notebook final: procesado de variables (resolución de pantalla, RAM, almacenamiento, CPU, GPU, marcas y sistemas operativos), EDA de *features*, comparativa de modelos, optimización y reentrenamiento con todos los datos.
- [TC-Kaggle_submission_pruebas.ipynb](TC_04_Sprint_12_Kaggle/TC-Kaggle_submission_pruebas.ipynb) — experimentos intermedios.
- Modelos probados: Random Forest, KNN, árbol de decisión, regresión lineal, **CatBoost**, **XGBoost** y **LightGBM**.
- Resultado en validación: **RMSE ≈ 238** (5-fold CV) y **≈ 241** en el *split* local 80/20.

> Los datos de la competición (`data/`) y los ficheros de envío (`submission/`) no se versionan. Los datos se descargan desde la competición de Kaggle y se colocan en `TC_04_Sprint_12_Kaggle/data/`.
