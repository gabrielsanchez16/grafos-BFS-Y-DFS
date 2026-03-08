# Análisis de BFS y DFS en Grafos

## Autor

### Gabriel Sánchez
### Estudiante de Ingeniería de Sistemas
### Universidad del Pacífico

---

## Introducción

Este proyecto lo desarrollé con el objetivo de comprender de forma práctica el funcionamiento de dos algoritmos fundamentales en el recorrido de grafos: **Breadth First Search (BFS)** y **Depth First Search (DFS)**.

Durante el estudio de estructuras de datos y algoritmos, estos métodos aparecen con frecuencia como herramientas básicas para explorar grafos, encontrar caminos entre nodos y resolver diversos problemas computacionales. Sin embargo, muchas veces su explicación queda en el plano teórico.

Por esta razón decidí realizar una implementación en **Python** que permitiera visualizar su comportamiento y comparar algunos aspectos de su ejecución, especialmente el **camino encontrado y el uso de memoria**.

El enfoque de este trabajo se centra en demostrar de manera clara cómo cada algoritmo explora un grafo y qué diferencias prácticas pueden observarse entre ambos.

---

## Objetivo del proyecto

El propósito principal de este ejercicio fue implementar y analizar los algoritmos BFS y DFS aplicados a un grafo pequeño, con el fin de:

* Comprender su lógica de funcionamiento paso a paso.
* Visualizar cómo se realiza el recorrido en cada algoritmo.
* Comparar el camino encontrado entre dos nodos.
* Analizar el uso de memoria durante la ejecución.
* Representar el grafo de manera visual para facilitar la interpretación.

Además, busqué que el proyecto no se limitara únicamente al código, sino que también incluyera una pequeña **interfaz interactiva** que permitiera experimentar con diferentes nodos de inicio y destino.

---

## Enfoque del desarrollo

Para desarrollar este ejercicio utilicé **Python en Google Colab**, lo cual permite ejecutar el código directamente desde el navegador y visualizar los resultados de manera interactiva.

También decidí utilizar la librería **NetworkX**, ya que facilita la creación y visualización de grafos, permitiendo observar gráficamente cómo están conectados los nodos.

El proceso general del proyecto fue el siguiente:

1. Crear un grafo pequeño de ejemplo.
2. Representar visualmente la estructura del grafo.
3. Implementar desde cero los algoritmos BFS y DFS.
4. Ejecutar ambos algoritmos para encontrar un camino entre dos nodos.
5. Medir el uso de memoria durante la ejecución.
6. Comparar los resultados obtenidos.

---

## Sobre los algoritmos analizados

### Breadth First Search (BFS)

El algoritmo BFS realiza una búsqueda **por niveles**, explorando primero todos los vecinos cercanos al nodo inicial antes de continuar hacia niveles más profundos del grafo.

Durante la investigación y las pruebas realizadas en este proyecto, pude observar que BFS suele encontrar **el camino más corto entre dos nodos** cuando el grafo no tiene pesos en sus aristas. Sin embargo, también puede requerir **más memoria**, ya que mantiene una estructura de cola con múltiples caminos posibles.

---

### Depth First Search (DFS)

El algoritmo DFS, por otro lado, sigue una estrategia diferente: explora el grafo **en profundidad**, avanzando lo más posible por un camino antes de retroceder.

En las pruebas realizadas, noté que DFS puede encontrar una solución rápidamente en algunos casos, pero no necesariamente el camino más corto. A diferencia de BFS, suele utilizar menos memoria, ya que su estructura principal se basa en una pila.

---

## Resultados observados

Al ejecutar ambos algoritmos sobre el mismo grafo, se pudieron observar algunas diferencias interesantes:

* **BFS** tiende a encontrar el camino más corto entre el nodo inicial y el nodo objetivo.
* **DFS** puede encontrar un camino diferente dependiendo del orden de exploración.
* El consumo de memoria varía entre ambos algoritmos debido a las estructuras de datos que utilizan.

La visualización del grafo también facilita entender cómo cada algoritmo recorre los nodos.

---

## Tecnologías utilizadas

Para la implementación del proyecto utilicé las siguientes herramientas:

* Python
* Google Colab
* NetworkX
* Matplotlib
* ipywidgets

Estas herramientas permitieron construir tanto la lógica del algoritmo como la parte visual del análisis.

---

## Cómo ejecutar el proyecto

Para ejecutar el proyecto se deben seguir los siguientes pasos:

1. Abrir el notebook en **Google Colab**.
2. Ejecutar las celdas en orden.
3. Seleccionar el nodo inicial y el nodo objetivo desde la interfaz.
4. Ejecutar el análisis.
5. Observar el camino encontrado por cada algoritmo y la comparación de memoria.
6. Link del proyecto https://colab.research.google.com/drive/1UlgsmpkYfhkS-H0lBfpatqdgT7k1XtHT?usp=sharing

---

## Reflexión final

Desde mi perspectiva, implementar estos algoritmos de forma práctica fue una manera muy útil de comprender realmente cómo funcionan los recorridos en grafos.

Aunque en teoría BFS y DFS pueden parecer similares, al implementarlos y visualizar su comportamiento se hace evidente que cada uno sigue una estrategia distinta de exploración.

Este ejercicio me permitió reforzar conceptos fundamentales de **estructuras de datos, algoritmos y representación de grafos**, además de mostrar cómo herramientas de visualización pueden ayudar a entender mejor procesos que normalmente se explican solo de forma conceptual.

---

## Repositorio

Este repositorio contiene el notebook desarrollado en Google Colab junto con el código utilizado para implementar y analizar los algoritmos BFS y DFS.

