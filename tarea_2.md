![](./images/itam_logo.png)

Noviembre 2020

### Tarea 2

Enviar a más tardar el **miércoles 11 de noviembre 2020 23:59:59 CST** por correo electrónico (liliana.millan@itam.mx) con el *subject* `md_tarea_2`.

Se quitará **1 punto** por cada día de retraso.

Tarea **individual**.

#### Instrucciones

Utilizando los datos de [Diabetes](https://www.dropbox.com/s/wnynz7b8u9rnlqz/diabetes.csv?dl=0) en mujeres de la India, queremos predecir si una mujer tendrá o no diabetes con las variables con las que contamos.

Utilizando la semilla `20201101` y árboles de decisión genera lo siguiente:

1. ¿Cuál es la etiqueta positiva?
2. Divide el conjunto de datos para que el 25% de los datos sean de pruebas. ¿Cuántas observaciones tienes en entrenamiento y pruebas?

Utiliza un `GridSearchCV` con los siguientes hiperparámetros:
+ Profundidad: 5,10,15
+ Mínimo número de elementos para definir una hoja: 3,5,7
+ Cross validation: 10
+ Scoring: Eficiencia

3. ¿Cuántos modelos generarás?
4. ¿Cuál es la variable que está en la raíz?
5. ¿Cuáles son las 3 variables que aportan más información a la predicción?

Elimina las variables que tienen menos del 7% de importancia y vuelve a generar un `GridSearchCV` con los mismos hiperparámetros que configuraste anteriormente.

Podemos tener estrictamente menos del 10% (sin incluirlo) en equivocaciones del tipo: predicción diabetes y no tener diabetes.

6. ¿Qué hiperparámetros tiene el mejor modelo?  
7. ¿Cuál es el punto de corte del modelo que cumple con las restricciones de negocio (4 decimales)?
8. ¿Qué porcentaje de FNR tendremos?
9. ¿Qué eficiencia tiene el modelo en ese punto?
10. ¿Cuál es la matriz de confusión asociada a ese punto de corte?

### ¿Qué se entrega?

+ Notebook `ipynb` con el código y las respuestas de cada pregunta.
