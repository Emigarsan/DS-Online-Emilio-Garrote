# Projects · Project Breaks

[← Repositorio](../README.md)

Los *Project Breaks* son los proyectos de mayor envergadura del bootcamp: se trabajan en equipo, parten de un problema concreto y terminan con una presentación. Son lo más representativo de mi forma de trabajar.

| Proyecto | Tipo | Stack | Equipo |
|---|---|---|---|
| [**Project Break I** · EDA de juegos de mesa](Project_Break_I/README.md) | Análisis exploratorio de datos | Python, pandas, matplotlib, seaborn, API de BoardGameGeek | 2 personas |
| [**Project Break II** · Forecasting de ocupación de un spa](Project_Break_II/README.md) | Machine Learning + despliegue web | Python, scikit-learn, holidays, joblib, Flask, React, Render | 3 personas |

---

## Project Break I · Qué ocurre con los juegos de mesa

**Pregunta:** ¿qué características (complejidad, duración, número de jugadores, edad mínima, mecánicas, categorías…) se asocian a mejores valoraciones y mayor popularidad en BoardGameGeek?

- Datos obtenidos de la API de BoardGameGeek, normalizados en tablas relacionales (juegos, categorías, mecánicas, diseñadores, editores…).
- Cuatro hipótesis planteadas de antemano y contrastadas con análisis uni, bi y multivariante.
- Entregables: notebook principal, [presentación](Project_Break_I/Project_Break_I_EDA/EDA_Tabletop_Games_presentation.pdf) y [memoria técnica](Project_Break_I/Project_Break_I_EDA/Tabletop_games_memoria_tecnica.pdf).

**Habilidades:** consumo de APIs · limpieza y normalización · EDA · visualización · formulación de hipótesis · comunicación de resultados.

## Project Break II · Predicción de ocupación de un spa

**Pregunta:** ¿cuántas citas habrá en cada tramo horario (mañana/tarde) para dimensionar personal y cabinas?

- **Datos reales de un negocio en funcionamiento**: el export original contiene datos personales y no se versiona (RGPD); solo se publican agregados sin información personal.
- Split cronológico *antes* del EDA para evitar fuga temporal; validación con `TimeSeriesSplit`; MAE como métrica (el MAPE era inviable con tramos de 0 citas).
- Comparativa de 6 algoritmos, optimización con `RandomizedSearchCV` y **una única evaluación final** contra test.

| Modelo (test, 2026-01-25 → 2026-06-30) | MAE | RMSE | R² |
|---|---:|---:|---:|
| Baseline: media de train | 2,76 | 3,70 | −0,22 |
| Baseline estacional (t-7) | 2,46 | 3,16 | 0,11 |
| **Random Forest (final)** | **1,92** | **2,52** | **0,43** |

- Desplegado como servicio web (API + frontend): [demo en vivo](https://spa-occupancy-frontend-y2wk.onrender.com) · [código del servicio](https://github.com/Emigarsan/Spa_model_webservice).
- Trabajo en equipo con Git Flow: ramas `feature/*`, *Pull Requests* revisadas e *issues* ([ML_Spa_M003](https://github.com/Emigarsan/ML_Spa_M003)).

**Habilidades:** ML sobre series temporales · *feature engineering* con calendario y festivos · protección de datos personales · interpretabilidad · despliegue · trabajo colaborativo con Git.
