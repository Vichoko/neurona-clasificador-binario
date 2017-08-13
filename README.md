# neurona-clasificador-binario
Clasificador binario implementado mediante una sola neurona (con funcion de activación sigmoidea), y su propio algoritmo de aprendizaje de pesos.

## Uso y contenidos
Mediante el método de la neurona ```train(tasaAprendizaje, inputX, inputY, expectedOutput)```, se van ajustando los pesos de este.

Se incluye el test ```testTraining``` que ejecuta un entrenamiento con 1,000,000 iteraciones, y luego se analiza la tasa de aciertos y de desaciertos para comprobar la efectividad del clasificador; mediante métricas objetivas.

Aparte se incluyen tests de compuertas logicas implementadas mediante neuronas, para probar el correcto comportamiento de estas.

## Importar
Se puede importar el proyecto con Eclipse y ejecutar los test con JUnit 4.0.
