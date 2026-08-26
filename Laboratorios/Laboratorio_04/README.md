# Regresión Logística Binaria - Incumplimiento de Pago

Laboratorio de regresión logística binaria para predecir si un cliente incumplirá el pago del próximo mes.

## Dataset
- 30.000 ejemplos
- 23 características predictoras
- Variable objetivo: `default payment next month`
- Clase 0: No incumple
- Clase 1: Incumple

## Metodología
- Preprocesamiento con Pandas.
- 80% de los datos para entrenamiento.
- 20% para prueba.
- Normalización de características.
- Función sigmoide.
- Función de costo.
- Descenso de gradiente para determinar los parámetros θ.

## Resultados
- Costo final aproximado: 0.463
- Exactitud en prueba: 80.78%
- Datos utilizados para prueba: 6.000

El modelo logró converger correctamente y obtuvo un desempeño aproximado del 80.78% sobre datos que no participaron en el entrenamiento.
