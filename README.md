# Investigacion-operativa

Enunciado

Uno de los enfoques clásicos de la investigación operativa es la teoría de grafos. Podemos
pensar que un grafo es un conjunto de nodos (o vértices) y aristas (flechas). Un grafo puede
usarse, entre muchas otras aplicaciones diversas, para representar conexiones entre puntos
geográficos, o rutas entre ciudades, o calles entre esquinas dentro de una misma ciudad. Un
enfoque similar usa el googlemaps cuando pedimos direcciones a algún lugar.
Imaginar un punto de origen (1) y un punto de destino (8) en un grafo que representa posibles
rutas entre (1) y (8).

![image](https://user-images.githubusercontent.com/102690796/169887622-7099f5e2-253d-4a44-9574-769ee2fa5578.png)

El problema que hay que resolver es determinar cuál es la ruta óptima que minimiza la distancia
recorrida para ir de (1) a (8), suponiendo que las distancias entre los nodos son conocidas y los
sentidos posibles son solamente los marcados con las aristas del grafo.

Suponga que la distancias no son euclídeas y que existe un nuevo camino entre 1 y 6. Se pide
definir una función que tome como parámetro (w) la distancia entre 1 y 6 del nuevo camino y
devuelva, luego de plantear el modelo y resolver, la distancia total óptima de acuerdo con el
camino más corto entre 1 y 8, considerando como posible la nueva ruta. Responder el valor de
la distancia recorrida total para valores de w de 10, 400,y 3000

En el archivo function_103904.py se muestra la resolución de este ejercicio
