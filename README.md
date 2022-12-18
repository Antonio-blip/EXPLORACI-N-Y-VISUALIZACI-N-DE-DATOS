# Exploración y visualización de datos

Se intenta responder a la pregunta de si hay una relación directa entre las expectativas de los consumidores a la hora de puntuar un alojamiento y el precio del mismo. Se utilizan los vecindarios como grupos principales.

El primer gráfico enfrenta las puntuaciones medias de los clientes que oscilan en valores del 70 al 100 (por ello se recorta el gráfico) con el precio promedio.

Al mismo tiempo basándonos en los datos se crea una escala legible que traduce el valor resultante de dividir Review Scores Rating entre Averaga price como Best quality, Good quality, average quality y poor quality, siendo el primer grupo teoricamente mejor que el último.

En el segundo gráfico podemos ver un topN interactivo en el que podemos seleccionar el número de valores y clicar en él por si quisiesemos localizar alguno de los valores en el gráfico 1.

En el tercer gráfico se realiza una comparativa de cuanta mejoría ha habido entre los años 2014 y 2016 que funciona con el mismo topN que el gráfico anterior, se traduce a porcentaje, así si la división resultante de rating/precio promedio pasa de 2puntos a 4puntos habrá mejorado un 100%.

Se añaden otros gráficos como el de año que actua sobre los dos primeros gráficos para poder navegar a lo largo de la historia de los vecindarios, el de grupos de calidad y el de vecindarios por si quisieramos reducir la muestra, para este último menester se duplica la columna de vecindario y se convierte en contexto para la preferencia de cálculo por delante de los top N.

