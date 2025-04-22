# Proyecto de Estadística Bayesiana

## Descripción
Este repositorio contiene el proyecto final para la materia de Estadística Bayesiana de la Maestría en Ciencias Físicas de la Universidad Nacional de Colombia. 
El proyecto implementa métodos bayesianos para análisis estadístico y modelado probabilístico en [contexto específico o conjunto de datos], utilizando el lenguaje de programación R.

## Estructura del Proyecto
```
proyecto-estadistica-bayesiana/
├── data/                 # Conjuntos de datos utilizados
├── scripts/              # Scripts auxiliares y de preprocesamiento
├── output/               # Resultados generados, gráficos y tablas
├── docs/                 # Documentación adicional
├── DESCRIPTION           # Metadatos del proyecto y dependencias
└── README.md             # Este archivo
```

## Objetivo
Este proyecto tiene como objetivo aplicar técnicas de inferencia bayesiana para [objetivo específico, por ejemplo: "estimar parámetros poblacionales", "desarrollar modelos predictivos", "comparar modelos estadísticos", etc.].

## Metodología
El análisis implementa los siguientes métodos bayesianos:

- Inferencia bayesiana paramétrica
- Modelos jerárquicos/multinivel
- Métodos MCMC (Markov Chain Monte Carlo)
- Algoritmos de muestreo (Gibbs, Metropolis-Hastings, HMC)
- Diagnóstico de convergencia
- Selección y comparación de modelos

## Requisitos

Para ejecutar este proyecto, es necesario tener instalado R (versión 4.1.0 o superior) y los siguientes paquetes:

```r
# Instalación de paquetes
install.packages(c(
  "rstan",       # Interface a Stan para modelos bayesianos
  "brms",        # Modelos bayesianos de regresión
  "rstanarm",    # Modelos bayesianos aplicados
  "bayesplot",   # Visualización de modelos bayesianos
  "loo",         # Leave-one-out cross-validation
  "tidyverse",   # Paquetes para manipulación de datos
  "coda",        # Herramientas de diagnóstico para MCMC
  "posterior",   # Manipulación de muestras posteriores
  "rmarkdown",   # Para documentación reproducible
  "knitr"        # Para informes dinámicos
))
```

Alternativamente, para asegurar la reproducibilidad, se puede utilizar el paquete `renv`:

```r
# Restaurar el entorno del proyecto con las versiones exactas
install.packages("renv")
renv::restore()
```

## Resultados Principales

[Breve descripción de los hallazgos más importantes, pueden incluirse imágenes o gráficos clave]

## Uso

Para reproducir el análisis:

1. Clone este repositorio
2. Abra el proyecto en RStudio (archivo .Rproj)
3. Instale las dependencias necesarias
4. Ejecute los scripts en el orden indicado

```bash
git clone https://github.com/usuario/proyecto-estadistica-bayesiana.git
cd proyecto-estadistica-bayesiana
# Abrir en RStudio y ejecutar:
# source("scripts/00_setup.R")
```

## Informes y Análisis

- Los análisis principales se encuentran en archivos R Markdown (`.Rmd`) en la carpeta `scripts/`
- El informe completo compilado está disponible en [enlace o ruta al PDF]
- Las diapositivas de la presentación se encuentran en [enlace o ruta]

## Autor

Samuel Huertas Rojas


## Referencias

- [Referencias bibliográficas relevantes]
- [Literatura utilizada]
- [Fuentes de datos]
