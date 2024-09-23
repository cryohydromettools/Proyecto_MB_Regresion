# Proyecto: Aprendizaje automático para la modelización del balance de masa de glaciares

**Autores:** <br />
Jordi Bolibar <br />
Facundo Sapienza  
Traducción: Eduardo Villavicencio

## Descripción del proyecto

El proyecto consiste en 4 notebooks de Jupyter en Python, enfocados en la modelización del balance de masa de glaciares utilizando diferentes métodos de regresión. Los datos se extraen usando el [Open Global Glacier Model (OGGM)](https://github.com/OGGM/oggm), que proporciona datos climáticos, topográficos y de balance de masa para casi cualquier glaciar en la Tierra. El proyecto está centrado en los glaciares de Bajas Latitudes, con el objetivo de aprender sobre los cambios de balance de masa multi-anual a partir del artículo geodésico de balance de masa de [Hugonnet et al. (2021)](https://www.nature.com/articles/s41586-021-03436-z). Cubrimos una de las bibliotecas de aprendizaje automático más populares para principiantes: [scikit-learn](https://scikit-learn.org/stable/).

Los siguientes temas son cubiertos en este proyecto:

1. [Pre-procesamiento de datos](https://github.com/cryohydromettools/Proyecto_MB_Regresion/blob/main/1_Preprocessing.ipynb) :earth_africa:: Aquí aprendemos cómo extraer todos los datos climáticos, topográficos y de balance de masa necesarios para cualquier glaciar en la Tierra usando OGGM.

2. [Exploración de datos](https://github.com/cryohydromettools/Proyecto_MB_Regresion/blob/main/2_Data_exploration.ipynb) :mag:: Aquí aprendemos cómo entender el conjunto de datos que hemos recopilado, cuáles son los supuestos detrás de ellos y cómo construir correctamente un buen conjunto de datos para modelos de aprendizaje automático de regresión de procesos físicos.

3. [Entrenamiento](https://github.com/cryohydromettools/Proyecto_MB_Regresion/blob/main/3_Training.ipynb) :rocket:: Aquí introducimos los diferentes métodos de aprendizaje automático que podemos usar para simular el balance de masa de glaciares. Exploraremos las características de cada uno, incluidos sus hiperparámetros específicos.

4. [Validación](https://github.com/cryohydromettools/Proyecto_MB_Regresion/blob/main/4_Validation.ipynb) :dart:: Una vez que estemos familiarizados con los diferentes modelos de aprendizaje automático, introduciremos los conceptos de validación cruzada y selección de hiperparámetros. Elegiremos uno de los modelos, que ajustaremos en detalle en la validación cruzada para extrapolar correctamente datos no vistos.

### ¡Proyectos adicionales!

El objetivo principal del proyecto es aprender los fundamentos de los flujos de trabajo de aprendizaje automático aplicados a la modelización glaciar y geofísica. No obstante, para aquellos interesados en profundizar en los aspectos glaciológicos, proponemos dos proyectos adicionales. Estos dos proyectos usan conjuntos de datos distribuidos (enrejados), que tienen una mayor resolución espacial y complejidad. Se pueden seguir dos notebooks adicionales para esto:

5. [Pre-procesamiento de datos distribuidos](https://github.com/cryohydromettools/Proyecto_MB_Regresion/blob/main/5_Distributed_preprocessing.ipynb) :bar_chart:: En este notebook aprendemos a descargar conjuntos de datos enrejados para cualquier glaciar en el mundo, incluidos el balance de masa geodésico, datos de espesor de hielo, datos topográficos como la pendiente de la superficie, la orientación, la distancia al borde, y cómo reducir fácilmente la escala de los datos climáticos para esos glaciares.

6. [Proyectos adicionales](https://github.com/cryohydromettools/Proyecto_MB_Regresion/blob/main/6_Bonus_Projects.ipynb) :diamonds:: En este notebook presentamos los dos proyectos adicionales: uno centrado en predecir tasas de balance de masa geodésico enrejadas y otro en inferir el espesor del hielo glaciar distribuido.

> Actualizaremos este proyecto de manera iterativa. Si encuentras algún error o equivocación en los notebooks, no dudes en hacer un pull request.
