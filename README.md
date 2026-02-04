Clasificación usando Regresión Logística, Árboles de Decisión y SVM
📊 Data obtenida desde
[Data](https://www.kaggle.com/datasets/umerrtx/machine-failure-prediction-using-sensor-data)

📌 Resumen del problema

El objetivo de este proyecto es resolver un problema de clasificación supervisada, comparando el desempeño de distintos modelos de Machine Learning.
A partir de un conjunto de datos con variables numéricas, se busca predecir la clase objetivo y determinar qué algoritmo ofrece el mejor equilibrio entre precisión, generalización e interpretabilidad.

El estudio se enfoca en responder las siguientes preguntas:

¿Qué modelo clasifica mejor los datos?
¿Qué tan estables son los modelos frente a los datos?

🧪 Metodología
1. Exploración y preparación de datos

Se realizó un análisis exploratorio (EDA) para comprender la distribución de las variables y la variable objetivo.
Se verificó la ausencia de valores nulos críticos y se analizaron las escalas de las variables.
Debido a que algunos modelos son sensibles a la escala, se aplicó escalado de características usando StandardScaler.

2. División del conjunto de datos

El dataset fue dividido en:
Conjunto de entrenamiento 80% de la data
Conjunto de prueba 20% de la data

3. Modelos implementados

Se entrenaron y evaluaron tres algoritmos de clasificación:

🔹 Regresión Logística
🔹 Árbol de Decisión
🔹 Support Vector Machine (SVM) con kernel RBF.

4. Evaluación de modelos

Los modelos fueron evaluados utilizando:
🔹 Accuracy
🔹 Matriz de confusión
🔹 Validación cruzada (cross-validation)

📊 Resultados generales

SVM obtuvo el mejor desempeño global y mayor capacidad de generalización.
Árbol de Decisión presentó un buen equilibrio entre rendimiento e interpretabilidad.
Regresión Logística mostró un desempeño aceptable, pero limitado en problemas no lineales.

