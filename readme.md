## Modelo predictivo para casos confirmados de COVID-19

Este modelo fue creado en Tensorflow utilizando redes neuronales recurrentes para poder identificar y generar secuencias de datos. En este caso si se utiliza un modelo de regresion convencional podria determinarse un patron pero no una secuencia. 

Para generar la celda RNN se utilizo la siguiente configuracion:

1. Lotes de datos: 7 (una semana)
2. Neuronas: 100
3. Iteraciones de entrenamiento: 5000
4. Optimizador: Adam
5. Funcion de perdida: MSE

