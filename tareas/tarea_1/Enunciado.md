Universidad de Costa Rica  <br>
Sistema de Estudios de Posgrado <br>
Maestría en Computación e Informática <br>
PF-3121 - Técnicas de Análisis de Grandes Volúmenes de Datos <br>
Ciclo: I-2022 <br>
Docente: Allan Berrocal Rojas

---

# Tarea 1


## Preliminares

En esta tarea se utilizan las herramienta [`OpenRefine`](https://openrefine.org/) y [`Jupyter Lab`](https://jupyter.org/index.html) que ya hemos introducido en clases. 

## Contexto

Esta práctica gira en torno a los conceptos introductorios del curso: **preprocesamiento de datos** y **análisis exploratorio**.  

## Asignación

1. [5%] Buscar un *data set* público (elección libre) ojalá puro (que tenga problemas, que no esté limpio). No debe ser gigante pero idealmente lo suficientemente grande para que puedan experimentar con él.
2. [0%] Cree un documento en `Markdown` llamado `reporte_tarea_1.md` con las anotaciones que hará para esta tarea.
3. [5%] Escriba en su reporte al menos **tres** preguntas de investigación que quisiera estudiar a partir de dicho *data set*
2. En la primera fase utilice la herramienta `OpenRefine`. 
	- Explorre el *data set* con las funcionalidades para las cuales `OpenRefine` se muestra util.
	- [10%] Identifique y escriba en su reporte al menos **tres problemas** (no tribiales y de diferente naturaleza) con los datos y proponga correcciones o alternativas. Haga al menos tres cambios de atributos para corregir los problemas identificados.
	- [10%] Siguiendo las preguntas que usted se planteó inicialmente, identifique al menos **dos atributos** que considera importantes o posiblemente valiosos para resolver dichas preguntas. Liste dichos atributos en su reporte y explique brevemente su fundamentación.
	- [10%] Haga al menos **dos transformaciones** (no tribiales y de diferente naturaleza) en el *data set* tales como quitar filas o columnas anómalas. Explique el brevemente la fundamentazión de sus transformaciones.
	- [5%] Exportar los resultados del *data set* con `OpenRefine` para su posterior uso en un análisis exploratorio.
	- [5%] Exportar el historial de acciones que realizó con `OpenRefine` (No exportar proyecto, sino el archivo `.json` con el historial de cambios que realizó).
2. En la segunda fase use la herramienta `Jupyter Notebook` o `Google Colab`.
	- [5%] Cree un notebook llamado `EDA_tarea_1.ipynb`  para hacer un análisis exploratorio de datos (*Exploratory Data Analysis*). Agregue celdas de formato `Markdown` explicando el proceso que sigue en su *EDA*. 
	- [15%] Utilice y explique brevemente al menos **tres técnicas** durante su proceso de *EDA* (e.g. estadística descriptiva, correlaciones, particionamiento de clases, visualizaciones). Incluya una breve interpretación en sus propias palabras de los resultados obtenidos con cada técnica. 
	- [15%] Cree al menos **dos gráficas** y discuta la distribución de los atributos que consideró de más interés para resolver las preguntas que usted se planteó inicialmente. Las gráficas deben estar bien hechas, identificar el nombre de los datos en cada eje, escala de valores, simbología, y la discusión debe ser congruente con la gráfica. 
	- [10%] Identifique al menos **dos atributos** problemáticos que ofrecen poco valor (redundantes, *sparce*, pocos-valores, etc.).
	- [5%] En el `notebook`  de esta parte `EDA_tarea_1.ipynb` deben quedar claros cada uno de los pasos anteriores. Agregue encabezados o secciones que ayuden a identificar cada uno de los puntos que se le solicitan en la tarea.


## Entregables 

En su repositorio personal para este curso, cree un directorio que se llame `/tareas/tarea_1` y agregue los siguientes archivos:


1. El *data set* inicial que utilizó. **NOTA**: Si es muy grande subirlo comprimido. 
2. El dataset transformado mediante `OpenRefine` (exportar *data set* resultante).
2. El historial de acciones que realizó con `OpenRefine` (No exportar proyecto sino el archivo `.json` con el historial de cambios que realizó).
3. El `notebook` ( `EDA_tarea_1.ipynb`) de `Jupyter` donde se muestren las celdas ejecutadas (tablas, gráficos, etc.).
4. El reporte  `reporte_tarea_1.md`. Este puede ser en el formato [`Markdown`](https://www.markdownguide.org/) o bien un archivo con extensión `PDF`. **Nota**: No entregar el reporte en archivos con formato de la familia *Office* (e.g. *MS Word*, *Open Office*, *Pages*, etc.)



