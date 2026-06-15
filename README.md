# Modelado dinámico de degradación de motores Turbofan mediante NODEs y UDEs

Proyecto desarrollado para la materia Datos, Ecuaciones Diferenciales e Inteligencia Artificial (FCEN, UBA).

## Descripción 

En este trabajo se estudia la predicción de fallas en motores turbofan utilizando el dataset **C-MAPSS** de la NASA. El problema se formula como uno de análisis de supervivencia, modelando directamente la probabilidad de falla a partir de datos de sensores.

Para ello se implementaron y comparan modelos basados en:

+ Neural Differential Equations (NODEs)

+ Universal Differential Equations (UDEs)


## Tecnologías

+ Julia

+ Librerias: CSV, DataFrames, Statistics, Plots, Lux, ComponentArrays, OrdinaryDiffEq, SciMLSensitivity, Optimization, OptimizationOptimisers, Zygote, DataInterpolations, MLUtils y LinearAlgebra.


## Reproducción de resultados

La implementación del proyecto se encuentra en:

```mi_entorno/degradacionHilos.ipynb```

## Presentación

+ Informe: Motores_Informe.pdf

+ Poster: Poster_Motores.pdf 

## Autores 

+ Gian Lucca Sanza

+ Sebastian Souto