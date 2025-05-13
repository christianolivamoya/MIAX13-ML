# MIAX13-ML

Material preparado para las clases de Machine Learning del máster MIAX: Edición 13

Autores:

* Christian Oliva Moya

* Pedro Ventura Gómez

<hr>

## Contenido del repositorio

* `dataset` incluye los conjuntos de datos que vamos a utilizar durante las clases.

* `slides` incluye las diapositivas que se están viendo durante las clases.

* `notebooks` incluye los notebooks que estamos utilizando como material durante las clases. En particular, un notebook tendrá el siguiente nombre: `<BLOQUE>_<N>_<DESCRIPCION>.ipynb`, donde `<BLOQUE>` será el bloque del temario que tiene relación con el notebook, `<N>` es simplemente un ordinal y `<DESCRIPCION>` da nombre al notebook. Por ejemplo, `3_1_arboles.ipynb` es el primer notebook del bloque 3.

## Temario

* **Bloque 1: Introducción al curso y al Machine Learning. Conceptos básicos de ML** [2025-05-13]
  * Notebook *1_1_introduccion_experimentando_con_activos*. Introducción a un primer concepto de ML con activos financieros.
  
* **Bloque 2: K-Nearest Neighbors (KNN). Introducción a SKlearn y Google Colab** [2025-05-13 y 2025-05-14]
  * Notebook *2_1_knn*. Implementación manual de KNN. Comparación con `KNeighborsClassifier` de SKlearn.
  * Notebook *2_2_knn_experimentando_con_activos*. Uso de KNN con la misma idea de búsqueda de patrones en el tiempo. Introducción a `KNeighborsRegressor` de SKlearn.
  
* **Bloque 3: Árboles de decisión** [2025-05-14]
  * Notebook *3_1_arboles*. Implementación de `DecisionTreeClassifier` y visualización del árbol con SKlearn.
  * Notebook *3_2_bancarrota*. Implementación con SKlearn.
  
* **Bloque 4: Preprocesamiento** [2025-05-16]

* **Bloque 5: Evaluación** [2025-05-16]

* **Bloque 6: Reducción de dimensionalidad** [2025-05-16]

* **Bloque 7: Teoría Bayesiana: Naive Bayes** [2025-05-17]
  * Notebook *7_1_Naive_Bayes*. Ejemplo de uso de SKlearn. Comparación de NB con KNN y árboles en un problema con dependencias entre atributos.

* **Bloque 8: Modelos lineales** [2025-05-17]
  * Notebook *8_1_ejemplos_regresion_lineal*. Dos ejemplos sencillos de aplicar la regresión lineal con SKlearn en finanzas.

* **Bloque 9: SVMs** [2025-05-17]

* **Bloque 10: Conjuntos de clasificadores** [2025-05-17]
  * Notebook *10_1_conjuntos*. Implementación manual de los típicos algoritmos de conjuntos de clasificadores y comparación con la implementación de SKlearn.

* **Bloque 11: Clustering** [2025-05-21 y 2025-05-22]
