#ProyectoAGG01
1.Instalaciones; Este proyecto esta destinado a resolver el proyecto 01 del curso científico de datos de UADACITY

2.Motivación del proyecto: Este proyecto esta motivado en poder desarrollar las habilidades en Ciencia de Datos y poder contestar las siguientes 3 preguntas:

a. ¿Cuál es el tipo de desarrollo más popular entre los individuos? b. ¿Cuál es el genero que tiene una mayor participación en el mercado de la programación? c. ¿Qué tan bien podemos predecir el ExpectedSalary que va a preferir un nuevo individuo?

El resultado del análisis realizado es: El tipo de desarrollador más popular es Web developer con un 38%, el segundo es Desktop applications developer con 15% El genero que tiene la mayor participación en los individuos que programan es Male con el 85%, luego viene female con un 15% Con el ejercicio de hacer el modelo con regresión, y con los datos recolectado la predicción de ExpectedSalary, no es muy buena dado que el Rcuadra en testing es de 23% y en training es de 52%.

3.Descripciones de archivos:

Bibliotecas: import numpy as np import pandas as pd import matplotlib.pyplot as plt from sklearn.linear_model import LinearRegression from sklearn.model_selection import train_test_split from sklearn.metrics import r2_score, mean_squared_error import seaborn as sns import matplotlib.pyplot as plt from collections import defaultdict

Archivos: survey-results-public.csv: Base de datos de la encuentra survey-results-schema.csv: Base de datos del esquema de preguntas realizadas Proyecto1.ipynb: programa en jupiterNotebook para responder a la pregunta a, b y c de este proyecto Proyecto1

4.Cómo interactuar con tu proyecto En una plataforma jupiterNotebook cargar los archivos y las bases de datos.

5.Licencias, Autores, Agradecimientos, etc. N/A