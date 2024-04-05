# Algoritmo de Detección de Géneros Musicales en Spotify

Este proyecto es un algoritmo muy simple para determinar la pertenencia de una canción a diferentes géneros musicales en Spotify. El objetivo era crear un modelo adaptable que pudiera distinguir entre géneros musicales diversos, utilizando la API de Spotify para obtener las características de cada canción como base de datos.

## Funcionalidades Principales

- **Implementación en Python:** Utiliza la librería "Spotipy" para acceder a la API de Spotify y obtener datos de canciones.
- **Modelo de Clasificación:** Se emplearon métodos de árboles de decisión clasificatorios de la librería "Scikit Learn" para crear el modelo de detección de géneros musicales.
- **Adaptabilidad:** Permite generar fácilmente modelos para detectar la pertenencia de una canción entre 2 géneros distintos, con la posibilidad de cambiar los géneros estudiados.

## Pruebas y Resultados

Se realizaron 2 modelos distintos (los cuales se presentan en cada notebook en un estilo de informe) para las pruebas:
- **Pruebas Iniciales:** Se realizaron pruebas entre géneros muy diferentes como Trap y Música Clásica, obteniendo una precisión del 96% en la base de datos de testeo con un árbol de decisión sencillo.
- **Pruebas Avanzadas:** Se profundizó en géneros más similares como Rock Nacional y Cumbia Clásica, logrando una precisión del 85% en la base de datos de testeo con un árbol más complejo.

## Limitaciones y Futuras Mejoras

- **Adaptabilidad Limitada:** El modelo es altamente adaptable pero está restringido a los dos datasets de géneros musicales seleccionados, lo que limita su flexibilidad para otros géneros.
- **Posibles Mejoras:** Para futuras mejoras, se podría considerar la incorporación de más datasets de géneros musicales para ampliar la versatilidad del modelo.

## Autor

- Gonzalo Rodriguez Jannots (@GonzaRJ)
