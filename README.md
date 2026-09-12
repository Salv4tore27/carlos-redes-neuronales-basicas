# Redes neuronales básicas con NumPy

[![Abrir en Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Salv4tore27/carlos-redes-neuronales-basicas/blob/main/carlos_redes_neuronales_basicas.ipynb)

Este proyecto recorre el aprendizaje neuronal desde una frontera lineal hasta una red con capa oculta. Todos los cálculos se construyen directamente con **Python y NumPy**, de modo que sea posible observar cómo cambian los pesos, el sesgo y la pérdida durante el entrenamiento.

## Recorrido del notebook

| Etapa | Problema | Modelo | Elemento principal |
|---|---|---|---|
| 1 | Compuertas AND y OR | Perceptrón | Regla de actualización basada en el error |
| 2 | Clasificación OR | Neurona sigmoide | Descenso de gradiente y entropía cruzada |
| 3 | Compuerta XOR | Red `2-4-1` | Capa oculta `tanh` y retropropagación |

El caso XOR cierra el recorrido porque demuestra por qué una sola frontera lineal no siempre es suficiente y cuándo se necesita una representación intermedia.

## Qué se comprueba

- Predicciones correctas para las tablas de verdad trabajadas.
- Reducción de la pérdida durante el entrenamiento.
- Formas coherentes de las matrices de pesos.
- Reproducibilidad mediante semillas aleatorias fijas.
- Exactitud final del 100 % en los tres ejercicios.

## Archivo principal

- `carlos_redes_neuronales_basicas.ipynb`: explicaciones, implementaciones, resultados y pruebas automáticas.

No se utilizan TensorFlow, Keras ni PyTorch. El propósito es mostrar las operaciones internas de cada modelo antes de recurrir a bibliotecas de alto nivel.
