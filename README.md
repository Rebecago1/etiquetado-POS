**Descripción**

Este proyecto presenta un **estudio comparativo entre dos herramientas de Procesamiento del Lenguaje Natural (PLN)** de código abierto, **spaCy y FreeLing**, aplicadas al análisis lingüístico de dos breves textos —uno en español y otro en italiano—.
El objetivo principal es observar las diferencias y su grado de precisión en los procesos de tokenización, lematización y etiquetado morfosintáctico (**POS *tagging***) en cada uno de los idiomas analizados.

Por lo que respecta al procesamiento del lenguaje con spaCy, se han utilizado los modelos multilingües disponibles en Python, mientras que en el caso de FreeLing, se ha empleado la versión en línea, a través de su demostrador oficial, que ofrece configuraciones idiomáticas.

**Conclusiones**

En el análisis comparativo se ha comprobado que ambas herramientas alcanzan una precisión general en torno al 83 % en los procesos de tokenización, lematización y etiquetado morfosintáctico.

Las principales **dificultades detectadas** se relacionan con las **unidades léxicas complejas, la homografía y el tratamiento de los clíticos**, fenómenos que no siguen patrones fijos y suponen un reto para los modelos automáticos.

Finalmente, se observa que el rendimiento de cada sistema refleja su finalidad: **spaCy, basado en etiquetas de *Universal Dependencies* (UD), prioriza la unificación categorial y la simplicidad estructural** para favorecer comparaciones interlingüísticas, mientras que **FreeLing, sustentado en el *tagset* EAGLES, persigue una mayor especificidad y exhaustividad morfológica**.

Finalmente, se observa que spaCy y FreeLing muestran diferente precisión, según el idioma del texto analizado. En italiano la precisión de spaCy es mayor que en español en ciertos aspectos, debido a que el corpus de base, *Italian Stanford Dependency Treebank (ISDT)*, conserva etiquetas más detalladas, en su conversión a UD, que el corpus español, UD AnCora.

**Archivos del repositorio**:

**analisis_spacy.ipynb** — cuaderno con el código de la tokenización, lematización y etiquetado POS realizadas con spaCy del texto en español.

**etiquetado_POS.pdf** — documento analítico y comparativo en el que se adjuntan los docuementos de entrada y salida, tras el etiquetado POS realizado por spaCy y FreeLing en ambos idiomas.
