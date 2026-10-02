# Emilio Garrote Sánchez · Portfolio del Bootcamp de Data Science + IA

**Data Analyst Junior · Power BI · SQL · Python · ETL**

Este repositorio reúne todo el trabajo que desarrollé en el **Bootcamp de Data Science + IA de [The Bridge](https://www.thebridge.tech/)** (marzo – septiembre 2026): 18 sprints de formación más material adicional, dos *Project Breaks*, cuatro *Team Challenges*, masterclasses y microcredenciales. Va de Python básico a Machine Learning, Deep Learning y despliegue en la nube, y está organizado para que puedas ir directo a lo que te interese.

Vengo de **9 años de experiencia técnica en investigación científica** (Doctorado en Biología Computacional, Máster en Bioinformática) y administración de sistemas Linux, donde construí pipelines ETL, modelos y herramientas de análisis. El bootcamp me ha dado el marco formal de ciencia de datos y BI sobre esa base.

---

## 🎯 Proyectos destacados

| Proyecto | Qué demuestra | Resultado |
|---|---|---|
| [**Project Break II · Forecasting de ocupación de un spa**](Projects/Project_Break_II/) | Proyecto de ML de principio a fin con **datos reales y privados** (RGPD), validación temporal, *feature engineering*, interpretabilidad y **despliegue web** | Random Forest con **MAE 1,92** citas/tramo en test vs. 2,46 del baseline estacional (**R² 0,43**). [Demo en vivo](https://spa-occupancy-frontend-y2wk.onrender.com) |
| [**Project Break I · EDA de juegos de mesa**](Projects/Project_Break_I/) | Obtención de datos vía API, limpieza, análisis univariante/bivariante/multivariante, formulación y contraste de hipótesis, comunicación de resultados | Análisis de BoardGameGeek con 4 hipótesis, presentación y memoria técnica |
| [**Team Challenge · Kaggle “Data on the top”**](Team_Challenges/TC_04_Sprint_12_Kaggle/) | Competición de regresión (precio de portátiles) con CatBoost, XGBoost y LightGBM, validación cruzada y optimización | RMSE ≈ 238 en validación cruzada (5-fold) |
| [**Workshops AWS · API Flask en EC2 y PostgreSQL en RDS**](Sprints/06_Data_Engineering/Sprint_18/README.md) | Despliegue de servicios en la nube y bases de datos gestionadas | Flask + SQLAlchemy sobre RDS |

**Fuera de este repositorio:**
[Spa_model_webservice](https://github.com/Emigarsan/Spa_model_webservice) (API Flask + frontend React desplegados en Render) ·
[ML_Spa_M003](https://github.com/Emigarsan/ML_Spa_M003) (repositorio original del Project Break II) ·
[LokiAPP](https://github.com/Emigarsan/LokiAPP) (plataforma full-stack Spring Boot + React desplegada en AWS para gestionar eventos de juegos de mesa en tiempo real).

---

## 🧰 Habilidades y dónde verlas

| Habilidad | Nivel (según CV) | Evidencia en este repositorio |
|---|---|---|
| **Python** (pandas, NumPy, SciPy) | Avanzado | [Sprints 01–04](Sprints/01_Programacion_Basica/README.md) · [NumPy/Pandas](Sprints/02_Herramientas_Avanzadas/README.md) · todos los proyectos |
| **ETL y calidad de datos** | Avanzado | [Sprint 05 · ETL y ficheros](Sprints/03_Data_Analysis/Sprint_05/README.md) · limpieza y trazabilidad en [Project Break II](Projects/Project_Break_II/src/docs/business_case.md) |
| **SQL** | Intermedio | [Sprint 06 · SQL](Sprints/03_Data_Analysis/Sprint_06/README.md) · [TC SQL (SQL Murder Mystery + diseño en BigQuery)](Team_Challenges/TC_02_Sprint_06_SQL/) · [RDS PostgreSQL](Sprints/06_Data_Engineering/Sprint_18/README.md) |
| **Estadística** (descriptiva e inferencial) | Intermedio | [Sprint 07](Sprints/03_Data_Analysis/Sprint_07/README.md) · [Sprint 09](Sprints/04_Machine_Learning/Sprint_09/README.md) |
| **Visualización** (Matplotlib, Seaborn) | Intermedio | [Sprint 08](Sprints/03_Data_Analysis/Sprint_08/README.md) · [EDA de juegos de mesa](Projects/Project_Break_I/) |
| **Power BI** | Intermedio | [Masterclass Power BI](Masterclasses/MC_PowerBI/) (modelo relacional, DAX, informe `.pbix`) |
| **Machine Learning supervisado** (regresión, clasificación, árboles, bagging/boosting) | Intermedio/Avanzado | [Bloque 04](Sprints/04_Machine_Learning/README.md) · [Kaggle](Team_Challenges/TC_04_Sprint_12_Kaggle/) · [Project Break II](Projects/Project_Break_II/) |
| **Machine Learning no supervisado** (K-Means, DBSCAN, PCA, selección de *features*) | Intermedio/Avanzado | [Sprint 13](Sprints/04_Machine_Learning/Sprint_13/README.md) · [Sprint 14](Sprints/04_Machine_Learning/Sprint_14/README.md) |
| **Deep Learning** (Keras, CNN, transfer learning, RNN) | — | [Bloque 05](Sprints/05_Deep_Learning/README.md) |
| **APIs REST** (consumo, diseño, *scraping*) | Intermedio | [Sprint 06 · scraping y APIs](Sprints/03_Data_Analysis/Sprint_06/README.md) · [Sprint 17 · Flask](Sprints/06_Data_Engineering/Sprint_17/README.md) |
| **Series temporales, NLP, Big Data (Spark), aprendizaje por refuerzo** | — | [Bloque 07 · Material adicional](Sprints/07_Material_Adicional/README.md) |
| **Cloud** | Básico | [AWS EC2 y RDS](Sprints/06_Data_Engineering/Sprint_18/README.md) |
| **Git y GitHub** | Intermedio | [Masterclass Git/GitHub](Masterclasses/MC_02_Sprint_02_Git_Github/) · ramas y *Pull Requests* en [ML_Spa_M003](https://github.com/Emigarsan/ML_Spa_M003) |

*El resto de mi stack (Shell/Bash, R, Azure, Java/Spring Boot, React) está en mi CV y en [LokiAPP](https://github.com/Emigarsan/LokiAPP); no se refleja en este repositorio.*

---

## 🗺️ Estructura del repositorio

```
DS-Online-Emilio-Garrote/
├── Projects/                 # Proyectos del bootcamp (los más completos)
│   ├── Project_Break_I/      #   EDA de juegos de mesa (BoardGameGeek)
│   └── Project_Break_II/     #   Forecasting de ocupación de un spa (ML + despliegue)
├── Team_Challenges/          # Retos en equipo
│   ├── TC_01_Sprint_03_Hundir_la_Flota/
│   ├── TC_02_Sprint_06_SQL/
│   ├── TC_03_Sprint_09_Toolbox/
│   └── TC_04_Sprint_12_Kaggle/
├── Sprints/                  # Itinerario completo del bootcamp (18 sprints + extras)
│   ├── 01_Programacion_Basica/      # Sprints 00–02
│   ├── 02_Herramientas_Avanzadas/   # Sprints 03–04
│   ├── 03_Data_Analysis/            # Sprints 05–08
│   ├── 04_Machine_Learning/         # Sprints 09–14
│   ├── 05_Deep_Learning/            # Sprints 15–16
│   ├── 06_Data_Engineering/         # Sprints 17–18
│   └── 07_Material_Adicional/       # Extras: series temporales, NLP, Spark, RL
├── Masterclasses/            # Git/GitHub, Power BI
└── Microcredenciales_UAM/    # Datos sintéticos, Orange Data Mining
```

Cada carpeta tiene su propio README que explica su contenido:

| Zona | Qué encontrarás | README |
|---|---|---|
| **Projects** | Los dos *Project Breaks*, con problema de negocio, método y resultados | [Projects/](Projects/README.md) |
| **Team Challenges** | Retos en equipo: Python/POO, SQL, paquete de herramientas ML y Kaggle | [Team_Challenges/](Team_Challenges/README.md) |
| **Sprints** | Todo el material formativo, por bloque → sprint → unidad | [Sprints/](Sprints/README.md) |
| **Masterclasses** | Sesiones monográficas con material práctico | [Masterclasses/](Masterclasses/README.md) |
| **Microcredenciales UAM** | Datos sintéticos y herramientas visuales de minería de datos | [Microcredenciales_UAM/](Microcredenciales_UAM/README.md) |

### Itinerario del bootcamp

| Bloque | Sprints | Contenido |
|---|---|---|
| [01 · Programación básica](Sprints/01_Programacion_Basica/README.md) | 00–02 | Python, estructuras de datos, funciones, POO |
| [02 · Herramientas avanzadas](Sprints/02_Herramientas_Avanzadas/README.md) | 03–04 | NumPy, Pandas |
| [03 · Análisis de datos](Sprints/03_Data_Analysis/README.md) | 05–08 | ETL, SQL, web scraping y APIs, estadística descriptiva, visualización |
| [04 · Machine Learning](Sprints/04_Machine_Learning/README.md) | 09–14 | Estadística inferencial, ML supervisado y no supervisado |
| [05 · Deep Learning](Sprints/05_Deep_Learning/README.md) | 15–16 | Keras, CNN, transfer learning, RNN |
| [06 · Data Engineering](Sprints/06_Data_Engineering/README.md) | 17–18 | APIs en producción, AWS EC2 y RDS |
| [07 · Material adicional](Sprints/07_Material_Adicional/README.md) | Extra 01–02 | Series temporales, NLP, Big Data con Spark, aprendizaje por refuerzo |

Dentro de cada unidad el esquema se repite: **`01_Workout`** (notebooks guiados) → **`02_Ejercicios_Workout`** (consolidación) → **`03_Practica_Obligatoria`** (práctica evaluable).

---

## ⚙️ Cómo ejecutar el código

1. Clona el repositorio y abre la carpeta en VS Code o JupyterLab.
2. Crea un entorno virtual e instala las dependencias de lo que quieras ejecutar:

   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```

   - Cada proyecto trae su `requirements.txt`: [Project Break I](Projects/Project_Break_I/Project_Break_I_EDA/requirements.txt) y [Project Break II](Projects/Project_Break_II/requirements.txt).
   - Los Sprints usan, según el bloque: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `catboost`, `lightgbm`, `tensorflow`/`keras`, `flask`, `flask-sqlalchemy`, `requests`, `beautifulsoup4`.
3. Ejecuta los notebooks en orden dentro de cada unidad.

**Qué no encontrarás aquí (a propósito):**
- Las soluciones oficiales del bootcamp: el repositorio contiene únicamente mi trabajo.
- Datos con información personal (p. ej. el export original del spa) ni credenciales; los datasets muy pesados se excluyen con `.gitignore` (consulta el README de cada zona).

---

## 📬 Contacto

- 📧 [emilio.garrote.sanchez@gmail.com](mailto:emilio.garrote.sanchez@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/emilio-garrote-s%C3%A1nchez-56b7a815b)
- 🐙 [GitHub · Emigarsan](https://github.com/Emigarsan)

Busco incorporarme a un equipo de datos y BI donde aportar esta base analítica y de ingeniería de datos, crecer en el ecosistema Microsoft (Power BI, Azure) e iniciarme en proyectos de IA aplicada al negocio.

---
*Última actualización: octubre de 2026*
