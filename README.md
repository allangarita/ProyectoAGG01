#ProyectoAGG01
1.Instalaciones; Este proyecto esta destinado a resolver el proyecto 01 del curso cient�fico de datos de UADACITY

2.Motivaci�n del proyecto: Este proyecto esta motivado en poder desarrollar las habilidades en Ciencia de Datos y poder contestar las siguientes 3 preguntas:

a. �Cu�l es el tipo de desarrollo m�s popular entre los individuos? b. �Cu�l es el genero que tiene una mayor participaci�n en el mercado de la programaci�n? c. �Qu� tan bien podemos predecir el ExpectedSalary que va a preferir un nuevo individuo?

El resultado del an�lisis realizado es: El tipo de desarrollador m�s popular es Web developer con un 38%, el segundo es Desktop applications developer con 15% El genero que tiene la mayor participaci�n en los individuos que programan es Male con el 85%, luego viene female con un 15% Con el ejercicio de hacer el modelo con regresi�n, y con los datos recolectado la predicci�n de ExpectedSalary, no es muy buena dado que el Rcuadra en testing es de 23% y en training es de 52%.

3.Descripciones de archivos:

Bibliotecas: import numpy as np import pandas as pd import matplotlib.pyplot as plt from sklearn.linear_model import LinearRegression from sklearn.model_selection import train_test_split from sklearn.metrics import r2_score, mean_squared_error import seaborn as sns import matplotlib.pyplot as plt from collections import defaultdict

Archivos: survey-results-public.csv: Base de datos de la encuentra survey-results-schema.csv: Base de datos del esquema de preguntas realizadas Proyecto1.ipynb: programa en jupiterNotebook para responder a la pregunta a, b y c de este proyecto Proyecto1

4.C�mo interactuar con tu proyecto En una plataforma jupiterNotebook cargar los archivos y las bases de datos.

5.Licencias, Autores, Agradecimientos, etc. N/A