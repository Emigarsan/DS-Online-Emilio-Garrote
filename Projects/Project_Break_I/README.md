# Project Break I · EDA de juegos de mesa (BoardGameGeek)

[← Projects](../README.md) · [Repositorio](../../README.md)

Análisis exploratorio de datos de [BoardGameGeek](https://boardgamegeek.com/) para identificar qué características de un juego de mesa (valoración, popularidad, complejidad, duración, jugadores, edad mínima, categorías y mecánicas) se asocian a mejores resultados.

> **Documentación completa del proyecto** (hipótesis, metodología, conclusiones): [Project_Break_I_EDA/README.md](Project_Break_I_EDA/README.md)

## Entregables

| Qué | Dónde |
|---|---|
| Notebook principal | [main.ipynb](Project_Break_I_EDA/main.ipynb) |
| Presentación | [EDA_Tabletop_Games_presentation.pdf](Project_Break_I_EDA/EDA_Tabletop_Games_presentation.pdf) |
| Memoria técnica | [Tabletop_games_memoria_tecnica.pdf](Project_Break_I_EDA/Tabletop_games_memoria_tecnica.pdf) |
| Notebooks de desarrollo (limpieza, análisis, gráficos) | [src/notebooks/](Project_Break_I_EDA/src/notebooks/) |
| Funciones reutilizables | [src/utils/funciones.py](Project_Break_I_EDA/src/utils/funciones.py) |
| Tablas depuradas | [src/data/tables/](Project_Break_I_EDA/src/data/tables/) |
| Gráficos generados | [src/img/](Project_Break_I_EDA/src/img/) |

## Qué demuestra

- **Obtención de datos** desde la API de BoardGameGeek con scripts de descarga por lotes.
- **Limpieza y modelado de datos**: de un JSON anidado a tablas relacionales (juegos, categorías, mecánicas, diseñadores, artistas, editores…).
- **EDA completo**: univariante, bivariante y multivariante, con métricas como la valoración bayesiana.
- **Método**: cuatro hipótesis planteadas de antemano y contrastadas con los datos.
- **Comunicación**: visualizaciones, presentación y memoria técnica.

## Reproducir los datos

Por tamaño, el repositorio **no incluye** los lotes JSON brutos de la API (`src/data/groups/*.json`, ~400 MB), el vídeo de la presentación ni el ejemplo auxiliar de YouTube. Las tablas ya depuradas de `src/data/tables/` sí están, por lo que los notebooks de análisis funcionan sin regenerar nada.

Para volver a descargar los datos de la API:

1. Crea un fichero `.env` en `Project_Break_I_EDA/` con tu token: `BGG_TOKEN="<tu-token>"`.
2. Descarga los datos por lotes con [bgg_id_batch_downloader.py](Project_Break_I_EDA/bgg_id_batch_downloader.py) (lee los IDs de `boardgames_ranks.csv`, guarda cada lote en JSON y permite reanudar).
3. Une los lotes en ficheros combinados con [src/data/groups/groups_batches.py](Project_Break_I_EDA/src/data/groups/groups_batches.py).

## Equipo

- Emilio Garrote Sánchez — [@Emigarsan](https://github.com/Emigarsan)
- Sandra Gusi Martínez — [@sgusmar](https://github.com/sgusmar) · [repositorio original del proyecto](https://github.com/sgusmar/Tabletop-games-EDA)
