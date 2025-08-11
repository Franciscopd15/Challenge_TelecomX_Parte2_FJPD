# **Challenge Telecom X Parte 2**

Esta es la segunda parte del ***Challenge Telecom X***, en este repositorio podemos encontrar los archivos relacionados con el proyecto, estos son Notebook, archivos de datos y
seriales del modelo **Champion** y el modelo para encoding de las variables.

Con base en la evaluación de los modelos utilizados (Baseline, Regresión Logística, Árbol de Decisión, Random Forest y KNN), las métricas obtenidas y el análisis de la importancia
de las variables, se decide que el modelo que mejor predice la evasión de clientes es el **Random Forest Classifier** con un balanceo de datos por *Undersampling* y tomando
solo 23 features de las 36 que componen el DF principal (codificadas por el método *One Hot Encoding*).

Para visualizar el proceso de carga y tratamiento, encoding y modelado, así como una prueba de predicción, ver el notebook adjunto. El cual se compone del siguiente indice:

<img width="1916" height="1010" alt="image" src="https://github.com/user-attachments/assets/6c33fa78-8123-4c89-ba64-cf901d0b8961" />
