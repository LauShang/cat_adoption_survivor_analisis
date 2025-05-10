# Análisis de Supervivencia en Gatos

## Descripción

Este proyecto tiene como objetivo analizar el tiempo que tarda un gato en ser adoptado en función de su color. El análisis se basa en un conjunto de datos de un refugio de animales de Austin, con información sobre más de 22,000 gatos. El análisis utiliza un **modelo de supervivencia** para estudiar cómo el color del gato afecta al tiempo hasta la adopción, considerando diferentes factores que influyen en este proceso.

## Objetivo

El objetivo principal es entender si el color del gato tiene un impacto significativo en el tiempo que tarda en ser adoptado. Esto puede ser útil para los refugios de animales al momento de gestionar sus recursos y priorizar la adopción de gatos que podrían estar esperando más tiempo.

## Datos

Los datos utilizados en este análisis provienen de un refugio de animales de Austin. Incluyen información sobre:

- **Color del gato**: Si el gato es negro o de otro color.
- **Tiempo hasta la adopción**: Cuánto tiempo tardó el gato en ser adoptado (en días).
- **Evento de adopción**: Indica si el gato fue adoptado o si el tiempo de observación terminó antes de la adopción.

## Metodología

Se utiliza un modelo de supervivencia exponencial para predecir el tiempo hasta la adopción de los gatos, en función de su color. El análisis se basa en la teoría estadística presentada en el libro *Statistical Rethinking* de Richard McElreath.

## Resultados Esperados

Se espera que el análisis revele si existe una diferencia significativa en los tiempos de adopción entre los gatos de color negro y los de otros colores. Los resultados del modelo ayudarán a comprender cómo las características de los gatos pueden influir en su adopción.


