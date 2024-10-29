
![](https://github.com/nadrianTDF/parque_nacional_tierra_del_fuego_y_el_turismo_en_la_provincia/politecnico_header.jpg)

<p align="right">
	<a href="https://github.com/nadrianTDF">
    <img src="https://komarev.com/ghpvc/?username=nadrianTDF" alt="Vistas de perfil" />
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT" />
  </a>
  <a href="https://cookiecutter-data-science.drivendata.org/">
		<img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
	</a>
</p>

---

**Carrera:** Tecnicatura Superior en Ciencia de Datos e Inteligencia 
Artificial.

 **Institucion:** Politécnico Malvinas Argentinas

 **Materia:** Aprendizaje Automático

 **Proyecto Aprendizaje Automatico:** Parque Nacional Tierra del Fuego 
 y el turismo en la provincia

 **Alumno:** Nicora Adrian

 **Profesor de la Catedra:** Martin Mirabete

---
# Parque Nacional Tierra del Fuego y el turismo en la provincia

### Objetivo:

Utilizando técnicas de machine learning, este proyecto tiene como 
objetivo desarrollar un modelo capaz de predecir la afluencia de 
visitantes al parque nacional en funcion de las proyecciones de turismo 
en la provincia.

### Contexto del Problema:

Cada año, el Parque Nacional Tierra del Fuego recibe visitantes de todo 
el mundo. Si bien el parque no genera ingresos directos a la provincia, 
su atractivo natural incentiva y atrae a esos turistas que también 
consumen y pagan por otros servicios de la provincia como alojamiento, 
gastronomía, transporte y otros que si generan ingresos a las arcas del 
gobierno local. 


### Preguntas de estudio:

Algunas de las preguntas que intenta responder este trabajo son:

1. ¿Hay alguna relación entre la cantidad de turistas que visitan el 
Parque Nacional Tierra del Fuego y la cantidad de turistas que visitan 
la provincia?
2. ¿Hay diferencias en esa relación entre turistas residentes y no 
residentes?
3. ¿Es posible predecir la afluencia de visitantes al parque nacional 
en función de la cantidad de turistas que llegan a la provincia?
4. ¿Cuáles variables tienen el impacto más significativo en la predicción?

### Relevancia:

Esta herramienta sería sumamente importante para la planificación de 
recursos para el traslado de esos visitantes hacia el parque nacional, 
ya que ayudaría a las empresas locales especializadas en traslados a 
optimizar sus recursos, así como también mejoraría la “experiencia” de 
los turistas, lo cual genera buenas reseñas de los mismos para futuros 
visitantes y asegura la continuidad en la explotación de este recurso. 

### Organizacion del proyecto

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         parque_nacional_tierra_del_fuego_y_el_turismo_en_la_provincia and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── parque_nacional_tierra_del_fuego_y_el_turismo_en_la_provincia   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes parque_nacional_tierra_del_fuego_y_el_turismo_en_la_provincia a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```
---

