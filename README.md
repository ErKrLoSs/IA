# Modelos de la asignatura Inteligencia Artificial de Ingeniería de Computadores de la ETSII-US

En esta carpeta de GitHhub podrás encontrar los diversos modelos que vamos usando en las clases de la asignatura. Por ahora lo que hay disponible es:

+ [**Búsquedas Ciegas (o no informadas)**](http://www.cs.us.es/~fsancho/?e=95):
  + [Busqueda Ciega.nlogo](https://raw.githubusercontent.com/fsancho/IA/blob/master/Busquedas%20no%20informadas/Busqueda%20Ciega.nlogo): Un modelo que muestra cómo generar árboles en NetLogo y soluciones para su recorrido en profundidad o en anchura.
  + [BFS general.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20no%20informadas/BFS%20general.nlogo): Muestra cómo dar procedimientos generales de búsqueda en anchura haciendo uso de estructuras de listas y abstracción en las funciones que recorren las estructuras que se generan a lo largo de la búsqueda. Se ejemplifica sobre un juego numérico de búsqueda. En [BFS general-Ej Diccionario.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20no%20informadas/BFS%20general-Ej%20Diccionario.nlogo) se muestran las funciones auxiliares necesarias para un ejemplo de búsqueda en diccionarios.
  + [BFS agentes.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20no%20informadas/BFS%20agentes.nlogo): Muestra la solución a la búsqueda en anchura pero haciendo uso de agentes (turtles y links) para mantener la estructura de árbol que va generando el procedimiento de búsqueda. Se ejemplifica sobre el mismo problema de búsqueda numérica que en el caso anterior. En el modelo [BFS agentes-Hanoi.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20no%20informadas/BFS%20agentes%20-%20Hanoi.nlogo) se presenta una solución al problema de las Torres de Hanoio haciendo uso de la misma capa abstracta.
+ [**Búsquedas Informadas**](http://www.cs.us.es/~fsancho/?e=62):
  + [A-estrella Patches.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20Informadas/A-estrella%20Patches.nlogo): Algoritmo A* general de búsqueda sobre la estructura regular de patches. Se da un algoritmos general, y se ejemplifica sobre un modelo en el que se sitúan obstáculos y se puede seleccionar el par de puntos entre los que se buscará el camino más coto usando como heurística la distancia euclídea (admite moverse por 4 vecinos o por 8).
  + [A-estrella Tortugas.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20Informadas/A-estrella%20Tortugas.nlogo): Algoritmo A* general de búsqueda sobre una estructura de grafo cualquier. Se da un algoritmo general, y se ejemplifica sobre un modelo de grafo geométrico usando como heurística la distancia euclídea.
  + [a-star_2009.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20Informadas/a-star_2009.nlogo): Modelo creado por James P. Steiner en el que se muestra la influciencia de diversas heurísticas en la aplicación del algoritmo A* para encontrar los caminos más cortos entre patches.
+ [**Búsquedas Locales**](http://www.cs.us.es/~fsancho/?e=96):
  + [Ascenso Colina.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20Locales/Ascenso%20Colina.nlogo): Modelo básico de demostración del algoritmo de Ascenso de la colina usando los patches como estructura de datos con valores a optimizar. También se ofrece una [versión 3D](https://github.com/fsancho/IA/blob/master/Busquedas%20Locales/Ascenso%20Colina%203D.nlogo3d) del mismo problema, para ser usada con NetLogo3D.
  + [Templado Simulado.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20Locales/Templado%20Simulado.nlogo): Ejemplo básico de la metodología del Templado simulado para optimización de problemas.
  + [Nonograma TS.nlogo](https://github.com/fsancho/IA/blob/master/Busquedas%20Locales/Nonograma%20TS.nlogo): Un ejemplo de cómo usar el método de Templado Simulado para resolver (a veces) puzles de nonogramas.
+ [**Lógica**](http://www.cs.us.es/~fsancho/?e=120):
  + [Resolución LP.nlogo](https://github.com/fsancho/IA/blob/master/Logica/Resolucion%20LP.nlogo): Demostración gráfica del método de Resolución para la Lógica Proposicional.
+ [**Computación Evolutiva**](http://www.cs.us.es/~fsancho/?e=65):
  + [Biomorphs Girasol.nlogo](https://github.com/fsancho/IA/blob/master/Computacion%20Evolutiva/Biomorphs%20Girasol.nlogo): Modelo básico de demostración de reproducción sexual y asexual para analizar cómo se puede dirigir la descendencia.
  + [Tiburones y pececillos evolutivos.nlogo](https://github.com/fsancho/IA/blob/master/Computacion%20Evolutiva/Tiburones%20y%20pececillos%20evolutivos.nlogo): Un ejemplo de optimizción por selección natural en entornos hostiles.
  + [Paisaje Evolutivo.nlogo](https://github.com/fsancho/IA/blob/master/Computacion%20Evolutiva/Paisaje%20Evolutivo.nlogo): Muestra cómo los métodos de optimización por poblaciones pueden ser eficientes cuando las condiciones del problema cambian dinámicamente.
  + [Algoritmo Genético.nlogo](https://github.com/fsancho/IA/blob/master/Computacion%20Evolutiva/Algoritmo%20Genetico.nlogo): Ejemplo muy básico de algoritmo genético para la optimización de un problema.
+ [**Optimización con Hormigas**](http://www.cs.us.es/~fsancho/?e=71)[ **y PSO**](http://www.cs.us.es/~fsancho/?e=70):
  + [AntSystem.nlogo](https://github.com/fsancho/IA/blob/master/Optimizacion_AS_PSO/AntSystem.nlogo): Resolución clásica del problema TSP haciendo uso de colonias de hormigas.
  + [Particle Swarm Optimization.nlogo](https://github.com/fsancho/IA/blob/master/Optimizacion_AS_PSO/Particle%20Swarm%20Optimization.nlogo): Un ejemplo de optimización de funciones bidimensionales haciendo uso de enjambres de partículas.
  + [PSO Trafico1D.nlogo](https://github.com/fsancho/IA/blob/master/Optimizacion_AS_PSO/PSO%20Trafico1D.nlogo): Uso de PSO para optimización de parámetros de modelos de simulación. En este caso, hace uso de Muestra cómo los métodos de optimización por poblaciones pueden ser eficientes cuando las condiciones del problema cambian dinámicamente.
+ [**Simulación Social**](http://www.cs.us.es/~fsancho/?e=52):
  + [Difusión Cultural.nlogo](https://github.com/fsancho/IA/blob/master/Simulacion%20Social/Difusion%20Cultural.nlogo): Modelo de difusión cultural de Axelrod. Puedes encontrar un artículo sobre el tema [aquí](http://jasss.soc.surrey.ac.uk/12/1/6/appendixB/Axelrod1997.html)
  + [Segregacion.nlogo](https://github.com/fsancho/IA/blob/master/Simulacion%20Social/Segregacion.nlogo): Modelo de segregación de [Schelling](http://blog.pseudolog.com/article/el-tablero-de-ajedrez-de-thomas-schelling).
  + [Voto.nlogo](https://github.com/fsancho/IA/blob/master/Simulacion%20Social/Voto.nlogo): Modelo simple de votación en malla cuadrada. En este caso, se muestra cómo pueden darse interpretaciones sociales a partir de un autómata celular muy simple.
  + [Distribucion Riqueza.nlogo](https://github.com/fsancho/IA/blob/master/Simulacion%20Social/DistribucionRiqueza.nlogo): Modelo de distribución de riqueza en un entorno simple que muestra que, bajo ciertas condiciones de distribución y acceso, se tiende a cumplir el [Principio de Pareto](https://www.wikiwand.com/es/Principio_de_Pareto).
  + [PD Iterado Evolutivo.nlogo](https://github.com/fsancho/IA/blob/master/Simulacion%20Social/PD%20Iterado%20Evolutivo.nlogo): Versión Iterada y evolutiva del [Dilema del Prisionero](https://www.wikiwand.com/es/Dilema_del_prisionero).
  + [Anasazi.zip](https://github.com/fsancho/IA/blob/master/Simulacion%20Social/Anasazi%20NetLogo.zip): Paquete ZIP con los ficheros relacionados con la simulación de evolución de la cultura [Anasazi](https://www.wikiwand.com/es/Anasazi). Puedes encontrar el artículo original sobre esta simulación [aquí](http://jasss.soc.surrey.ac.uk/12/4/13.html).
+ [**Aprendizaje Automático**](http://www.cs.us.es/~fsancho/?e=75):
  + [K-Medias.nlogo](https://github.com/fsancho/IA/blob/master/Aprendizaje%20Automatico/K-medias2.nlogo): Ejemplo de cómo implementar el algoritmo de K-medias en dimensión 2. Además, presenta una primera aproximación a encontrar el número de clusters óptimo.
  + [ID3.nlogo](https://github.com/fsancho/IA/blob/master/Aprendizaje%20Automatico/ID3.zip): Paquete ZIP con el algoritmo ID3 y algunos ejemplos de demostración. Solo trabaja sobre variables categóricas, no considera variables numéricas continuas.
  + [SOM.nlogo](https://github.com/fsancho/IA/blob/master/Aprendizaje%20Automatico/SOM2015.zip): Paquete ZIP con el algoritmo Self-Optimization Maps con algunos ejemplos de demostración. Vienen dos versiones: malla cuadrada y malla hexagonal.
  + [Redes Neuronales.nlogo](https://github.com/fsancho/IA/blob/master/Aprendizaje%20Automatico/Redes%20Neuronales.zip): Paquete ZIP con un algoritmo de aprendizaje que hace uso de Back Propagation para aprender caracteres. viene con algunos ejemplos de demostración que se pueden precargar (dígitos, letras mayúsculas y letras minúsculas) 
  + [Smart Sweepers.nlogo](https://github.com/fsancho/IA/blob/master/Aprendizaje%20Automatico/smart_sweepers.zip): Paquete ZIP con una demostración de cómo aplicar algoritmos genéticos para optimizar redes neuronales con un fin prefijado. En este caso, se intenta aprender el movimiento de un par de motores de un robot para alcanzar comida en el entorno. 
  + [Q-Learning.zip](https://github.com/fsancho/IA/blob/master/Aprendizaje%20Automatico/QLearning%20-%20Hanoi.nlogo): Ejemplo del algoritmo por refuerzo Q-Learning para aprender busquedas en espacios de estado. Se ejemplifica con la búsqueda de la solución óptima en el problema de las Torres de Hanoi.
