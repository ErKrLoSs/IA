# Modelos de la asignatura Inteligencia Artificial de Ingeniería de Computadores de la ETSII-US

En esta carpeta de GitHhub podrás encontrar los diversos modelos que vamos usando en las clases de la asignatura. Por ahora lo que hay disponible es:

+ [**Búsquedas Ciegas (o no informadas)**](http://www.cs.us.es/~fsancho/?e=95):
  + [Busqueda Ciega.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20no%20informadas/Busqueda%20Ciega.nlogo): Un modelo que muestra cómo generar árboles en NetLogo y soluciones para su recorrido en profundidad o en anchura.
  + [BFS general.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20no%20informadas/BFS%20general.nlogo): Muestra cómo dar procedimientos generales de búsqueda en anchura haciendo uso de estructuras de listas y abstracción en las funciones que recorren las estructuras que se generan a lo largo de la búsqueda. Se ejemplifica sobre un juego numérico de búsqueda. En [BFS general-Ej Diccionario.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20no%20informadas/BFS%20general-Ej%20Diccionario.nlogo) se muestran las funciones auxiliares necesarias para un ejemplo de búsqueda en diccionarios.
  + [BFS agentes.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20no%20informadas/BFS%20agentes.nlogo): Muestra la solución a la búsqueda en anchura pero haciendo uso de agentes (turtles y links) para mantener la estructura de árbol que va generando el procedimiento de búsqueda. Se ejemplifica sobre el mismo problema de búsqueda numérica que en el caso anterior. En el modelo [BFS agentes-Hanoi.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20no%20informadas/BFS%20agentes%20-%20Hanoi.nlogo) se presenta una solución al problema de las Torres de Hanoio haciendo uso de la misma capa abstracta.
+ [**Búsquedas Informadas**](http://www.cs.us.es/~fsancho/?e=62):
  + [A-estrella Patches.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20Informadas/A-estrella%20Patches.nlogo): Algoritmo A* general de búsqueda sobre la estructura regular de patches. Se da un algoritmos general, y se ejemplifica sobre un modelo en el que se sitúan obstáculos y se puede seleccionar el par de puntos entre los que se buscará el camino más coto usando como heurística la distancia euclídea (admite moverse por 4 vecinos o por 8).
  + [A-estrella Tortugas.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20Informadas/A-estrella%20Tortugas.nlogo): Algoritmo A* general de búsqueda sobre una estructura de grafo cualquier. Se da un algoritmo general, y se ejemplifica sobre un modelo de grafo geométrico usando como heurística la distancia euclídea.
  + [a-star_2009.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20Informadas/a-star_2009.nlogo): Modelo creado por James P. Steiner en el que se muestra la influciencia de diversas heurísticas en la aplicación del algoritmo A* para encontrar los caminos más cortos entre patches.
+ [**Búsquedas Locales**](http://www.cs.us.es/~fsancho/?e=96):
  + [Ascenso Colina.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20Locales/Ascenso%20Colina.nlogo): Modelo básico de demostración del algoritmo de Ascenso de la colina usando los patches como estructura de datos con valores a optimizar. También se ofrece una [versión 3D](https://github.com/fsancho/IA/blob/master/Busquedas%20Locales/Ascenso%20Colina%203D.nlogo3d) del mismo problema, para ser usada con NetLogo3D.
  + [Templado Simulado.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20Locales/Templado%20Simulado.nlogo): Ejemplo básico de la metodología del Templado simulado para optimización de problemas.
