# Sprint 06 · SQL, web scraping y APIs

[← Bloque 03 · Análisis de datos](../README.md) · [Repositorio](../../../README.md)

> Extracción de datos desde bases de datos relacionales y desde fuentes externas (web y APIs).

**Habilidades que se trabajan:** SQL: `SELECT`, `WHERE`, agregaciones, `JOIN` · Conectividad SQLite desde Python · Web scraping con BeautifulSoup · Consumo de APIs

## Unidades

### Unidad 01 · Procesado de datos internos · Bases de datos

Carpeta: [`Unidad_01_Procesado_Datos_Internos_BBDD`](Unidad_01_Procesado_Datos_Internos_BBDD/)

**Qué se trabaja**

- Conectividad y cursores (SQLite)
- Modelo de datos y primeras consultas, `WHERE`
- Agregación y agrupación
- `JOIN` (teoría y ejemplos con `LEFT`)
- Gestión de bases de datos (DDL/DML)
- Base de datos de ejemplo: Chinook

| Carpeta | Contenido | Notebooks |
|---|---|---:|
| [`01_Workout`](Unidad_01_Procesado_Datos_Internos_BBDD/01_Workout/) | Notebooks guiados de teoría y práctica | 10 |
| [`02_Ejercicios_Workout`](Unidad_01_Procesado_Datos_Internos_BBDD/02_Ejercicios_Workout/) | Ejercicios para consolidar lo visto en el Workout | 3 |
| [`03_Practica_Obligatoria`](Unidad_01_Procesado_Datos_Internos_BBDD/03_Practica_Obligatoria/) | Práctica de la unidad | 1 |

**Práctica:** [Práctica obligatoria · SQL](Unidad_01_Procesado_Datos_Internos_BBDD/03_Practica_Obligatoria/18_Practica_Obligatoria_SQL.ipynb)

<details><summary>Ver todos los notebooks de la unidad</summary>

- **01_Workout**
  - [Conectividad Cursores](Unidad_01_Procesado_Datos_Internos_BBDD/01_Workout/03_Conectividad_Cursores.ipynb)
  - [Modelo Datos Primeras Queries](Unidad_01_Procesado_Datos_Internos_BBDD/01_Workout/04_Modelo_Datos_Primeras_Queries.ipynb)
  - [WHERE](Unidad_01_Procesado_Datos_Internos_BBDD/01_Workout/05_WHERE.ipynb)
  - [Agregacion Agrupacion](Unidad_01_Procesado_Datos_Internos_BBDD/01_Workout/06_Agregacion_Agrupacion.ipynb)
  - [Joins Teoria](Unidad_01_Procesado_Datos_Internos_BBDD/01_Workout/07_Joins_Teoria.ipynb)
  - [Join Ejemplos LEFT](Unidad_01_Procesado_Datos_Internos_BBDD/01_Workout/08_Join_Ejemplos_LEFT.ipynb)
  - [Joins Ejemplos II](Unidad_01_Procesado_Datos_Internos_BBDD/01_Workout/09_Joins_Ejemplos_II.ipynb)
  - [Gestion BD](Unidad_01_Procesado_Datos_Internos_BBDD/01_Workout/10_Gestion_BD.ipynb)
  - [Gestion BDs II](Unidad_01_Procesado_Datos_Internos_BBDD/01_Workout/11_Gestion_BDs_II.ipynb)
  - [Extra Problemas SQLite RICHT JOIN DROP COLUMN](Unidad_01_Procesado_Datos_Internos_BBDD/01_Workout/Extra_Problemas_SQLite_RICHT_JOIN_DROP_COLUMN.ipynb)
- **02_Ejercicios_Workout**
  - [Ejercicio Consultas SQL](Unidad_01_Procesado_Datos_Internos_BBDD/02_Ejercicios_Workout/12_Ejercicio_Consultas_SQL.ipynb)
  - [Ejercicio Joins Merge](Unidad_01_Procesado_Datos_Internos_BBDD/02_Ejercicios_Workout/13_Ejercicio_Joins_Merge.ipynb)
  - [Ejercicio Gestion BDs](Unidad_01_Procesado_Datos_Internos_BBDD/02_Ejercicios_Workout/14_Ejercicio_Gestion_BDs.ipynb)
- **03_Practica_Obligatoria**
  - [Práctica obligatoria · SQL](Unidad_01_Procesado_Datos_Internos_BBDD/03_Practica_Obligatoria/18_Practica_Obligatoria_SQL.ipynb)

</details>

### Unidad 02 · Procesado de datos externos · Web scraping y APIs

Carpeta: [`Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs`](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/)

**Qué se trabaja**

- Introducción al web scraping
- BeautifulSoup (I y II) y ejemplos de scraping
- APIs: conceptos y ejemplo

| Carpeta | Contenido | Notebooks |
|---|---|---:|
| [`01_Workout`](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/01_Workout/) | Notebooks guiados de teoría y práctica | 7 |
| [`02_Ejercicios_Workout`](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/02_Ejercicios_Workout/) | Ejercicios para consolidar lo visto en el Workout | 2 |
| [`03_Practica_Obligatoria`](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/03_Practica_Obligatoria/) | Práctica de la unidad | 1 |

**Práctica:** [Práctica obligatoria · Web Scraping APIs](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/03_Practica_Obligatoria/18_Practica_Obligatoria_Web_Scraping_APIs.ipynb)

<details><summary>Ver todos los notebooks de la unidad</summary>

- **01_Workout**
  - [Intro Web Scraping](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/01_Workout/02_Intro_Web_Scraping.ipynb)
  - [BeautifulSoup I](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/01_Workout/03_BeautifulSoup_I_clase.ipynb)
  - [BeautifulSoup II](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/01_Workout/04_BeautifulSoup_II.ipynb)
  - [Ejemplo Scraping I](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/01_Workout/05_Ejemplo_Scraping_I.ipynb)
  - [Ejemplo Scraping II](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/01_Workout/06_Ejemplo_Scraping_II.ipynb)
  - [API I](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/01_Workout/07_API_I.ipynb)
  - [API II Ejemplo](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/01_Workout/08_API_II_Ejemplo.ipynb)
- **02_Ejercicios_Workout**
  - [Ejercicio Web Scraping](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/02_Ejercicios_Workout/10_Ejercicio_Web_Scraping.ipynb)
  - [Ejercicio APIs](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/02_Ejercicios_Workout/11_Ejercicio_APIs.ipynb)
- **03_Practica_Obligatoria**
  - [Práctica obligatoria · Web Scraping APIs](Unidad_02_Procesado_Datos_Externos_Web_Scraping_APIs/03_Practica_Obligatoria/18_Practica_Obligatoria_Web_Scraping_APIs.ipynb)

</details>
