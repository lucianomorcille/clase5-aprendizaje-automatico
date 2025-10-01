# clase5-aprendizaje-automatico
En esta actividad debíamos elegir un dataset de nuestra preferencia y, mediante la implementación de los algoritmos Árbol de Decisión y K-NN, evaluar y comparar la precisión de los clasificadores generados.
Yo elegí trabajar con el dataset "Titanic" que trae Seaborn y estos fueron los resultados obtenidos:
**Precisión global (accuracy)**


Árbol de Decisión: 74.4 %


K-NN: 78.1 %

**Matriz de confusión**


Árbol de Decisión


Predijo correctamente:
99 pasajeros que no sobrevivieron.
61 pasajeros que sobrevivieron.
Se equivocó en:
27 casos de no sobrevivientes (los clasificó como sobrevivientes).
28 casos de sobrevivientes (los clasificó como no sobrevivientes).
K-NN
Predijo correctamente:
106 pasajeros que no sobrevivieron.
62 pasajeros que sobrevivieron.
Se equivocó en:
20 casos de no sobrevivientes.
27 casos de sobrevivientes.

**Precisión, Recall y F1-Score**
Árbol de Decisión
Clase 0 (no sobrevivió): F1 = 0.78
Clase 1 (sobrevivió): F1 = 0.69
K-NN
Clase 0: F1 = 0.82
Clase 1: F1 = 0.73

Al aplicar los algoritmos de Árbol de Decisión y K-Nearest Neighbors (K-NN) sobre el dataset Titanic, se observó que ambos modelos alcanzaron un desempeño aceptable en la tarea de clasificación de pasajeros sobrevivientes.
El Árbol de Decisión obtuvo una precisión del 74 %, mostrando la ventaja de su interpretabilidad, ya que permite identificar claramente las variables más influyentes, como el sexo, la clase del pasaje y la edad, y cómo estas determinan la supervivencia.
Por su parte, el K-NN alcanzó una precisión superior, cercana al 78 %, lo que indica una mejor capacidad de generalización en este conjunto de datos. Además, logró una leve mejora en la predicción de la clase "sobrevivió" respecto al Árbol de Decisión.
En términos generales, ambos modelos resultaron más efectivos para predecir a los pasajeros que no sobrevivieron, lo cual puede explicarse por el desbalance de la muestra (más fallecidos que sobrevivientes).
En conclusión, el Árbol de Decisión es útil cuando se busca interpretar las reglas de clasificación, mientras que el K-NN ofrece un mejor desempeño predictivo en este caso. La elección entre ambos dependerá del contexto: si se prioriza la comprensión del modelo o la precisión de las predicciones.
