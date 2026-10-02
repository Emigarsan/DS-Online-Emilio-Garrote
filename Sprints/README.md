# Sprints · Itinerario del bootcamp

[← Repositorio](../README.md)

Aquí está el trabajo de los 18 sprints del Bootcamp de Data Science + IA, agrupado en seis bloques temáticos, más un séptimo bloque de material adicional. Cada sprint tiene dos o tres unidades y cada unidad sigue el mismo esquema: **Workout** (notebooks guiados) → **Ejercicios** → **Práctica obligatoria**.

| Bloque | Sprints | De qué trata |
|---|---|---|
| [01 · Programación básica](01_Programacion_Basica/README.md) | 00–02 | Fundamentos de programación con Python y de las herramientas de trabajo (Jupyter, Markdown): sintaxis, estructuras de datos, funciones, flujos de control y programación orientada a objetos. |
| [02 · Herramientas avanzadas](02_Herramientas_Avanzadas/README.md) | 03–04 | Las dos librerías base de todo el ecosistema de datos en Python: NumPy para cálculo numérico y Pandas para manipulación de datos tabulares. |
| [03 · Análisis de datos](03_Data_Analysis/README.md) | 05–08 | El ciclo completo del análisis de datos: extracción desde ficheros, bases de datos SQL, web scraping y APIs; limpieza y transformación (ETL); estadística descriptiva; y visualización con Matplotlib y Seaborn. |
| [04 · Machine Learning](04_Machine_Learning/README.md) | 09–14 | Estadística inferencial y Machine Learning con scikit-learn: aprendizaje supervisado (regresión, clasificación, árboles, ensembles, KNN, SVM) y no supervisado (clustering, PCA, selección de características), con evaluación y validación de modelos. |
| [05 · Deep Learning](05_Deep_Learning/README.md) | 15–16 | Introducción a las redes neuronales: perceptrón y MLP, Keras, redes convolucionales, transfer learning / fine-tuning y redes recurrentes para series temporales. |
| [06 · Data Engineering y despliegue](06_Data_Engineering/README.md) | 17–18 | Del notebook a producción: APIs REST con Flask, despliegue de modelos, cloud computing en AWS (EC2) y bases de datos en la nube (RDS PostgreSQL). |
| [07 · Material adicional](07_Material_Adicional/README.md) | Extra 01–02 | Material complementario fuera del itinerario principal: series temporales, procesamiento de lenguaje natural, Big Data con Spark y aprendizaje por refuerzo. |

## Mapa de progresión

```
Python ─► NumPy/Pandas ─► ETL · SQL · APIs ─► Estadística · Visualización
                                    │
                                    ▼
      Despliegue (Flask · AWS) ◄─ Deep Learning ◄─ Machine Learning
```

Aparte, el bloque 07 amplía con series temporales, NLP, Big Data (Spark) y aprendizaje por refuerzo.

## Notas

- El bloque 07 reúne material complementario (series temporales, NLP, Spark, aprendizaje por refuerzo) que no forma parte de los 18 sprints del itinerario principal.
- Los *Project Breaks* y los *Team Challenges* asociados a cada fase viven fuera de esta carpeta: ver [Projects](../Projects/README.md) y [Team Challenges](../Team_Challenges/README.md).
- Las soluciones oficiales del bootcamp **no** se versionan: el repositorio contiene únicamente mi trabajo.
- Los datasets muy pesados (p. ej. imágenes de las prácticas de CNN) se excluyen mediante `.gitignore`.
