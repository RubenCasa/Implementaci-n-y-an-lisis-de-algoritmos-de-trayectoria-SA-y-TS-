^_~ Contexto del Proyecto
Este proyecto fue desarrollado como parte de la Actividad Autónoma (AA U2T1) para la asignatura de Metaheurísticas. El objetivo principal no es solo aplicar librerías, sino construir la lógica interna de SA y TS para comprender y comparar sus mecanismos fundamentales de exploración y escape de óptimos locales.

🛠️ Contenido del Repositorio
El script principal AA3_rubendcasa.ipynb incluye:

Definición del Problema: Un conjunto de 6 ciudades de Ecuador con coordenadas (x, y) simplificadas.

Algoritmos Base:

Una función simulated_annealing_basico() que implementa la lógica de enfriamiento y la probabilidad de aceptación de Boltzmann.

Una función tabu_search_basico() que implementa la gestión de una "lista tabú" (memoria a corto plazo) para evitar ciclos.

Registro de Resultados: El script mide y reporta la solución final (distancia), el tiempo de ejecución y el número de iteraciones.

Visualización: Utiliza matplotlib para generar una comparativa gráfica de la ruta inicial vs. las rutas optimizadas por SA y TS.
