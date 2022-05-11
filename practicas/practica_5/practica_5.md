
Universidad de Costa Rica  <br>
Sistema de Estudios de Posgrado <br>
Maestría en Computación e Informática <br>
PF-3121 - Técnicas de Análisis de Grandes Volúmenes de Datos <br>
Ciclo: I-2022 <br>
Docente: Allan Berrocal Rojas

---

# Práctica 5 - Trees


## Preliminares

En esta práctica se utiliza la herramienta [`Jupyter Lab`](https://jupyter.org/index.html) que se mostró en clases. Alternativamente, usted puede hacer la práctica usando el servicio de `Google Cloud` llamado [Colab](https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l01c01_introduction_to_colab_and_python.ipynb#scrollTo=YHI3vyhv5p85)

Para esta práctica los materiales se encuentran en los links que se mencionan más adelante. 

## Contexto

Esta práctica gira en torno a los conceptos de algoritmos de aprendizaje de máquina basados en árboles de decisión *DecisionTree Classifier & Regressor*, *RandomForest Classifier & Regressor*,y *Gradient Boosting Classifier & Regressor* 

## Asignación

La práctica consiste en seguir dos tutoriales cortos disponibles en el sitio web [Machine Learning Mastery](https://machinelearningmastery.com/) y escritos por el Dr. Jason Brownlee. 


Seleccione al menos dos de los siguientes tres tutoriales para esta práctica. 

1. [How to Develop a Random Forest Ensemble in Python](https://machinelearningmastery.com/random-forest-ensemble-in-python/)
2. [Extreme Gradient Boosting (XGBoost) Ensemble in Python](https://machinelearningmastery.com/extreme-gradient-boosting-ensemble-in-python/)
1. [How to Develop an Extra Trees Ensemble with Python](https://machinelearningmastery.com/extra-trees-ensemble-with-python/)

Pasos específicos:

1. Para cada tutorial seleccionado, 
- [30% c/u] cree un `Notebook` con el nombre `reporte_tutorial_[1,2].ipynb` y transcriba ahí el código ejecutable del tutorial para que pueda estudiarlo, modificarlo y cambiarlo como parte de la práctica para facilitar su comprensión de los conceptos.
- [5%] Agregue una sección al notebook con título __Comentarios del ejercicio__ y escriba ahí un breve reporte (máximo 300 palabras) resumiendo lo que ha aprendido y el posible uso que le dará a esta materia como profesional. Incluya comentarios sobre aspectos que haya aprendido en el ejercicio, aspectos que no le quedan claros, o que quisiera conocer mejor.
- [15% c/u] Preste especial atención a los aspectos relacionados con el uso de los algoritmos (`DecisionTree`, `RandomForest`, `XGB`, `ExtraTrees`) en lo que se refiere a los parámetros de control de complejidad. Estudie el impacto que tiene cada parámetro en el modelo resultante, agregue una sección al notebook con título __Comentarios sobre parámetros__ y escriba un comentario breve sobre sus hallazgos. 
2. Hay elementos en el tutorial que no hemos estudiado aún como `RepeatedStratifiedKFold`, `cross validation`. Si gusta puede estudiarlos brevemente usted mismo leyendo en la documentación de [`Scikit-learn`](https://scikit-learn.org/stable/modules/classes.html) si le parecen conceptos familiares, sino, no se preocupe por ahora ya que algunos de estos conceptos los vamos a cubrir adelante en el curso. 

Material **opcional** para auto estudio si es de su interés. 

1. Reemplace el *data set* sintético que utilizan los tutoriales (creado con la subrutina ` make_classification` de la  biblioteca `sklearn.datasets`) por un *data set* de su propio interés. Solo debe asegurarse de usar un *data set* que esté etiquetado para un problema de clasificación o que tenga un atributo *target* o variable dependiente contínua para un problema de regresión.  
2. Paso a paso como se crea un algoritmo del tipo `DecisionTree` [How To Implement The Decision Tree Algorithm From Scratch In Python](https://machinelearningmastery.com/implement-decision-tree-algorithm-scratch-python/)
3. La biblioteca [`XGBoost`](https://github.com/dmlc/xgboost) se puede configurar para usar el algoritmo de `Gradient Boosting` sobre `RandomForest` (y es en apariencia más rápido que otras implementaciones de `RandomForest` como la de `scikit-learn`). La biblioteca es fácil de utilizar y los parámetros son casi idénticos a aquellos del algoritmo de `RF` de `scikit-learn`. Aquí hay un ejemplo [How to Develop Random Forest Ensembles With XGBoost](https://machinelearningmastery.com/random-forest-ensembles-with-xgboost/)
4. Si quieren visualizar Arboles creados mediante GradientBoosting [How to Visualize Gradient Boosting Decision Trees With XGBoost in Python](https://machinelearningmastery.com/visualize-gradient-boosting-decision-trees-xgboost-python/)




## Entregables 

En su repositorio personal para este curso, cree un directorio que se llame `/practicas/practica_5` y agregue los siguientes archivos:

1. Los dos archivos generados arriba `reporte_tutorial_1.ipynb` y `reporte_tutorial_2.ipynb` con las partes que se le solicitó.


 

