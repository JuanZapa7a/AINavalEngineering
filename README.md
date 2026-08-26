# Inteligencia Artificial Aplicada

**Máster Universitario en Ingeniería Naval y Oceánica** — ETS de Ingeniería Naval y Oceánica, Universidad Politécnica de Cartagena (UPCT)

Asignatura optativa, 6 ECTS, 2º curso, 1er cuatrimestre. Código `232209009`. [Guía docente oficial](https://navales.upct.es/guia-docente/232209009).

## Sobre este curso

La idea central de la asignatura es que teoría y práctica formen un todo cohesionado: cada clase de 2 horas introduce un concepto y lo aplica de inmediato sobre un **dataset real** de ingeniería naval y oceánica (sonar, consumo de combustible, hidrodinámica de cascos, inspección submarina, oleaje ECMWF, rutas históricas de barcos, batimetría real), en vez de separar "teoría" y "prácticas" en bloques distintos.

Cada notebook (`NB01`–`NB21`) es autocontenido y corresponde a una sesión real de clase.

## Horario

| | |
|---|---|
| Días | Martes y Miércoles |
| Horario | 09:00 – 10:50 |
| Aula | Aula de Informática |
| Cuatrimestre | 1er cuatrimestre, curso 2026/2027 |
| Inicio periodo docente | 8 de septiembre de 2026 |
| Fin periodo docente | 22 de diciembre de 2026 |

30 sesiones de 2h = 60h de contacto lectivo, exactamente lo que fija la guía docente (32h aula convencional + 28h aula de informática). La planificación sesión a sesión con fechas reales la mantiene el profesor por separado.

## Sistema de evaluación

| Actividad | Peso |
|---|---|
| Parcial 1 (tipo test, a mitad del periodo docente) | 20% |
| Parcial 2 (tipo test, al final del periodo docente) | 20% |
| Resolución individual de un caso práctico ya trabajado en clase | 20% |
| Trabajo individual + defensa oral de un caso de estudio **no visto en clase** | 40% |

Las fechas de los parciales se pactan con el alumnado dentro del horario docente. El caso de estudio del 40% es el proyecto final compartido: `Final_Project_Wave_Height_Forecasting_STARTER.ipynb` (datos reales de una boya oceánica NOAA), lanzado formalmente en `NB21`.

## Contenidos — índice de notebooks

### Bloque 1: Introducción a la IA

| NB | Título |
|---|---|
| [`NB01`](NB01_History_of_AI_and_Applications_in_Naval_Engineering.ipynb) | History of AI and Applications in Naval Engineering |

### Bloque 2: Machine Learning

| NB | Título |
|---|---|
| [`NB02`](NB02_Python_and_Colab_Essentials_First_Naval_Dataset.ipynb) | Python and Colab Essentials — First Naval Dataset |
| [`NB03`](NB03_NumPy_Array_Mechanics_Dtypes_Indexing_and_Views.ipynb) | NumPy Array Mechanics — dtypes, Indexing, and Views |
| [`NB04`](NB04_NumPy_for_Engineering_Computation_Vectors_Matrices_and_Linear_Algebra.ipynb) | NumPy for Engineering Computation — Vectors, Matrices, Linear Algebra |
| [`NB05`](NB05_Matplotlib_Fundamentals_Figures_Axes_and_Real_Naval_Plots.ipynb) | Matplotlib Fundamentals — Figures, Axes, and Real Naval Plots |
| [`NB06`](NB06_SciPy_for_Naval_Engineering_Interpolation_Optimization_and_Signals.ipynb) | SciPy for Naval Engineering — Interpolation, Optimization, Signals |
| [`NB07`](NB07_Machine_Learning_Fundamentals_First_Real_Ship_Dataset.ipynb) | Machine Learning Fundamentals — First Real Ship Dataset |
| [`NB08`](NB08_Decision_Trees_Ensembles_and_SVM_with_Real_Sonar_Data.ipynb) | Decision Trees, Ensembles and SVM with Real Sonar Data |
| [`NB09`](NB09_Clustering_and_Dimensionality_Reduction_with_Real_Data.ipynb) | Clustering and Dimensionality Reduction with Real Data |
| [`NB10`](NB10_A_Complete_ML_Project_Yacht_Hull_Resistance.ipynb) | A Complete ML Project — Yacht Hull Resistance |

### Bloque 3: Deep Learning

| NB | Título |
|---|---|
| [`NB11`](NB11_Neural_Network_Fundamentals_First_PyTorch_Model.ipynb) | Neural Network Fundamentals — First PyTorch Model |
| [`NB12`](NB12_Training_Deep_Networks_Properly.ipynb) | Training Deep Networks Properly |
| [`NB13`](NB13_Convolutional_Neural_Networks_Underwater_Hull_Images.ipynb) | Convolutional Neural Networks — Underwater Hull Images |
| [`NB14`](NB14_Sequence_Models_RNN_LSTM_Real_Fuel_Forecasting.ipynb) | Sequence Models (RNN/LSTM) — Real Fuel Forecasting |
| [`NB15`](NB15_Transfer_Learning_Feature_Extraction_vs_Fine_Tuning.ipynb) | Transfer Learning — Feature Extraction vs Fine-Tuning |
| [`NB16`](NB16_Autoencoders_and_Anomaly_Detection_Real_Fuel_Data.ipynb) | Autoencoders and Anomaly Detection — Real Fuel Data |
| [`NB17`](NB17_Choosing_an_Architecture_Closing_Deep_Learning.ipynb) | Choosing an Architecture — Closing Deep Learning |

### Bloque 4: Proyectos — casos de estudio

| NB | Título |
|---|---|
| [`NB18`](NB18_Case_Study_ECMWF_Predicting_Wave_Height_from_Wind.ipynb) | Case Study: ECMWF — Predicting Wave Height from Wind |
| [`NB19`](NB19_Case_Study_CLIWOC_Nationality_from_Ship_Routes.ipynb) | Case Study: CLIWOC — Nationality from Ship Routes |
| [`NB20`](NB20_Case_Study_GMRT_Bathymetry_Interpolation.ipynb) | Case Study: GMRT Bathymetry — Seafloor Depth Interpolation |
| [`NB21`](NB21_Individual_Project_Launch_Rubric_and_Defense_Template.ipynb) | Individual Project Launch — Rubric and Defense Template |

Tras `NB21`, las 7 sesiones restantes del calendario son de **trabajo supervisado en clase**: el alumnado avanza en su proyecto individual (`Final_Project_Wave_Height_Forecasting_STARTER.ipynb`) con un checkpoint revisado cada sesión, en vez de recibir contenido nuevo — así se cumple el requisito de la guía docente de que el 40% final sea un caso "no visto previamente en clase". El calendario cierra con 2 sesiones de defensa oral: 21 (`NB01`-`NB21`) + 7 de trabajo supervisado + 2 de defensa = 30 sesiones, salvo que algún festivo caiga en martes o miércoles y desplace el calendario.

## Datasets reales utilizados

Ningún dataset de este curso es inventado para la ocasión. Entre otros: Sonar Mines vs. Rocks (UCI), Yacht Hydrodynamics (UCI), Ship Fuel Consumption and CO2 Emissions (Kaggle), LIACi (SINTEF Ocean, inspección visual submarina de cascos), ERA5/ECMWF (viento y oleaje, vía Copernicus CDS), CLIWOC (bitácoras históricas de navegación), GMRT (batimetría global, Lamont-Doherty), y datos reales de boyas oceánicas NOAA NDBC para el proyecto final.

## Profesor

**Juan Francisco Zapata Pérez**

Email: [juan.zapata@upct.es](mailto:juan.zapata@upct.es)

Página personal: [personas.upct.es/perfil/juan.zapata](https://personas.upct.es/perfil/juan.zapata)
