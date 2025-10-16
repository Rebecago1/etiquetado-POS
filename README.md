**Descripción**

Este proyecto, surgido a partir de una tarea propuesta en la asignatura *Etiquetado POS y lematización*, perteneciente al Máster Universitario en Procesamiento dle Lenguaje y aplicaciones de la IA a la Lingüística de la Universidad de La Rioja, presenta un **estudio comparativo entre dos herramientas de Procesamiento del Lenguaje Natural (PLN)** de código abierto, **spaCy y FreeLing**, aplicadas al análisis lingüístico de dos breves textos —uno en español y otro en italiano—.
El objetivo principal es observar las diferencias y el grado de precisión en los procesos de tokenización, lematización y etiquetado morfosintáctico (**POS *tagging***) en cada uno de los sistemas analizados.

Por lo que respecta al procesamiento del lenguaje con spaCy, se han utilizado los modelos multilingües disponibles en Python, mientras que en el caso de FreeLing, se ha empleado la versión en línea, a través de su demostrador oficial, que ofrece configuraciones idiomáticas.

**Conclusiones**

En el análisis comparativo se ha comprobado que ambas herramientas alcanzan una precisión general en torno al 83 % en los procesos de tokenización, lematización y etiquetado morfosintáctico.

Las principales **dificultades detectadas** se relacionan con las **unidades léxicas complejas, la homografía y el tratamiento de los clíticos**, fenómenos que no siguen patrones fijos y suponen un reto para los modelos automáticos.

Además, se observa que el rendimiento de cada sistema refleja su finalidad: **spaCy, basado en etiquetas de *Universal Dependencies* (UD), prioriza la unificación categorial y la simplicidad estructural** para favorecer comparaciones interlingüísticas, mientras que **FreeLing, sustentado en el *tagset* EAGLES, persigue una mayor especificidad y exhaustividad morfológica**.

Finalmente, se aprecia que spaCy y FreeLing muestran diferente precisión, según el idioma del texto analizado. **En italiano la precisión de spaCy es mayor que en español** en ciertos aspectos, debido a que el corpus de base, *Italian Stanford Dependency Treebank (ISDT)*, conserva etiquetas más detalladas, en su conversión a UD, que el corpus español, UD AnCora.

**Archivos del repositorio**:

**POS_spaCy.ipynb**: cuaderno de *Jupyter* con el código en lenguaje de programación Python de la tokenización, lematización y etiquetado POS realizadas con spaCy de los textos en español e italiano.

**etiquetado_POS.pdf**: documento analítico y comparativo en el que se adjuntan los textos de entrada y salida, tras el etiquetado POS realizado por spaCy y FreeLing en ambos idiomas.

**Librería y herramienta empleada para el PLN**: spaCy (Python) y FreeLing (versión web).


