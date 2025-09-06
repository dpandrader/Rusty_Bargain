🚗 Proyecto – Predicción del Valor de Coches de Segunda Mano

Objetivo del proyecto:

Desarrollar un modelo de machine learning para estimar el valor de mercado de coches de segunda mano en la plataforma Rusty Bargain, evaluando no solo la calidad de la predicción, sino también la velocidad de inferencia y el tiempo de entrenamiento.

Procedimientos:

Exploración y análisis de los datos disponibles: historial, especificaciones técnicas, versiones de equipamiento y precios.
Entrenamiento de distintos modelos de regresión, incluyendo árbol de decisión, Random Forest, regresión lineal y Gradient Boosting.
Comparación de modelos con diferentes hiperparámetros, midiendo tanto la precisión como la eficiencia en el entrenamiento y predicción.
Selección del modelo más adecuado en función de métricas de error (RMSE), velocidad de predicción y escalabilidad.

Conclusiones:

El modelo basado en Gradient Boosting ofreció la mejor combinación entre precisión y velocidad de predicción.
Se cumplió el objetivo de predecir de manera confiable el valor de mercado de los coches, optimizando a la vez el rendimiento computacional.
Todo el flujo de trabajo se implementó con Python, pandas, scikit-learn, LightGBM, matplotlib y seaborn.
