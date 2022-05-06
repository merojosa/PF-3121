## Data set

https://www.kaggle.com/datasets/rankirsh/evolution-of-top-games-on-twitch


## Preguntas de investigación

1. ¿Cuál categoría será la más popular en el 2022?
2. ¿Cuántas horas vistas en total registrará diciembre del 2022?
3. ¿Cuál streamer hispanohablante será más visto en el 2022?

## OpenRefine

### Tres problemas con los datos

1. La columna Hours_Streamed tiene la palabra "hours" luego del número. Se propone remover esa palabra para todas las filas y convertir la columna en numérica.
2. Avg_viewer_ratio tiene algunos valores enteros y otros con decimales. Se propone convertir toda la columna en flotante.
3. El data set tiene filas repetidas ya que es un ranking mensual de categorías. Se propone hacer grouping.

### Dos atributos importantes

1. Hours_watched: Determina la popularidad de una categoría. Entre más horas, más popular será.
2. Month y Year: Ya que se quiere determinar lo que podría pasar en el 2022, definitivamente el mes y el año de cada fila es importante para implementar el modelo.

### Dos transformaciones en el data set

1. Se removió en la columna Hours_streamed la palabra "hours" para así poder convertir la columna a tipo númerico. Las demás columnas con números que no ocupaban remover nada más se convertieron directamente a númerico.
2. Se creó una nueva columna year_month_date con las columnas Year y Month. El join se hizo con el separador "-" así tendría un formato permitido disponible para fechas ISO. Al tener dicha columna con el formato YYYY-MM, se transformó a fecha.

NOTA: Profesor, no encontré una forma de hacer grouping más allá de hacer el join. Es más una cuestión teórica que técnica, porque quisiera volver a consultar con usted en su momento qué se hace en este caso con un data set histórico. ¿Se separa por periodos de tiempos? ¿Por meses? ¿Años?